# Learning Objectives


1.Check Terraform Status.
- Check that Terraform is installed and functioning properly using the terraform version command.
- Note: You do not need to worry about the version of Terraform being used in this lab.

2.Clone Terraform Code and Switch to Proper Directory.
- The Terraform code required for this lab has already been cloned onto the provided VM.
- Switch to the directory where the code is located to perform the remaining tasks.
- View the files in the directory.

3.Examine the Code in the Files.
- Closely examine the code in the main.tf file.
- Review the contents of the variables.tf, script.sh, and outputs.tf files.

4.Review and Deploy the Terraform Code.
- Format the code using the terraform fmt command.
- Initialize the working directory and download the required providers.
- Validate the code using the terraform validate command.
- Review the actions that will be performed when you deploy the code using the terraform plan command.
- Deploy the code with the terraform apply --auto-approve command.

5.Test Out the Deployment and Clean Up
- View the outputs of the deployment within the CLI immediately upon successful execution.
- Verify that your resources were created as intended in the AWS Management Console.
- Verify that the webserver is up and running using the URL generated as an output.
- Tear down the infrastructure using the terraform destroy --auto-approve command.