### [🐳 Ansible-Docker-Swarm kit)](https://github.com/AlexandrNeverov/ansible_docker_setup

[![Ansible](https://img.shields.io/badge/Ansible-Docker--Swarm--Provisioning-EE0000?style=for-the-badge&logo=ansible&logoColor=white)](https://github.com/AlexandrNeverov/ansible_docker_setup)
[![Docker](https://img.shields.io/badge/Docker-Container--Platform-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![Ubuntu](https://img.shields.io/badge/Ubuntu-Tested--on--Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)](https://ubuntu.com/)
[![CI Ready](https://img.shields.io/badge/CI--Ready-Automated--Setup-brightgreen?style=for-the-badge)]()

<table>
  <tr>
    <td width="500">
      <a href="https://www.youtube.com/watch?v=XXXXXXXXXXX" target="_blank">
        <img src="https://raw.githubusercontent.com/AlexandrNeverov/ansible_docker_setup/main/image.png" width="500" alt="Terraform Admin Bootstrap video thumbnail"/>
      </a>
    </td>
    <td valign="top">
      <img src="https://raw.githubusercontent.com/AlexandrNeverov/zero-node-devops-kit/main/neveroff.png" width="100" alt="Neveroff Logo"/><br/>
      <strong>Automated admin-ready cloud Docker node with Ansible</strong><br/>
  •Installing Docker CE, Compose v2, Swarm mode, and Portainer usually involves a long sequence of shell commands, package installations, and security configurations. Mistakes are easy, automation is tricky, and reusability is low.

**`ansible-docker-swarm-kit`** eliminates this pain by fully automating the process with Ansible:

- 🧩 Installs Docker CE and containerd from Docker’s official APT repo  
- 🧰 Adds Docker Compose v2 as a binary  
- 🌀 Bootstraps Docker Swarm (if not yet active)  
- 🚀 Deploys Portainer CE as a Docker container  
- 🧭 Inventory-based provisioning with SSH private key auth  

This is ideal for: 🧪 Testing Docker in clean environments  🛠️ DevOps labs, demos, and bootstrap nodes  💡 Repeatable setup for Swarm-based projects or local learning 🐧 Ubuntu EC2 hosts, Raspberry Pi servers, or any SSH-accessible node

   </td>
  </tr>
</table>

### [🚀Docker-node Zero Bootstrap (with Terraform )](https://github.com/AlexandrNeverov/terraform_docker_setup)

[![Terraform](https://img.shields.io/badge/Terraform-Infrastructure--as--Code-623CE4?style=for-the-badge&logo=terraform&logoColor=white)](https://github.com/AlexandrNeverov/terraform_docker_setup)
[![Docker](https://img.shields.io/badge/Docker-Container--Setup-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://github.com/AlexandrNeverov/terraform_docker_setup)

<table>
  <tr>
    <td width="500">
      <a href="https://www.youtube.com/watch?v=XXXXXXXXXXX" target="_blank">
        <img src="https://raw.githubusercontent.com/AlexandrNeverov/terraform_docker_setup/main/image.png" width="500" alt="Terraform Admin Bootstrap video thumbnail"/>
      </a>
    </td>
    <td valign="top">
      <img src="https://raw.githubusercontent.com/AlexandrNeverov/zero-node-devops-kit/main/neveroff.png" width="100" alt="Neveroff Logo"/><br/>
      <strong>Automated admin-ready cloud node with Ansible</strong><br/>
  • 🖥️ EC2 provisioning with custom AMI, subnet, and security group
  • 🔐 IAM Instance Profile with secure metadata-based AWS API access
  • 🐳 Automatic Docker installation via cloud-init user data
  • 🪣 Remote backend: S3 (versioned) + DynamoDB (state locking)
  • 📦 Modular Terraform code: separated providers, variables, outputs, and versions
  • 🧩 Reusable for other container images or base configurations
  • 🔧 Customizable via terraform.tfvars without touching core logic
  • 🖼 Image reference: architecture diagram included (image.png)
  • 📝 Versioned deployment structure for easy updates and tracking

   </td>
  </tr>
</table>

### [🚀 Ansible Zero Bootstrap](https://github.com/AlexandrNeverov/ansible-zero-node)

[![Ansible Node](https://img.shields.io/badge/Ansible-Automation--EC2--IAM-blue?style=for-the-badge&logo=ansible&logoColor=white)](https://github.com/AlexandrNeverov/ansible-zero-node)
[![Vault Secrets](https://img.shields.io/badge/Vault-Secrets--Management--Optional-6f42c1?style=for-the-badge&logo=vault&logoColor=white)](https://github.com/AlexandrNeverov/ansible-zero-node)

<table>
  <tr>
    <td width="500">
      <a href="https://www.youtube.com/watch?v=XXXXXXXXXXX" target="_blank">
        <img src="https://raw.githubusercontent.com/AlexandrNeverov/ansible-zero-node/main/image.png" width="500" alt="Terraform Admin Bootstrap video thumbnail"/>
      </a>
    </td>
    <td valign="top">
      <img src="https://raw.githubusercontent.com/AlexandrNeverov/zero-node-devops-kit/main/neveroff.png" width="100" alt="Neveroff Logo"/><br/>
      <strong>Automated admin-ready cloud node with Ansible</strong><br/>
    🔧 Automated EC2 bootstrap with Ansible, CLI tools, and IAM-based auth<br/>
    • 🚀 Provision EC2 instance with admin IAM role and metadata-based authentication<br/>
    • ⚙️ Ansible auto-installed via official Ubuntu PPA, ready to run<br/>
    • 🧰 Preinstalled CLI tools: AWS CLI v2, Git, jq, curl, unzip, htop, tmux, Python3, pip3<br/>
    • 🔐 Optional Vault install with systemd launch and minimal config<br/>
    • 🧩 Modular design: use scripts standalone or as full pipeline<br/>

   </td>
  </tr>
</table>

### [☁️ Cloud Bootstrap Automation with Terraform & Vault](https://github.com/AlexandrNeverov/vault-iac-bootstrap)

[![Terraform Admin](https://img.shields.io/badge/Terraform-Admin--EC2--IAM-critical?style=for-the-badge&logo=terraform&logoColor=white)](https://github.com/AlexandrNeverov/vault-iac-bootstrap) 
[![Vault Secrets](https://img.shields.io/badge/Vault-Secrets--Management--HCP-6f42c1?style=for-the-badge&logo=vault&logoColor=white)](https://github.com/AlexandrNeverov/vault-iac-bootstrap)

<table>
  <tr>
    <td width="500">
      <a href="https://www.youtube.com/watch?v=XXXXXXXXXXX" target="_blank">
        <img src="https://raw.githubusercontent.com/AlexandrNeverov/vault-iac-bootstrap/main/image.png" width="500" alt="Terraform Admin Bootstrap video thumbnail"/>
      </a>
    </td>
    <td valign="top">
      <img src="https://raw.githubusercontent.com/AlexandrNeverov/zero-node-devops-kit/main/neveroff.png" width="100" alt="Neveroff Logo"/><br/>
      <strong>Automated admin-ready cloud node with HCL Vault </strong><br/>
      • 🚀 Provision EC2 instance with full admin rights via IAM Instance Profile<br/>
      • 🧰 Preinstalled tools: Terraform, Vault, AWS CLI, Git, Python, jq, htop<br/>
      • ☁️ Remote backend ready: S3 (versioned) + DynamoDB (state locking htop<br/>
      • 🔐 Vault auto-installed, configured, and launched as systemd service <br/>
      • ✅ No static credentials – IAM-managed secure access only  <br/>
   </td>
  </tr>
</table>

### [🛡️ Terraform Admin Bootstrap on EC2 via IAM Instance Profile](https://github.com/AlexandrNeverov/Terraform-Admin-Bootstrap-on-EC2-via-IAM-Instance-Profile)

[![Terraform Admin](https://img.shields.io/badge/Terraform-Admin--EC2--IAM-critical?style=for-the-badge&logo=terraform&logoColor=white)](https://github.com/AlexandrNeverov/Terraform-Admin-Bootstrap-on-EC2-via-IAM-Instance-Profile)

<table>
  <tr>
    <td width="500">
      <a href="https://www.youtube.com/watch?v=XXXXXXXXXXX" target="_blank">
        <img src="https://raw.githubusercontent.com/AlexandrNeverov/Terraform-Admin-Bootstrap-on-EC2-via-IAM-Instance-Profile/main/image.png" width="500" alt="Terraform Admin Bootstrap video thumbnail"/>
      </a>
    </td>
    <td valign="top">
      <img src="https://raw.githubusercontent.com/AlexandrNeverov/zero-node-devops-kit/main/neveroff.png" width="100" alt="Neveroff Logo"/><br/>
      <strong>Automated admin-ready cloud node using <code>Terraform</code>, <code>EC2</code> and IAM instance profile:</strong><br/>
      • 🛡️ Launch EC2 with <strong>AdministratorAccess</strong> IAM Role (Instance Profile)<br/>
      • ⚙️ Use Terraform to manage infrastructure securely<br/>
      • 🧰 Tools installed: Terraform, AWS CLI, Git, Python, jq, htop<br/>
      • ☁️ Remote backend: <strong>S3</strong> (versioning) + <strong>DynamoDB</strong> (locking)<br/>
      • 🔐 Verifies IAM permissions and protects credentials<br/>
      • 🎬 <a href="https://www.youtube.com/watch?v=XXXXXXXXXXX" target="_blank">Watch the demo video</a>
    </td>
  </tr>
</table>

### [🔧 Terraform AWS DevOps Kit](https://github.com/AlexandrNeverov/zero-node-devops-kit)

[![Terraform AWS](https://img.shields.io/badge/Terraform-AWS-blueviolet?style=for-the-badge&logo=terraform&logoColor=white)](https://github.com/AlexandrNeverov/zero-node-devops-kit)

<table>
  <tr>
    <td width="500">
      <a href="https://www.youtube.com/watch?v=_W2HxS0K1PE" target="_blank">
        <img src="https://raw.githubusercontent.com/AlexandrNeverov/zero-node-devops-kit/main/image.png" width="500" alt="Terraform AWS DevOps Kit video thumbnail"/>
      </a>
    </td>
    <td valign="top">
      <img src="https://raw.githubusercontent.com/AlexandrNeverov/zero-node-devops-kit/main/neveroff.png" width="100" alt="Neveroff Logo"/><br/>
      <strong>A fully automated infrastructure provisioning kit using <code>Terraform</code> and <code>AWS</code>:</strong><br/>
      • ⚙️ Launch EC2 instance with IAM and SSH access<br/>
      • 🧰 Install core DevOps tools (Git, CLI, Python, htop, etc.)<br/>
      • ☁️ Configure remote backend with <strong>S3</strong> + <strong>DynamoDB</strong> for state management<br/>
      • 🎬 <a href="https://www.youtube.com/watch?v=_W2HxS0K1PE" target="_blank">Watch the demo video</a>
    </td>
  </tr>
</table>
