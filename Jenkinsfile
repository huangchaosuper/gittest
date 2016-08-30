node {
   stage 'Stage 1'
   sh 'pwd'
   stage 'Stage 2'
   dir {
       sh 'pwd'
   }
   stage 'Stage 3'
   git credentialsId: 'xsio', url: 'https://github.com/huangchaosuper/react-study.git'
   stage 'Stage 4'
   wrap {
       sh 'pwd'
   }
}
