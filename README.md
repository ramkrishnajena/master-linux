
# 🐧 Linux Mastery TOC — Zero to Hero

This is a **complete, no-BS roadmap** to take you from
**“I know nothing about Linux” → “I understand Linux like a pro.”**

Linux mastery is **not about memorizing commands**.
It’s about understanding **how the operating system works under the hood** and being able to **operate, debug, and automate systems confidently**.

---

## 🧱 Phase 1: Foundation — *Survival Mode*

> **Goal:** Navigate Linux without a mouse and understand the filesystem.

### 1. Philosophy & History

* What is the **Kernel**? (Linux vs Unix)
* The **Unix Philosophy** — *Do one thing and do it well*
* Linux Distributions:

  * Debian / Ubuntu
  * RHEL / CentOS / Rocky
  * Arch Linux

### 2. Directory Structure (The Tree)

* Root directory `/`
* Purpose of:

  * `/bin`
  * `/etc`
  * `/var`
  * `/home`
  * `/usr`
  * `/tmp`
  * `/dev`

### 3. Basic File Operations

* Navigation:

  * `pwd`, `cd`, `ls (-l, -a, -h)`
* File & directory management:

  * `cp`, `mv`, `rm`, `mkdir`, `touch`
* Viewing files:

  * `cat`, `less`, `head`, `tail`

### 4. Shell & Help System

* What is **Bash / Zsh**
* The most important command:

  * `man`
* Tab completion & command history

---

## 🛠 Phase 2: System Administration — *The Operator*

> **Goal:** Run and manage a Linux server.

### 1. Permissions & Ownership

* Read / Write / Execute (`rwx`)
* Commands:

  * `chmod` (numeric & symbolic)
  * `chown`, `chgrp`
* Root access:

  * `sudo` vs `su`

### 2. Package Management

* Debian / Ubuntu:

  * `apt`, `dpkg`
* RHEL-based:

  * `dnf`, `rpm`
* Compiling from source:

  * `make`, `gcc` (conceptual understanding)

### 3. Text Editors (Choose One)

* **Nano** — beginner friendly
* **Vim / Neovim** — power user (recommended)

  * modes, buffers, macros

### 4. Process Management

* Monitoring:

  * `top`, `htop`, `ps aux`
* Control:

  * `kill`, `killall`, `nice`, `renice`
* Jobs:

  * `&`, `bg`, `fg`, `jobs`

---

## 🌐 Phase 3: Networking & Security — *The Guardian*

> **Goal:** Connect systems securely and debug network issues.

### 1. Networking Basics

* Commands:

  * `ip addr`, `ping`, `ss`
* DNS:

  * `dig`, `nslookup`
* Hosts file:

  * `/etc/hosts`

### 2. SSH (Secure Shell)

* Remote login
* SSH keys:

  * `ssh-keygen`
* Passwordless login
* File transfer:

  * `scp`, `rsync`

### 3. Firewalls & Security

* Basic:

  * `ufw`, `firewalld`
* Advanced:

  * `iptables`, `nftables`
* Special permissions:

  * SUID, SGID, Sticky Bit

---

## 🤖 Phase 4: Automation & Scripting — *The Developer*

> **Goal:** Eliminate repetitive manual work.

### 1. Bash Scripting

* Shebang:

  * `#!/bin/bash`
* Variables
* Loops:

  * `for`, `while`
* Conditionals:

  * `if / else`
* Exit codes:

  * `$?`

### 2. Redirection & Pipes

* Streams:

  * `stdin`, `stdout`, `stderr`
* Piping:

  * `|`
* Redirection:

  * `>`, `>>`, `2>`

### 3. Text Processing Power

* `grep` — search
* `awk` — data processing
* `sed` — text transformation
* Regular Expressions (Regex)

### 4. Scheduling Tasks

* `cron` / `crontab`
* One-time jobs:

  * `at`

---

## 💾 Phase 5: Storage & Boot Process — *The Architect*

> **Goal:** Control disks, filesystems, and startup flow.

### 1. Storage Management

* Partitioning:

  * `fdisk`, `gdisk`, `parted`
* Filesystems:

  * `mkfs` (ext4, xfs, btrfs)
* Mounting:

  * `mount`, `umount`
  * `/etc/fstab`
* LVM:

  * Physical Volumes
  * Volume Groups
  * Logical Volumes

### 2. Boot Process

* BIOS / UEFI
* GRUB
* Kernel
* Init / systemd
* Runlevels / Targets

### 3. Service Management (systemd)

* `systemctl`

  * start, stop, enable, disable, status
* Logs:

  * `journalctl`
* Creating custom services

---

## 🚀 Phase 6: Advanced Internals & Performance — *The Guru*

> **Goal:** Debug, tune, and analyze Linux internals.

### 1. Kernel Interaction

* Virtual filesystems:

  * `/proc`, `/sys`
* Kernel modules:

  * `lsmod`, `modprobe`
* Runtime tuning:

  * `sysctl`

### 2. Performance Debugging

* Disk I/O:

  * `iostat`, `iotop`
* Network:

  * `tcpdump`, `iftop`
* System calls:

  * `strace`
* Open files:

  * `lsof`

### 3. Logs & Auditing

* `/var/log`
* `dmesg`
* Log rotation:

  * `logrotate`

---

## 📦 Phase 7: Modern Linux — *Virtualization & Containers*

> **Goal:** Run modern infrastructure on Linux.

* Virtualization:

  * KVM / QEMU basics
* Containers:

  * Docker / Podman
  * Images, Containers, Volumes, Networking

---

## 🏁 How to Start (Important)

❌ Don’t just read
✅ **Do things and break them**

### Step 1: Install a VM

* Use VirtualBox / VMware
* Install **Ubuntu Server (no GUI)** or **Rocky Linux**

### Step 2: Break It

* Misconfigure things
* Fix them **without reinstalling**
* Google less, read `man` more

That’s how real Linux skill is built.

---

If you want, I can:

* Turn this into a **Notion checklist**
* Create a **30 / 60 / 90 day Linux plan**
* Start **Phase 1 hands-on** with daily commands and tasks

Just say the word.

