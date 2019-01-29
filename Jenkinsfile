stage 'github1'
node {
     def job = build job: 'hello1'
}
stage 'gitbub2'
node {
     def job = build job: 'hello2'
}
stage 'custome echo'
node {
    sh "sleep 5"    
    sh 'echo hello3'
}