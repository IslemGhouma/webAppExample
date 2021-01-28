pipeline
{
 	agent any
	tools
		{
			maven 'maven3.6'
		}
	
	stages
		{
			stage('build application')
				{
   					steps
						{
							bat 'mvn clean package'
						}
				}		
		}
}