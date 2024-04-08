node("yasha") {
    stage('Checkout') {
        steps {
           git branch: 'main', url: 'https://github.com/Yasha12345656786/MySoftware2.git'
        }
    }

    stage('Push Changes') {
        steps {
            dir('MySoftware2') {
                bat 'git push origin main'
            }
        }
    }
}