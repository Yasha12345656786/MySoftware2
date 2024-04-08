node("yasha"){
     stage('Checkout') {
            steps {
                // Checkout the code from your Git repository
                bat 'git clone https://github.com/your-username/your-repository.git'
            }
     stage('Make Changes and Commit') {
            steps {
                // Make changes to your files
                bat 'echo This is a new line >> myfile.txt'

                // Add the changes to the Git staging area
                bat 'git add .'

                // Commit the changes with a commit message
                bat 'git commit -m "Automated commit via Jenkins pipeline"'
            }
     stage('Push Changes') {
           steps {
               // Push the changes to the remote repository
               bat 'git push origin master'
           }
}