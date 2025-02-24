

# **Application Code Repository Setup Guide**

| **Author** | **Created on** | **Version** | **Last updated by**|**Last Edited On**|**Level** |**Reviewer** |
|------------|---------------------------|-------------|----------------|-----|-------------|-------------|
| Nikita Joshi|  24-02-2025           | v2          | Nikita Joshi    |24-02-2025    |  internal review | Komal Jaiswal | 


## **Table of Contents**
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Repository Setup](#repository-setup)
  -  [Create an Organization](#step-1-create-an-organization)
  -  [Create a Repository](#step-2-create-a-repository)
  - [Configure Role-Based Access Control (RBAC)](#step-3-configure-role-based-access-control-rbac)
- [Best Practices](#best-practices)
- [Conclusion](#conclusion)
- [Contact Information](#contact-information)

___

## **Introduction**

The OT-Microservices Project is a modular system designed to streamline organizational tasks using a microservices architecture. It consists of the following components:

- Frontend

- Employee API

- Attendance API

- Salary API

This guide explains how to set up and organize the code repositories for these components in a Version Control System (VCS).


## **Prerequisites**

Before setting up repositories, ensure the following:  
- Access to a working VCS GitHub 
- Admin or Owner access to the repositories.

##  **Repository Setup**

### **Step 1: Create an Organization**

1. Go to GitHub and log in to your account.

2. Click on your profile picture in the top-right corner and select **Your organizations** from the dropdown menu.

3. Click New organization > Choose a plan.
   ![image](https://github.com/user-attachments/assets/28c55656-12a7-4988-aab3-23208516d7f0)


4. Choose the plan type for your organization:
   - **Free** for basic repositories.
   - **Team** or **Enterprise** for advanced features.
![image](https://github.com/user-attachments/assets/7c214510-8889-4a24-8def-5b032daba53a)

5. Fill in the details:
   - **Organization Name**: For example, `Snaatak-p12`.
   - **Email Address**: Provide an email address associated with the organization.

![Screenshot 2025-02-24 002425](https://github.com/user-attachments/assets/32863d3b-c600-41ad-b114-de267ab678f1)


### **Step 2: Create a Repository**

1. Navigate to the organization.

2. Click New repository.

3. Fill in the repository details:
   - **Repository Name**: For example, `frontend`.
   - **Description**: Add a brief description of the repository.
   - **Visibility**: Choose either **Public** or **Private**.
   - Check **Initialize this repository with a README.md**.
![Screenshot 2025-02-24 003721](https://github.com/user-attachments/assets/b222bf59-b81e-4c3a-b6b8-9aef669be09d)


4. Click **Create repository**.


![image](https://github.com/user-attachments/assets/f79fd463-acf1-41ca-acca-fe312136936d)

## **Step 3: Configure Role-Based Access Control (RBAC)**

1. **Navigate to the Organization Settings:**

  - Go to GitHub, select your organization, and click on Settings.

2. **Manage Teams and Members:**

  - In the left sidebar, click Teams.

  - Click New Team, enter a name, and set the Team Visibility.

  - Click Create Team.


![Screenshot 2025-02-24 132306](https://github.com/user-attachments/assets/a80989a9-031e-474d-9bd5-a76fcd886fde)

  - Add members by searching for their usernames or email addresses.

![Screenshot 2025-02-24 133135](https://github.com/user-attachments/assets/c54d4285-6fff-4b58-9dd1-7517003ac47b)


3. **Set Repository Access:**

  - Go to Repositories under the organization.

  - Select the repository and navigate to Settings > Manage Access.

  - Click Invite a collaborator and assign access levels:

**Admin:** Full access (manage repository settings and permissions).

**Maintainer:** Can push changes and manage branches.

**Developer:** Can push code and create pull requests.

![Screenshot 2025-02-24 133810](https://github.com/user-attachments/assets/44dc9a28-3625-4b9c-8034-7c044a7cff03)





## **Best Practices**

- Use meaningful repository names (e.g., attendance-api, employee-api).

- Implement branch protection rules.

- Follow a consistent commit message format.

- Role-based access control for team members.

- Better collaboration through team features and access settings.


# Conclusion
A well-organized repository structure is essential for the success of the OT-Microservices Project. By setting up clear repositories and following version control best practices, you enable collaborative and maintainable development.




# Contact Information

| **Name** | **Email address**            | **Github ID**
|----------|-------------------------------|-------------------|
| Nikita joshi    | Nikita.Joshi@mygurukulam.co    | https://github.com/jnikita19  |



