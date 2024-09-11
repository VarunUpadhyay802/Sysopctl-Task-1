# `sysopctl` Command Documentation

**Version:** v0.1.0

## Introduction
`sysopctl` is a command-line tool designed for managing various system operations. It provides users with an easy-to-use interface for interacting with system services, monitoring processes, analyzing logs, and performing system backups. This tool aims to simplify common system administration tasks, offering functionality similar to other Linux commands like `systemctl`, `uptime`, `df`, `top`, `journalctl`, and `rsync`.

## Usage
All commands follow the general syntax:


### Basic Commands

#### 1. Manual Page
To access the full documentation through the manual:


<div align="center">

![IMG-20240911-WA0023](https://github.com/user-attachments/assets/7f904283-270d-4d79-895a-b78c8f5de9d9)

</div>

#### 2. Help Option
To display usage information and examples:


<div align="center">

![IMG-20240911-WA0024](https://github.com/user-attachments/assets/3ab9bb8b-6ab6-47aa-b19e-3a69d8fed4dd)

</div>

#### 3. Version Information
To display the current version of the `sysopctl` command:


<div align="center">

![IMG-20240911-WA0025](https://github.com/user-attachments/assets/526c7748-938f-4f53-98ae-7dd1a97adf68)

</div>

### System Management Operations

#### Part 1: Easy Level

##### 1. List Running Services
Lists all active services on the system, similar to `systemctl list-units --type=service`.

**Command:**

<div align="center">


![IMG-20240911-WA0026](https://github.com/user-attachments/assets/4a7ec95f-7bc7-4fb9-85fa-ffc8533eb6ff)


</div>

##### 2. View System Load
Displays the current system load averages, similar to the output from the `uptime` command.

**Command:**

<div align="center">

![IMG-20240911-WA0027](https://github.com/user-attachments/assets/2646f102-3063-4026-a9ac-f2547cc78c5f)

</div>

#### Part 2: Intermediate Level

##### 1. Manage System Services
Starts or stops a specific service, akin to using `systemctl start/stop`.

**Start a Service:**
**Stop a Service:**

<div align="center">

</div>

##### 2. Check Disk Usage
Displays disk usage statistics by partition, similar to `df -h`.

**Command:**


<div align="center">


![IMG-20240911-WA0029](https://github.com/user-attachments/assets/b00d9efb-024f-4a35-879a-9796657df911)


</div>

#### Part 3: Advanced Level

##### 1. Monitor System Processes
Monitors real-time process activity, similar to the `top` or `htop` commands.

**Command:**

<div align="center">


![image](https://github.com/user-attachments/assets/e8d57fbb-4619-4f7d-8c6c-e70e17d7c1aa)


</div>

##### 2. Analyze System Logs
Analyzes and summarizes recent critical log entries, utilizing tools like `journalctl`.

**Command:**


<div align="center">


![niceee](https://github.com/user-attachments/assets/4f54e609-91b1-4c70-a1a6-4e2317d5a679)


</div>

##### 3. Backup System Files
Initiates a backup of specified files or directories, potentially using `rsync` for file transfers.

**Command:**


<div align="center">

![WhatsApp Image 2024-09-11 at 23 00 10_ecdd165e](https://github.com/user-attachments/assets/eaf58044-94e7-4b2b-9ebf-02e6f21254c2)
![WhatsApp Image 2024-09-11 at 23 00 44_5c61f688](https://github.com/user-attachments/assets/e5f5575a-6d1f-4238-a323-75075e0edb79)


</div>


