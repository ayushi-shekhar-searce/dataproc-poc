pipeline{
   agent any
   stages{
      stage('login server'){
         steps{
            sshagent(credentials:'private.key'){
               sh 'ssh  -o StrictHostKeyChecking=no  ayushi_shekhar_searce_com@10.1.0.95 uptime "whoami"'
          }
        echo "success lgoin"
         }
       }
   }
}
