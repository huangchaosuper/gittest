node {
   stage 'Stage 1'
   sh 'pwd'
   stage 'Stage 2'
   echo '${JOB_BASE_NAME}'
   stage 'Stage 3'
   git credentialsId: 'xsio', url: 'https://github.com/huangchaosuper/react-study.git'
   stage 'Stage 4'
   build job: 'build_app_test', parameters: [string(name: 'TESTME', value: '${commitid}')], quietPeriod: 1
   stage 'Stage 5'
   echo '${JOB_NAME}'
}
