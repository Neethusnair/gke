node {

    stage('Clone repository') {
        /* Cloning the Repository to our Workspace */

        checkout scm
    }

    stage('Terraform init') {
        /* This builds the actual image */

        sh 'terraform init'
    }
  
    stage('Terraform plan') {
        /* This builds the actual image */

        sh 'terraform init'
    }
  
     stage('Terraform apply') {
        /* This builds the actual image */

        sh 'terraform apply --auto-approve'
    }

}
