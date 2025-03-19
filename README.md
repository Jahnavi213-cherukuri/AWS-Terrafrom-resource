**What is Terraform?**

Terraform is an infrastructure as code tool that lets you build, change, and version cloud and on-prem resources safely and efficiently.

**How Terraform Works**

Terraform creates and manages resources on cloud platforms and other services through their application programming interfaces (APIs). Providers enable Terraform to work with virtually any platform or service with an accessible API.

![image](https://github.com/user-attachments/assets/d85cf6ba-0f32-4cf6-b1cb-2b462776079e)

Terraform follows a declarative approach, meaning you describe the desired state of your infrastructure, and Terraform handles the provisioning and maintenance.

**1. Configuration:**
You write your infrastructure setup in .tf files.

**2. Initialization (terraform init):**
Terraform initializes the working directory, downloads required provider plugins, and prepares the environment.

**3. Planning (terraform plan):**
Terraform analyzes the configuration and shows what changes will be applied without actually executing them.

**4. Applying (terraform apply):**
Terraform executes the plan and provisions the infrastructure.

**5. State Management (terraform state):**
Terraform maintains a state file (terraform.tfstate) to track resources and manage changes efficiently.

**6. Destroying (terraform destroy):**
This command removes all the resources defined in the configuration.

