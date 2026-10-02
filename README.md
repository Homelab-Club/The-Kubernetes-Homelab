# The-Kubernetes-Homelab
<img width="705" height="1125" alt="The Kubernetes Homelab" src="https://github.com/user-attachments/assets/a459d414-6e0a-4e03-95b4-277d424ca570" />
# 📖 The Kubernetes Homelab

**By Kevin Villarreal | Homelab Club**

Welcome to the official GitHub repository for *The Kubernetes Homelab*, part of the Homelab Club book series.

This repository contains the configuration files, Ansible playbooks, YAML manifests, scripts, and practical examples that accompany the book. These resources help you follow the hands-on exercises without having to type lengthy configuration files from the printed or digital edition.

## About the Book

*The Kubernetes Homelab* guides you through building and managing a Kubernetes cluster in your own homelab. You will learn how to prepare Linux virtual machines, automate configuration with Ansible, deploy containerized applications, configure networking and storage, and explore monitoring, security, and GitOps.

The examples are designed for a learning environment using Proxmox VE and Ubuntu Server. You can adapt them to your own infrastructure.

## Repository Contents

Files are organized by chapter to make it easy to find the resources associated with each exercise.

- **Chapter 5: Ansible**: Ansible configuration, example inventory, and the Linux preparation playbook.
- **Kubernetes installation and configuration**: Cluster setup instructions and configuration files.
- **Application deployments**: Kubernetes manifests and supporting configuration.
- **Networking and storage**: Examples for exposing applications and managing persistent data.
- **Automation and GitOps**: Resources for automating deployments and managing configuration through Git.

Additional files will be added as the book develops.

## How to Use This Repository

1. Browse the folders to find the chapter you are following.
2. Open a file to view its contents directly on GitHub.
3. Use the **Raw** button to view the plain-text version of a file.
4. Copy the contents or download the file to your homelab.
5. Review the configuration and customize it for your environment before running it.

You can also download the repository as a ZIP file using **Code → Download ZIP** on the repository's main page.

## Important: Customize Before Use

The examples are provided for educational purposes. Your network addresses, usernames, storage configuration, and other settings may differ from those used in the book.

Review each file before executing it. Never copy credentials, private keys, or other sensitive information into a public repository. Example inventory files should be customized for your own environment.

Some commands require administrative privileges and can modify system configuration. Understand what a command does before running it.

## Requirements

Depending on the chapter, you may need:

- Proxmox VE or another supported virtualization platform
- Ubuntu Server or another explicitly supported Linux distribution
- Basic Linux command-line and SSH knowledge
- Ansible for configuration automation
- A working network with DNS and Internet connectivity
- A Kubernetes cluster for the later exercises

Check the relevant chapter for the specific requirements.

## About Homelab Club

Homelab Club helps IT enthusiasts, self-hosters, and aspiring IT professionals learn through practical homelab projects.

Explore more resources and apparel at [homelab-club.com](https://homelab-club.com).

## Feedback and Contributions

Found an issue, outdated command, or improvement? Please open a GitHub issue describing the problem and the chapter or file concerned.

Thank you for learning with Homelab Club. Happy homelabbing!

**Kevin Villarreal**  
Author, *The Kubernetes Homelab*  
Homelab Club
