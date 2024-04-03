pipeline {
    agent {
  label 'linux'
    }

    stages {
        stage('First') {
            steps {
                git credentialsId: 'git_https',
                url: 'https://github.com/Evgenyi26rus/vector-role.git',
                branch: 'master'
            }
        }
        stage('Second') {
            steps {
                sh 'pip3 install ansible-lint yamllint'
                sh 'pip install "molecule[lint]"'
                sh 'pip install "molecule[docker,lint]"'
            }
        }
        stage('Dalee test') {
            steps {
                echo 'TEST'
                sh 'molecule test'
            }
        }
    }
}
