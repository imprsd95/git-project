pipeline {

   agent any
   stages {

   stage ('copy-qa') {
   steps {

   sh 'cp -r qa.html /var/www/html'

}


}

stage ('copy-uat') {
   steps {

   sh 'cp -r uat.html /var/www/html'

}


}

stage ('restart-httpd') {
   steps {

   sh 'service httpd restart'

}


}

}


}
