node('master') 
{
    stage('Continuous Download') 
	{
          git 'https://github.com/TimeMachine00/multibranchJenkin.git'
	}
     stage('Continuous Testing') 
       {
        sh 'echo "test success"'
       }
}
