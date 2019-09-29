pipeline
{


agent any



stages{
     stage "scm checkout"{
     git 'https://github.com/sachidud/maven-project'
     }

}
{
stages{
      stage "code test"{
      withMaven(maven: 'LocalMaven'){
      sh 'mvn test'
	  
}
}
}
}
}
