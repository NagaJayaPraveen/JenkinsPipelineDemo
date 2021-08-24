node('master') 
     {
    stage('continuous download')
           {
              git 'https://github.com/sunildevops77/maven'
           }

    stage('continuous build')
           {
              sh 'mvn package'
           }
     }
