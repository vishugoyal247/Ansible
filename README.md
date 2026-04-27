# Ansible Course Curriculum

---

## Module 1: Getting Started

- Module Introduction

### Lesson 1: What is Ansible

- Learning objectives
- 1.1 What is Configuration Management
- 1.2 Solutions for Configuration Management
- 1.3 Configuration as Code and DevOps
- 1.4 Ansible Components
- 1.5 Working with Ansible in Small Environments
- 1.6 Working with Ansible in Large Environments

### Lesson 2: Getting Started

- Learning objectives
- 2.1 Ansible Infrastructure Components
- 2.2 Setting up a RHEL Ansible Control Node
- 2.3 Setting up an Ubuntu Ansible Control Node
- 2.4 Setting up an Ansible Control Node with Python pip
- 2.5 Requirements for Managing Assets
- 2.6 Modules and Collections
- 2.7 Using Ansible to Configure Managed Nodes - Part 1
- 2.8 Using Ansible to Configure Managed Nodes - Part 2
- 2.9 Using Ansible to Configure Managed Nodes - Part 3
- 2.10 Defining Default Settings in ansible.cfg
- 2.11 Managing Windows
- 2.12 Using MacOS as a Control Node
- Lesson 2 Lab: Setting up an Ansible-managed Environment
- Lesson 2 Lab Solution: Setting up an Ansible-managed Environment

### Lesson 3: Using Ansible in Large Environments

- Learning objectives
- 3.1 Centralizing Configuration as Code Using Git
- 3.2 Using AWX and Ansible Automation Platform
- 3.3 Configuring ansible-navigator
- 3.4 Working with ansible-navigator
- 3.5 Providing Required Collections for ansible-navigator
- 3.6 ansible-navigator Configuration
- Lesson 3 Lab: Using ansible-navigator
- Lesson 3 Lab Solution: Using ansible-navigator

### Lesson 4: Using Ad-Hoc Commands

- Learning objectives
- 4.1 Ad-hoc Commands versus Playbooks
- 4.2 Using Ansible Content Collections
- 4.3 Exploring Essential Ansible Modules
- 4.4 Using Module Documentation
- 4.5 Using Ansible in an Idempotent Way
- Lesson 4 Lab: Using Ad-Hoc Commands
- Lesson 4 Lab Solution: Using Ad-Hoc Commands

### Lesson 5: Using Ansible Playbooks

- Learning objectives
- 5.1 Understanding Playbook Structure
- 5.2 Running Your First Playbook
- 5.3 Understanding Task Execution and Errors
- 5.4 Using ansible-navigator to Run Playbooks
- Lesson 5 Lab: Using a Playbook to Deploy a Webserver
- Lesson 5 Lab Solution: Using a Playbook to Deploy a Webserver

### Lesson 6: Using Ansible Tower

- Learning objectives
- 6.1 Understanding Ansible Tower, Automation Platform and AWX
- 6.2 Installing Ansible Tower
- 6.3 Understanding Ansible Tower Main Components
- 6.4 Setting up Ansible Tower to Manage Assets
- 6.5 Configuring Ansible Tower to Manage Windows
- Lesson 6 Lab: Setting up Ansible Tower to Manage Assets in Ansible
- Lesson 6 Lab Solution: Setting up Ansible Tower to Manage Assets in Ansible

---

## Module 2: Developing Flexible Playbooks

- Module Introduction

### Lesson 7: Working with Variables

- Learning objectives
- 7.1 Separating Code from Site-Specific Configuration
- 7.2 Using Variables in a Playbook
- 7.3 Understanding Where to Define Your Variables
- 7.4 Using Ansible Facts
- 7.5 Using set_fact
- 7.6 Understanding Different Notations for Facts and Variables
- 7.7 Using Multi-valued Variables
- 7.8 Using Magic Variables
- 7.9 Using Register
- 7.10 Using Vault to Store Sensitive Information
- Lesson 7 Lab: Making Playbooks Flexible with Variables
- Lesson 7 Lab Solution: Making Playbooks Flexible with Variables

### Lesson 8: Using Conditionals

- Learning objectives
- 8.1 Conditionals Overview
- 8.2 Using loop to Process a List of Items
- 8.3 Using Handlers for Conditional Task Execution
- 8.4 Using when to Run Tasks in Specific Situations
- 8.5 Using register to Work with Task Results
- 8.6 Using Blocks
- 8.7 Managing Failure with the fail Module
- 8.8 Using assert
- Lesson 8 Lab: Using when to Create Idempotency
- Lesson 8 Lab Solution: Using when to Create Idempotency

### Lesson 9: Managing Files

- Learning objectives
- 9.1 Manipulating Files
- 9.2 Changing File Contents
- 9.3 Using the find Module
- 9.4 Using Templates
- 9.5 Using Conditional Statements in Templates
- Lesson 9 Lab: Working with Files
- Lesson 9 Lab Solution: Working with Files

### Lesson 10: Using Roles

