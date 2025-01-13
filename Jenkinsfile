node {
    stage('clone') {
        git 'https://github.com/DIAS35/jenkins-helloworld-2.git'
    }

    stage('build') {
        sh '''
            javac Main.java
        '''
    }

    stage('run') {
        sh 'java Main'
    }
}
