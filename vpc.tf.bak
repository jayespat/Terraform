resource "aws_vpc" "this" {
  cidr_block       = "10.100.0.0/16"
  instance_tenancy = "default"

  tags = {
    Name = "upgrad-vpc"
    Terraform = "managedbyTerraform"
  }
}
