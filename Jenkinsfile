node{
    git branch: 'main', url: 'https://github.com/ahmedelgareep/simple-java-maven-app.git'

    stage('Build'){

        try{
            sh'echo "build in progress"'

        }
        catch(Exception e){
            echo " exceptionin found"
            throw e
        }
            
    }

      stage('Test') {

        if (env.BRANCH_NAME == 'mastfeater') {
            echo 'test stage'
        } else {
            echo 'skip Test stage'
        }
    }

    stage('Deploy') { 
         
    }

}
