pipeline {
    agent { docker { image 'nginx' } }
    stages {
        stage('build') {
            steps {
                sh 'pwd'
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
		sh 'echo $USER'
            }
        }
    }
}
