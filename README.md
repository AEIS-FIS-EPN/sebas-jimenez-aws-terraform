# About
In this repo you're going to find a VPC created with Terraform. This repo was made with the purpose of using some of the services of AWS. 
# Technologies
This project is working with **Terraform**

> [!NOTE]
> The whole project was created on Linux (Ubuntu), so make sure to run it on similar OS. Also, you can modify the path given on `main.tf` according to your OS to avoid errors.

# Prerequisites
You must have installed terraform on the computer that you're trying to run the project, make sure to follow the documentation below:

- [AWS Installation on Linux](https://docs.aws.amazon.com/es_es/cli/latest/userguide/getting-started-install.html)
- [Terraform Installation on Linux](https://developer.hashicorp.com/terraform/install#linux)

>Additionally, don't forget to set-up the whole AWS environment on your CLI following its [documentation](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-files.html)

# How to
**Step 1:** Clone the repo on your editor text of preferences
```
git clone https://github.com/SebastianJimenez2/VPC-Terraform.git
```
**Step 2:** Initialize the project
```
terraform init
```
**Step 3:** Verify if the configuration is valid or not
```
terraform validate
```
**Step 4:** 
```
terraform plan
```
> [!WARNING]
> If you have an error trying this command, make sure you have the files `config` and `credentials` on the directory `.aws`, if not make sure to follow the [documentation](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-files.html) for `aws configure` command.

**Step 5:** Create or update the infrastructure
```
terraform apply
```
**Step 6:**
```
terraform destroy
```
> [!NOTE]
> Make sure you destroyed the infrastructure on the AWS account you created the credentials, otherwise you'll get charged money on your bank account while the service is active. 

# Contributing
Contributions are always welcome! So don't be afraid of forking the repo and make a pull request.

Also, you can add any issue found on the project so it can be fixed asap.
