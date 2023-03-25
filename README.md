# zopstix
First I create Amazon Linux machine and install docker
once docker install i follow "https://github.com/jenkins-docs/simple-java-maven-app" article
Jenkins run succesfully but build was not trigger
add slack by below body in Jenkins file which is avaibale on git hub
post{
        failure{
            slackSend( channel: "#Jenkins", token: "slack_webhook token", color: "good", message: "${custom_msg()}")
        }
    }
automation task by shellor python script not done
when i am trying to upload code it was 100mb approx so i wrote all steap here
once you avaiable i will show you live demo how i did these all thing
