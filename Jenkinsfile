node {
   
   stage 'Checkout'
   
   git url: 'https://github.com/Raka03/Jenkins-support.git'

     def M2_HOME = 'M2_HOME'

  
   stage 'Build'
   
   bat "${M2_HOME}\\bin\\mvn -Dmaven.test.failure.ignore clean //package"
  // step([$class: 'JUnitResultArchiver', testResults: ]
echo "build complete"
echo " done"
}

