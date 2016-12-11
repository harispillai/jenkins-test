node {

echo "Jenkins Test ${VERSION}"


dir('jenkins-test') {
echo pwd()


sh 'npm version ${VERSION}'

sh 'git push origin master --tags'

}




}
