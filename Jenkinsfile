node {
stage ('Prepare environment') {
sh 'echo "prepration"'
}
stage ('Code analyse') {
sh 'echo "Run some lints"'
}
stage ('Unit test') {
sh 'echo "Tests will back"'
}
stage ('Build') {
sh 'echo "build now"'
}
stage ('Deploy') {
sh 'ssh jenkins@192.168.190.129 mkdir cd /root/Demo && git pull orgin master'
}
}
