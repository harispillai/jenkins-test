node {

echo "Jenkins Test ${VERSION}"


checkout scm

sh 'npm version ${VERSION}'

sh 'git push --tags'

sh 'npm publish'


}
