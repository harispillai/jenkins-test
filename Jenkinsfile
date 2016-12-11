node {

echo "Jenkins Test ${VERSION}"

deleteDir()


checkout scm

sh 'cat package.json'

sh 'npm version ${VERSION}'

sh 'git add -A'

sh 'git commit -m "version bumped"'

sh 'git push --tags'


}
