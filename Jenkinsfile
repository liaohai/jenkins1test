pipeline{
agent any
stages{
     stage("get code"){
	    steps{
		       git clone git@github.com:liaohai/jenkins1test.git
		}
	 }
	 stage("package"){
	    steps{
		      echo "package"
		}
	  } 
	  stage("deploy"){
	    steps{
			  echo "deploy" 
		}
	  } 
    }  
}
