# Ubuntu 22.04 (Jammy Jellyfish) Installation using Vagrant

This project demonstrates how to create and manage an Ubuntu 22.04 LTS Virtual Machine using Vagrant and VirtualBox.

## Prerequisites

- Git Bash
- Vagrant
- VirtualBox

**Open Git Bash**

## Step 1: Create a Project Directory

```bash
mkdir ubuntu-vagrant
cd ubuntu-vagrant
```

## Step 2: Initialize the Vagrant Project

```bash
vagrant init ubuntu/jammy64
```

This command creates a `Vagrantfile` in the current directory.

## Step 3: Start the Virtual Machine

```bash
vagrant up
```

Vagrant will:

- Download the Ubuntu 22.04 LTS box (only the first time)
- Create a VirtualBox virtual machine
- Boot the VM automatically

## Step 4: Connect to the VM

```bash
vagrant ssh
```

You should see:

```bash
vagrant@ubuntu-jammy:~$
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

Check the current directory:

```bash
pwd
```

Check Ubuntu version:

```bash
lsb_release -a
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

Restart the VM:

```bash
vagrant reload
```

Stop the VM:

```bash
vagrant halt
```

Destroy the VM:

```bash
vagrant destroy
```

List installed boxes:

```bash
vagrant box list
```

Remove the Ubuntu box:

```bash
vagrant box remove ubuntu/jammy64
```

## Project Structure

```
ubuntu-vagrant/
│── Vagrantfile
└── README.md
```

## Author

**Koushik**  
Learning DevOps with Vagrant and VirtualBox.