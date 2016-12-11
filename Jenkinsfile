node {

echo "Jenkins Test ${VERSION}"


checkout scm

sh 'npm version ${VERSION}'

sh 'git push origin master --tags'

sh 'npm publish'


}
