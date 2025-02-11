
# Github Setup


| **Author** | **Created on** | **Version** | **Last updated by** | **Last edited on** | **Reviewer** |
|------------|-------------|-----------|--------------|-------------|-----------|
| Nikita Joshi | 11-02-25 | V1 | Nikita Joshi | 11-02-25 |   |

![image](https://github.com/user-attachments/assets/881977db-078d-4211-ab9a-a7e903b27413)

# Table of Contents
1. [Introduction](#introduction)
2. [Types of VCS](#types-of-vcs)
3. [GIT](#git)
4. [GIT Setup Prerequisites](#git-setup-prerequisites)
5. [Git Installation on Ubuntu](#git-installation-on-ubuntu)
   - [Step 1: Update System Packages](#step-1-update-system-packages)
   - [Step 2: Installation of Git](#step-2-installation-of-git)
   - [Step 3: Verify the version of Git](#step-3-verify-the-version-of-git)
   - [Step 4: Configure Git on Ubuntu](#step-4-configure-git-on-ubuntu)
     - [1. Check the public key](#1-check-the-public-key)
     - [2. Create public key](#2-create-public-key)
     - [3. Copy the public key](#3-copy-the-public-key)
     - [4. Click on the Account setting](#4-click-on-the-account-setting)
     - [5. Add New SSH key](#5-add-new-ssh-key)
     - [6. Git clone](#6-git-clone)
6. [Contact Information](#contact-information)
7. [References](#references)


# Introduction

A Version Control System (VCS) is a tool that helps developers work together and keeps a detailed record of all changes made to their code over time

# Types of VCS

-   **Centralized version control system (CVCS):**
  A single, central server stores all versions of the files, and  developers "check out" files to work on them. Changes are then committed back to the central server.

-   **Distributed/Decentralized version control system (DVCS):** 
Every developer has a full copy of the entire project history, including all files and changes, on their local machine. Changes can be shared directly between developers or through a central server.Developers can work offline and commit changes locally.

# Git

Git is a free and open-source Distributed Version Control System (DVCS) used to track changes in code and manage projects efficiently It is widely used in software development to maintain
project history, resolve conflicts, and enable teamwork

# Git Setup Prerequisites

| **Requirement** | **Details**                                           |
|-----------------|-------------------------------------------------------|
| **OS**          | Ubuntu /Linux-based OS or Windows                     |
| **RAM**         | 1 GB minimum                                          |
| **Disk Space**  | 200 MB for Git installation                           |
| **Processor**   | Any modern processor (Intel or AMD, 1 GHz or faster). |

# Git Installation on Ubuntu

This guide provides the steps to install and configure GitHub on Ubuntu.

**Installation Steps**

## Step 1: Update System Packages

``` bash
sudo apt update
```

## Step 2: Installation of Git

**To install Git, use the apt package manager**

``` bash
sudo apt install git -y
```
![image](https://github.com/user-attachments/assets/545013cd-bfd1-4743-8b7b-8c4dd6e42dd4)

## Step 3: Verify the version of Git
``` bash
git –version
```
![image](https://github.com/user-attachments/assets/2d5fe005-55b9-436a-97fc-58eb5e373bcd)


## Step 4: Configure Git on Ubuntu

Before configuration on local machine of Git your account should be
available on GitHub website.


### Check the public key 

> Go to the ./ssh directory for check public key is available or not
![image](https://github.com/user-attachments/assets/c5ea93a8-3d94-4c7e-872e-719b35e2222a)



**If the public key is not available, then create the key**

### Create public key

``` bash
ssh-keygen
```
![image](https://github.com/user-attachments/assets/d329f0eb-3de3-49d7-887a-cbef69986333)




### Copy the public key
copy the public key and go you github account on web browser and singnin. 

![image](https://github.com/user-attachments/assets/062283dc-6df9-4047-97e0-b7d9694d520e)




### Go to the Account Setting 

1) Go you account
2) Click on right side of your account setting
3) click on ssh and gpg key

![image](https://github.com/user-attachments/assets/fdbb80af-26ea-41b2-bdb3-a29a69f4b2f7)



### Add New SSH key

> Add ssh key by pressing new ssh key button

![image](https://github.com/user-attachments/assets/04a7efb4-f348-4cf0-8e5e-8ee1d961f42d)




### Add the title name

Paste the ssh key in key box then click on add ssh key button

![image](https://github.com/user-attachments/assets/ca16132a-e439-4a04-a67b-d5622762df0f)

### Now click on your repo which want to clone on your local machine. Click on code 🡪 SSH 🡪 copy the code.

![image](https://github.com/user-attachments/assets/d5e3b522-2cd0-4c71-9c2f-0e72c87819c9)



## Git Clone
**Go to your system and type or paste the code that you copied**
![image](https://github.com/user-attachments/assets/4c25d0e2-4cef-4e62-9a84-1b09d9266d4d)




# Contact Information

| **Name**    | **Email address**         |
|-------------|---------------------------|
| Nikita joshi | <jnikita647@gmail.com> |

# References

| **Link** | **Description** |
|-----------------------------------|-------------------------------------|
| [Git installation on Ubuntu](https://www.digitalocean.com/community/tutorials/how-to-install-git-on-ubuntu) | GitHub installation |
| [GitHub SSH Configuraton](https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/GitHub-SSH-Key-Setup-Config-Ubuntu-Linux) | GitHub Configuration |
|[conclusion doc](https://github.com/avengers-p11/Documentation/tree/main/VCS%20Design%20%2B%20POC/Features%20of%20VCS/Conclusion%20doc)| why we choose GitHub |
