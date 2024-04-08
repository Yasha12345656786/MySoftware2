node("yasha") {
    stage('Checkout') {
           git branch: 'main', url: 'https://github.com/Yasha12345656786/MySoftware2.git'
    }
    stage('make Changes'){
       bat 'echo print("hELLO") > new.py'
       bat 'git add .'
       bat  'git commit -m "Commit NEWPY"'

    }
    stage('Push Changes') {
        bat 'git push origin main'
    }
}