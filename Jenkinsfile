node {

echo "Jenkins Test ${VERSION}"

deleteDir()


checkout scm

sh 'npm version ${VERSION}'

sh 'git push --tags'

sh 'npm publish'


}
