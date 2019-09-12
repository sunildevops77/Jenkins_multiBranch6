node('master')

{

stage('Continuous Download_Master') 
   
	 {
	
    git 'https://github.com/sunildevops77/maven.git'
    
	}

stage('Continuous build_Master') 
   
	 {
	
   sh label: '', script: 'mvn package'
	}

}


