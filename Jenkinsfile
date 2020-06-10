pipeline{ 
  parameters {
    choice(name: 'namespace', choices: ['Dev', 'QA'], description: 'choose env')
    extendedChoice(name: 'Git/Bucket',type: 'PT_CHECKBOX', value:'https://github.com/pradeep9795/hello-world.git',description: 'choose git')}
   agent any
	   stages {
	        stage ('SCM checkout'){
				  steps {
				       git branch:'master',
               url:'https://github.com/pradeep9795/hello-world.git'
				        }
				      }
				      	
			
                   }	
}
