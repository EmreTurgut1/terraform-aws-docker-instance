
provider "aws" {
  region = "us-east-1"
}

module "docker_instance" {
    source = "<EmreTurgut1>/docker-instance/aws"
    key_name = "your-keyname"
}