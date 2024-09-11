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
 ![WhatsApp Image 2024-09-11 at 22 51 27_9a3f8c56]

</div>

#### 2. Help Option
To display usage information and examples:


<div align="center">
![WhatsApp Image 2024-09-11 at 23 06 21_64db3b14]

</div>

#### 3. Version Information
To display the current version of the `sysopctl` command:


<div align="center">
![WhatsApp Image 2024-09-11 at 23 06 40_a6c1e758]

</div>

### System Management Operations

#### Part 1: Easy Level

##### 1. List Running Services
Lists all active services on the system, similar to `systemctl list-units --type=service`.

**Command:**

<div align="center">

![WhatsApp Image 2024-09-11 at 23 07 05_03822e55]


</div>

##### 2. View System Load
Displays the current system load averages, similar to the output from the `uptime` command.

**Command:**

<div align="center">
![WhatsApp Image 2024-09-11 at 23 07 31_a0960f43]

</div>

#### Part 2: Intermediate Level

##### 1. Manage System Services
Starts or stops a specific service, akin to using `systemctl start/stop`.

**Start a Service:**
**Stop a Service:**

<div align="center">
![WhatsApp Image 2024-09-11 at 23 07 54_c4c7961a]
</div>

##### 2. Check Disk Usage
Displays disk usage statistics by partition, similar to `df -h`.

**Command:**


<div align="center">


![WhatsApp Image 2024-09-11 at 23 08 23_576f000f]


</div>

#### Part 3: Advanced Level

##### 1. Monitor System Processes
Monitors real-time process activity, similar to the `top` or `htop` commands.

**Command:**

<div align="center">
![WhatsApp Image 2024-09-11 at 23 08 50_a5b98f1b]

</div>

##### 2. Analyze System Logs
Analyzes and summarizes recent critical log entries, utilizing tools like `journalctl`.

**Command:**


<div align="center">
![WhatsApp Image 2024-09-11 at 23 09 30_374d1125]

</div>

##### 3. Backup System Files
Initiates a backup of specified files or directories, potentially using `rsync` for file transfers.

**Command:**


<div align="center">

![WhatsApp Image 2024-09-11 at 23 00 10_ecdd165e](https://github.com/user-attachments/assets/eaf58044-94e7-4b2b-9ebf-02e6f21254c2)
![WhatsApp Image 2024-09-11 at 23 00 44_5c61f688](https://github.com/user-attachments/assets/e5f5575a-6d1f-4238-a323-75075e0edb79)


</div>


