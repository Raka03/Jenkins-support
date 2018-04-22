node {
   
   stage 'Checkout'
   
   git url: 'https://github.com/Raka03/Jenkins-support.git'

    //  def mvnHome = tool 'M3'

  
   stage 'Build'
   
   bat "${mvnHome}\\bin\\mvn -Dmaven.test.failure.ignore clean package"
   step([$class: 'JUnitResultArchiver', testResults: ]
}

