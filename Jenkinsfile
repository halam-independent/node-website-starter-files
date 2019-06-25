node {
stage (‘Prepare environment’) {
git branch: ‘master’, url: ‘https://github.com/halam-independent/node-website-starter-files.git’
sh ‘npm install’
}
stage (‘Code analyse’) {
sh ‘echo “Run some lints”’
}
stage (‘Unit test’) {
sh ‘echo “Tests will back”’
}
stage (‘Build’) {
sh ‘npm run clean’
sh ‘npm run build’
}
}
