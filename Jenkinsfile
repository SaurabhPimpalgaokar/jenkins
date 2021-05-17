pipeline
{
  agent label 'slave_first'
  
    stages
    {
    
      stage("build")
      {   steps
            {
                echo 'build phase'
                echo 'build by slave'
            }
      }
      stage("test")
      {   steps
            {
                echo 'test phase'
                echo 'second change in test '
                echo 'test by slave'
              
            }
      }
      stage("deploy")
      {   steps
            {
                echo 'deploy phase'
            }
      }
      
    }
      
}
