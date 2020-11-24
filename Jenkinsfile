pipeline {
  agent any
  stages {
    stage('2') {
      steps {
        echo '22222222'
      }
    }

    stage('3') {
      steps {
        echo '333'
        echo 'rrrr'
        sh 'echo "haha"'
        qyWechatNotification(webhookUrl: 'https://qyapi.weixin.qq.com/cgi-bin/webhook/send?key=39a9d06a-261f-4dc8-8deb-e7dcca3b48db', mentionedId: 'ALL', successSend: true, aboutSend: true, startBuild: true)
      }
    }

  }
}