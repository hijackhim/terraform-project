                                              # ** Terraform Project ** #
                                            # ** Static website hosting using S3 bucket **#
Prerequisites:
1. AWS Account
2. EC2 instance
3. Terraform installed
4. Documentation for reference
5. Common sense


Step: 1 Create an EC2 instance with the OS you want.

Step: 2 Create an IAM user with Admin permission.

Step: 3 Now generate a secret access key from the IAM user and put it in the AWS CLI which you installed in the EC2 instance.

Step: 4 Install terraform into the instance with the help terraform official documentation.

Step: 5 Using terraform documentation create S3 bucket by creating main.tf.

![s3-terra](https://github.com/hijackhim/terraform-project/assets/105789918/b6225f58-d4ef-4e29-a434-20199bfe2b79)


Step: 6 Now make S3 bucket public using terraform.

![terra-permission](https://github.com/hijackhim/terraform-project/assets/105789918/85870a90-ef48-4cf4-8a32-0fab37d7d92d)


Step: 7 Now upload or create index.html file and error.html file for the static website.

![Screenshot 2024-01-28 182612](https://github.com/hijackhim/terraform-project/assets/105789918/81bf3ffa-ca44-4c44-8ec4-9d4c5efc92ce)


Step: 8 You can check the website by clicking on the S3 bucket static link.

![Screenshot 2024-01-28 182738](https://github.com/hijackhim/terraform-project/assets/105789918/7c94f4ed-44e7-4adb-a1c5-a388d278d931)

Step: 9 Click on the link to open the site, it will show the content of index.html file

