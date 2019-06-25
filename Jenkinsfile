node {
stage (‘Prepare_environment’) {
git branch: ‘master’, url: ‘https://github.com/halam-independent/node-website-starter-files.git’
sh ‘npm install’
}
stage (‘Build’) {
sh ‘npm run clean’
sh ‘npm run build’
}
}
