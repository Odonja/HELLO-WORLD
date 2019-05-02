node{
    stage('SCM Checkout'){
        git 'https://github.com/Odonja/HELLO-WORLD'
    }
    stage('Compile-Package'){
        sh 'mvn package'
    }
}