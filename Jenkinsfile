env.JOB_BASE_NAME = $JOB_BASE_NAME
env.JOB_NAME = $JOB_NAME
node {
   stage 'Stage 1'
   sh 'pwd'
   stage 'Stage 2'
   echo '${JOB_BASE_NAME}'
   stage 'Stage 3'
   git credentialsId: 'xsio', url: 'https://github.com/huangchaosuper/react-study.git'
   stage 'Stage 4'
   echo '${JOB_NAME}'
}
