node('master')

{

stage('Continuous Download_Loans') 
   
	 {
	
    git 'https://github.com/sunildevops77/maven.git'
    
	}

stage('Continuous build_Loans') 
   
	 {
	
   sh label: '', script: 'mvn package'
	}


}


