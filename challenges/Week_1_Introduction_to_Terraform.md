# Week 1: CODE THEFT AUTO: Terraform Challenge - Introduction to Terraform

Welcome to the first week of the CODE THEFT AUTO: Terraform Challenge! Today, we're starting our adventure in the cloud infrastructure world with Terraform, setting the foundation just like beginning your journey in the vast city of Los Santos.

## Objective

Your mission this week is to get familiar with Terraform and set up your very first Terraform project. You'll be deploying a "safe house" in AWS - a simple EC2 instance to give you a base in the cloud.

## What You Will Learn

- What is Terraform and why it's a game-changer.
- How to install and configure Terraform.
- Basic concepts of Terraform: Providers, Resources, and State.
- Deploying your first AWS resource using Terraform.

## Prerequisites

Ensure you have the following ready before you start:

- An AWS account (free tier is sufficient).
- Terraform installed on your computer.
- Basic knowledge of cloud computing concepts.

## Installation Guide

1. **Terraform Installation**: Follow the official Terraform installation guide [here](https://learn.hashicorp.com/tutorials/terraform/install-cli).

2. **AWS CLI Setup**: Make sure you have the AWS CLI installed and configured. [AWS CLI Installation](https://aws.amazon.com/cli/).

---
### ⚡ Power-Up Option: Choose Your Cloud IDE

**Turbocharge Your Setup**: Before diving into Terraform, select a Cloud IDE for a seamless start. Why fuss with local setups when you can go cloud from the get-go? Choose from **GitHub Codespaces**, **Gitpod**, or **Visual Studio Code Online** based on what suits your style.

- **Quick Setup**: Each Cloud IDE offers a ready-to-code environment. (🤔 with Terraform and AWS CLI pre-installed ??)
- **Anywhere, Anytime**: Jump into coding from any device, anywhere. All you need is a browser.
- **Why This Power-Up?**: Share your choice and setup experience on our community forum or social media with `#CodeTheftAuto`. Reflect on how your selected IDE aligns with your workflow and enhances your challenge journey.
---

## Challenge Instructions

1. [ ] **Initialize Your Terraform Project**: Create a new directory for your project, navigate into it, and run `terraform init` to initialize a new Terraform project.
   
2. [ ] **Write Your First Configuration**: Create a `main.tf` file where you'll define your "safe house" - an AWS EC2 instance. Refer to the [Terraform AWS Provider Documentation](https://registry.terraform.io/providers/hashicorp/aws/latest/docs) for guidance.

3. [ ] **Plan and Apply**: Run `terraform plan` to see what Terraform intends to do and `terraform apply` to create your infrastructure.
   
4. [ ] **Destroy**: Run `terraform destroy` to terminate/delete the infrastructure you created in Step 3 above.

## Resources

- [Terraform Getting Started Guide](https://learn.hashicorp.com/terraform/getting-started/install)
- [AWS Provider Documentation](https://registry.terraform.io/providers/hashicorp/aws/latest/docs)

## Community Help

Stuck or have questions? Join the discussion in our [Patreon Community](https://www.patreon.com/GIFTEDLANE). Share your progress and get help from fellow participants and mentors.

## Wrap Up

Congratulations on completing Week 1 of the CODE THEFT AUTO: Terraform Challenge! You've just made your first step into the world of Infrastructure as Code (IaC) and have your very own "safe house" in AWS. Be ready for next week, where we'll dive deeper into managing state with Terraform - vital for planning and executing more complex "heists" in the cloud.

Remember, Los Santos wasn't built in a day, and neither is cloud mastery. Keep experimenting, exploring, and asking questions!

---

[Return to README](/README.md) | [Next: Week 2 - The Vinewood Job](/challenges/Week_2_Managing_State_with_Terraform.md)
