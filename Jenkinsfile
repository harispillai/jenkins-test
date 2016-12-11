node {

echo "Jenkins Test ${VERSION}"

sh "npm version ${VERSION}"

sh "git push origin master --tags"

sh "npm publish"


}
