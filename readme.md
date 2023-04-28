Terraform workspace :
=====================
how to create workspace in terraform
======================================
terraform worksapce new dev ---<env name>

terraform workspace select <dev>

terraform worksapce new stage ----<env name>

terraform worksapce select <stage>

---------------------------------------- 

to pass it aws configure multiple profile 
------------------------------------------
aws configure --profile dev
access_key=
secret_access_key=
region=
--------------------------------
aws configure --profile stage

access_key=
secret_access_key=
region=
--------------------------------------

to pass it aws configure multiple profile 
-------------------------------------------
export AWS_ACCESS_KEY_ID=<access_key>
export AWS_SECRET_ACCESS_KEY=<secret_access_key>
export AWS_DEFAULT_REGION=<region>
--------------------------------------------------------------------------
export AWS_ACCESS_KEY_ID=<access_key>
export AWS_SECRET_ACCESS_KEY=<secret_access_key>
export AWS_DEFAULT_REGION=<region>


