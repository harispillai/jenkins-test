node {

echo "Jenkins Test ${VERSION}"

deleteDir()


checkout scm

sh 'cat package.json'

sh 'npm version ${VERSION}'

sh 'git push --tags'

sh 'npm publish'


}
