node {
stage ('Prepare environment'){
 git 'https://github.com/satyasri73/Vedika-UI.git'
 }
 
 stage('install packages and build'){
  sh label: '', script: 'npm install'
 }

  stage('Build UI app'){
   sh label: '', script: 'ng build --prod'  
  } 
}


