**Ansible Docker Container Provisioning and Configuration Project**

**Overview**

This project demonstrates the use of Ansible to provision and configure three containers using Docker. The containers are provisioned with specific configurations: one for PostgreSQL, one for Apache, and one for Git. The objective is to showcase the power and capabilities of Ansible in automating the setup and configuration of containers.

**Problem Statement**

The problem statement for this project is as follows:

**1. Provision three containers using Ansible and Docker.**

**2. Configure the first container with PostgreSQL, the second container with Apache, and the third container with Git.**

**3. For the PostgreSQL container:**
      Create a database named "DevOps" using Ansible.
      Create a table named "students" in the "DevOps" database.
      Insert a list of students enrolled in the DevOps class, including their first name, last name, and registration number.

**4. For the Apache container:**

      Ping the Apache URL and verify a 200 response.

**5. For the Git container:**

      Create a file with your name.
      Add some text to the file.
      Push the change to a BitBucket repository.
      Verify that the change is visible on BitBucket.
      
**Project Architecture**

![image (4)](https://github.com/usman-akram-dev/DevOps-Project-1/assets/7351877/6a6b95e5-6ce3-4d6d-a725-5e594b363608)

**Project Components**

The project consists of the following components:

**1.** Provisioning Playbook: This playbook uses Ansible's Docker modules to create three containers - one for PostgreSQL, one for Apache, and one for Git.

**2.** PostgreSQL Playbook: This playbook uses Ansible's PostgreSQL module to:
        Create a database named "DevOps".
        Create a table named "students" in the "DevOps" database.
        Insert the list of students enrolled in the DevOps class.
        
**3.** Apache Playbook: This playbook uses Ansible's URI module to ping the Apache URL and verify a 200 response code.

**4.** Git Playbook: This playbook uses Ansible's Git module to:
        Clone a BitBucket repository.
        Create a file with your name using Ansible's File module.
        Add text to the file.
        Commit and push the change to the BitBucket repository.

**Conclusion**

This project showcases the capabilities of Ansible in automating the provisioning and configuration of containers. By using Ansible playbooks, we can easily set up a PostgreSQL database, verify the availability of Apache, and perform Git operations. Ansible simplifies the management and deployment of applications by providing a declarative language to define infrastructure as code.