- Learning objectives
- 10.1 Understanding and Using Roles
- 10.2 Working with ansible-galaxy
- 10.3 How Roles are Organized
- 10.4 Writing Custom Roles
- 10.5 Using System Roles
- Lesson 10 Lab: Working with Roles
- Lesson 10 Lab Solution: Working with Roles

---

## Module 3: Advanced Ansible Management Options

- Module Introduction

### Lesson 11: Ansible Best Practices and Optimization

- Learning objectives
- 11.1 Using include and import
- 11.2 Configuring Security
- 11.3 Using Tags
- 11.4 Using Delegation
- 11.5 Managing Parallelism
- 11.6 Efficiently Copying Files
- 11.7 Optimizing SSH
- 11.8 Case Study: Optimizing Ansible
- Lesson 11 Lab: Optimizing Ansible
- Lesson 11 Lab Solution: Optimizing Ansible

### Lesson 12: Using Filters

- Learning objectives
- 12.1 Understanding Filters and Plugins
- 12.2 Filters, Plugins, and Collections
- 12.3 Understanding Filters and Variable Types
- 12.4 Using Filters to Change Variables
- 12.5 Using Filters to Work with Network Addresses
- 12.6 Examples of Using Filters
- 12.7 More Examples of Using Filters
- Lesson 12 Lab: Using Filters
- Lesson 12 Lab Solution: Using Filters

### Lesson 13: Using Plugins

- Learning objectives
- 13.1 Understanding Plugins
- 13.2 Exploring Lookup Plugins
- 13.3 Common Lookup Plugins
- 13.4 Using the fileglob Plugin
- 13.5 Plugin-based Inventory
- 13.6 Fact Caching
- 13.7 Creating Random Passwords
- 13.8 The test Plugin
- Lesson 13 Lab: Using Callback Plugins
- Lesson 13 Lab Solution: Using Callback Plugins

### Lesson 14: Advanced Ansible Tower Usage

- Learning objectives
- 14.1 Managing Users and Teams
- 14.2 Creating Job Template Surveys
- 14.3 Configuring Notifications
- 14.4 Using Workflow
- 14.5 Scheduling Jobs
- 14.6 Importing Static Inventories
- 14.7 Creating and Updating Dynamic Inventories
- 14.8 Using Smart Inventories
- 14.9 Using Vault in Tower
- 14.10 Using the Tower API
- 14.11 Backing up Tower
- Lesson 14 Lab: Advanced Ansible Tower Usage
- Lesson 14 Lab Solution: Advanced Ansible Tower Usage

---

## Module 4: Managing Environments with Ansible

- Module Introduction

### Lesson 15: Managing Windows with Ansible

- Learning objectives
- 15.1 Understanding Requirements for Managing Windows
- 15.2 Using Playbooks to Manage Windows
- Lesson 15 Lab: Managing Windows with Ansible
- Lesson 15 Lab Solution: Managing Windows with Ansible

### Lesson 16: Managing Azure with Ansible

- Learning objectives
- 16.1 Understanding Requirements for Managing Azure
- 16.2 Using Playbooks to Manage Azure
- Lesson 16 Lab: Managing Azure
- Lesson 16 Lab Solution: Managing Azure

### Lesson 17: Managing Containers

- Learning objectives
- 17.1 Understanding Requirements for Managing Docker
- 17.2 Using Playbooks to Manage Docker
- 17.3 Managing Podman Containers
- Lesson 17 Lab: Managing Containers
- Lesson 17 Lab Solution: Managing Containers

### Lesson 18: Managing AWS with Ansible

- Learning objectives
- 18.1 Understanding Requirements for Managing AWS
- 18.2 Using Playbooks to Manage AWS
- 18.3 Configuring Dynamic Inventory
- Lesson 18 Lab: Managing AWS with Ansible
- Lesson 18 Lab Solution: Managing AWS with Ansible

### Lesson 19: Managing Network Devices with Ansible

- Learning objectives
- 19.1 Understanding Network Device Management
- 19.2 Setting Up Cisco SMB Devices
- 19.3 Configuring Cisco SMB Devices with Ansible
- 19.4 Using Generic Modules for Network Device Management
- Lesson 19 Lab: Automating Switch Setup with Ansible
- Lesson 19 Lab Solution: Automating Switch Setup with Ansible

### Lesson 20: Managing Virtual Machines with Ansible

- Learning objectives
- 20.1 Managing KVM Virtual Machines
- 20.2 Understanding vSphere Management
- 20.3 Managing ESXi
- Lesson 20 Lab: Managing a KVM Based Virtual Classroom with Ansible
- Lesson 20 Lab Solution: Managing a KVM Based Virtual Classroom with Ansible

### Lesson 21: Managing Kubernetes with Ansible

- Learning objectives
- 21.1 Understanding Requirements for Managing Kubernetes
- 21.2 Preparing the Kubernetes Setup
- 21.3 Writing a Playbook to Create a Kubernetes Cluster
- 21.4 Running the Playbook to Create a Kubernetes Cluster
- 21.5 Managing Kubernetes Resources
- Lesson 21 Lab: Automating Kubernetes Application Deployment with Ansible
- Lesson 21 Lab Solution: Automating Kubernetes Application Deployment with Ansible

