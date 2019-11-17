pipeline  {
  agent any
  stages  {
      ('Build') {
        steps {
      sh  'echo " Build job is running"'
      sh '''
          echo "Multiline shell steps works too"
          ls -lah
      '''
      }
     }
    }
   }
