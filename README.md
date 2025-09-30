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

**7. terraform validate:**
Check if the configuration is syntactically valid.

**8. terraform fmt:**
Format configuration files to standard style.


**State Management**

**terraform show** → Show the current state or a plan file.

**terraform state list** → List resources in the state file.

**terraform state show <resource>** → Show attributes of a specific resource.

**terraform state rm <resource>** → Remove a resource from the state file.

**terraform state mv <old> <new>** → Move items in the state.


**Workspace Commands**

**terraform workspace list** → List workspaces.

**terraform workspace show** → Show current workspace.

**terraform workspace new <name>** → Create a new workspace.

**terraform workspace select <name>** → Switch to another workspace.

**terraform workspace delete <name>** → Delete a workspace.


**Provisioning & Dependencies**

**terraform refresh** → Update the state file with real infrastructure.

**terraform import <resource> <id>** → Import existing resources into Terraform.

**terraform graph** → Generate a dependency graph of resources.




**How to Install Terraform**

**Install Terraform on Windows**

Step1: Download the latest Terraform Windows binary from below link
https://developer.hashicorp.com/terraform/install

Step2: Extract the ZIP file and move terraform.exe to C drive (C:\terraform)

Step3: Add C:\terraform to the System

PATH: **Open Control Panel → System → Advanced system settings**

**Click Environment Variables → System Variables → Path → Edit.**

**Add C:\terraform and save.**

Step4: Open Command Prompt and verify Terraform version using

**terraform -version**





