pipeline{ 
  parameters {
    choice(name: 'namespace', choices: ['Dev', 'QA'], description: 'choose env')
    extendedChoice(name: 'Git/Bucket',type: 'PT_CHECKBOX', 'https://github.com/devopsankur/alokdemo.git',description: 'choose git')}
   agent any
	   stages {
	        stage ('SCM checkout'){
				  steps {
				       git branch:'master',
               url:'https://github.com/devopsankur/alokdemo.git'
				        }
				      }
				      	
			
                   }	
}
