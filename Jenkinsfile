node {
    stage('clone') {
        git 'https://github.com/Gironald007/jenkins-helloworld.git'
    
    }
    
    stage('Build') {
        sh 'javac Main.java'
    
    }
    
    stage('Run') {
        sh 'java Main'
    
    }
}
