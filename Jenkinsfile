// Just an empty file to start

stage("outside node clause") {
    sh "echo Outside Node clause"
}

node ("container") {

    checkout scm
    
    stage("test echo") {
        sh "echo Hello"
    }
}
