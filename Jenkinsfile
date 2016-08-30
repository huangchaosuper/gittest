node {
   stage 'Stage 1'
   sh 'pwd'
   stage 'Stage 2'
   echo '${env.JOB_BASE_NAME}'
   stage 'Stage 3'
   git credentialsId: 'xsio', url: 'https://github.com/huangchaosuper/react-study.git'
   stage 'Stage 4'
   echo '${env.JOB_NAME}'
}
