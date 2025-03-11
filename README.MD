# Ansible Test Environment

## Overview

This repository is designed for educational purposes and demonstrates the usage of **Ansible** in a testing environment. It contains configurations, playbooks, and other resources required to automate and manage various aspects of system administration in a virtualized network environment.

## Setup

The setup consists of the following components:

- **Master Server**: A Linux-based system (e.g., Ubuntu, CentOS, etc.) that acts as the control node for Ansible.
- **Virtual Machines**: Two virtual machines (VMs) deployed within a single private network, which are used for testing various Ansible playbooks, tasks, and automation scripts.

### Virtual Machine Setup

- Both virtual machines are set up to be in the same network, allowing them to communicate with each other and the master server.
- The VMs can be used for testing software deployment, configuration management, and other automation tasks using Ansible.

### Master Server Configuration

- The master server runs a Linux distribution (e.g., Ubuntu, CentOS).
- Ansible is installed on the master server and is used to manage the virtual machines.
- All necessary configurations, such as inventory files, variables, and playbooks, are stored in this repository.

## How to Use

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/your-username/Ansible-test-environment.git
   cd Ansible-test-environment
   cp ansible.cfg.template ansible.cfg
   ```

   Then edit the variables as you need.
