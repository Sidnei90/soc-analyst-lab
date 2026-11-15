# Linux Fundamentals

## 1. Introduction

Linux is an open-source operating system widely used in servers, cloud infrastructure, and cybersecurity environments.

Understanding Linux is essential for system administration, security analysis, and infrastructure protection.

This document records practical Linux fundamentals using Parrot OS as the learning environment.

## 2. Learning Objectives

- Understand basic Linux commands.
- Navigate the Linux filesystem.
- Identify system information.
- Understand users and permissions.
- Develop practical command-line skills.

## 3. System Information

The following commands help identify the current user, hostname, kernel version, and Linux distribution.

| Command | Description |
|---|---|
| `whoami` | Displays the current username. |
| `hostname` | Displays the machine hostname. |
| `uname -a` | Displays kernel and system information. |
| `cat /etc/os-release` | Displays Linux distribution information. |

## 4. Filesystem Navigation

Linux uses a hierarchical filesystem structure.

| Command | Description |
|---|---|
| `pwd` | Displays the current working directory. |
| `ls` | Lists directory contents. |
| `ls -la` | Lists all files, including hidden files, with details. |
| `cd` | Changes the current directory. |

### Important Linux Directories

| Directory | Purpose |
|---|---|
| `/` | Root directory. |
| `/home` | User home directories. |
| `/etc` | System configuration files. |
| `/var` | Variable data and logs. |
| `/tmp` | Temporary files. |
| `/usr` | User applications and utilities. |

## 5. System Resources

These commands provide basic information about storage and memory.

| Command | Description |
|---|---|
| `df -h` | Displays filesystem disk usage. |
| `free -h` | Displays memory usage. |

## 6. Practical Exercises

The following commands will be executed in the Parrot OS virtual machine.

```bash
whoami
hostname
uname -a
cat /etc/os-release

pwd
ls -la

df -h
free -h
```

### Practical Results

Results will be documented after executing and analyzing each command.

- Current operating system:
- Kernel version:
- Current username:
- Hostname:
- Available disk space:
- Memory information:

## 7. Security Relevance

Linux fundamentals are important for cybersecurity because they help security professionals:

- Understand system configurations.
- Identify users and system resources.
- Navigate security-related files.
- Prepare for permission and access-control analysis.
- Investigate system behavior.

## 8. Learning Progress

- [ ] Basic Linux commands
- [ ] Filesystem navigation
- [ ] System information
- [ ] Disk and memory inspection
- [ ] Users and groups
- [ ] File permissions

## 9. References

- [Linux Documentation Project](https://tldp.org/)
- [Parrot Security Documentation](https://parrotsec.org/docs/)
- [Linux man-pages](https://man7.org/linux/man-pages/)

---

**Project:** Linux Security Lab

**Environment:** Parrot OS / VirtualBox

**Focus:** Linux Administration and Cybersecurity Fundamentals
