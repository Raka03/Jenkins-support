node {
   
   stage 'Checkout'
   
   git url: 'https://github.com/Raka03/Jenkins-support.git'

     def mvnHome = 'M2_HOME'

  
   stage 'Build'
   
   bat "${mvnHome}\\bin\\mvn -Dmaven.test.failure.ignore clean //package"
  // step([$class: 'JUnitResultArchiver', testResults: ]
echo "build complete"
echo " done"
}

