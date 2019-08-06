
pipeline{

     agent any
      
     stages{
     stage('CheckoutCodefromScm')
{
      steps{

      git 'https://github.com/kirankurakugit/RestApiHelloWorld.git'

     echo "checkoutcode from scm is successfull"
    }
    }
    
   stage('Build'){
    steps{
   mvn clean package
  echo "buiild
    }
        stage("deploy"){
             
        }
     
   
}
