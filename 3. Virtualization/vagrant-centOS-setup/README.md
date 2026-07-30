# CentOS Stream 9 Installation using Vagrant

This project demonstrates how to create and manage a CentOS Stream 9 Virtual Machine using Vagrant and VirtualBox.

## Prerequisites

- Git Bash
- Vagrant
- VirtualBox

**Open Git Bash**

## Step 1: Create a Project Directory

```bash
mkdir centos-vagrant
cd centos-vagrant
```

## Step 2: Initialize the Vagrant Project

```bash
vagrant init eurolinux-vagrant/centos-stream-9
```

This command creates a `Vagrantfile` in the current directory.

## Step 3: Start the Virtual Machine

```bash
vagrant up
```

Vagrant will:

- Download the CentOS Stream 9 box (only the first time)
- Create a VirtualBox virtual machine
- Boot the VM automatically

## Step 4: Connect to the VM

```bash
vagrant ssh
```

You should see:

```bash
[vagrant@localhost ~]$
```

## Step 5: Verify the Operating System

Check the current user:

```bash
whoami
```

Expected output:

```bash
vagrant
```

Check the operating system:

```bash
cat /etc/os-release
```

Check the kernel version:

```bash
uname -r
```

## Useful Vagrant Commands

Start the VM:

```bash
vagrant up
```

Connect to the VM:

```bash
vagrant ssh
```

Check VM status:

```bash
vagrant status
```

Suspend the VM:

```bash
vagrant suspend
```

Resume the VM:

```bash
vagrant resume
```

Stop the VM:

```bash
vagrant halt
```

Restart the VM:

```bash
vagrant reload
```

Destroy the VM:

```bash
vagrant destroy
```

Remove the downloaded box:

```bash
vagrant box remove eurolinux-vagrant/centos-stream-9
```

List installed boxes:

```bash
vagrant box list
```

## Project Structure

```
centos-vagrant/
│── Vagrantfile
└── README.md
```

## Author

**Koushik**  
Learning DevOps with Vagrant and VirtualBox.