pipeline
{


agent any



stages
{
     stage ("scm checkout"){
     git 'https://github.com/sachidud/maven-project'
     }

}
{
      stage ("testing stage")
	{
	      steps{
                   withMaven(maven: 'LocalMaven')
		      {
                        sh 'mvn test' 
                      }
                  }
       }
}
}
