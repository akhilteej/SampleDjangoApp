pipeline{
   agent any 

   stages {
    stage ("prepare") {
          steps {
          sh 'eb deploy --staged'
                   
         }
    }

   }
}
