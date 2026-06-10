Linux Notes

This repository contains my Linux studies and notes as I build my skills in System Administration, Networking, and Cybersecurity.

Topics I Am Studying

- Linux Fundamentals
- Linux File System
- File Management
- Permissions
- Users and Groups
- Processes
- Services
- Networking Commands
- Package Management
- Logs
- Bash Basics

---

Linux Fundamentals

Linux is an open-source operating system widely used in servers, cloud environments, and cybersecurity.

Why is it important?

- Most servers run Linux.
- Widely used in Cybersecurity and Cloud Computing.
- Essential for SOC analysts.

---

Linux File System

Linux organizes files using a hierarchical directory structure.

Common directories:

- /home
- /etc
- /var
- /usr
- /tmp

Useful Commands:

pwd
ls
cd

---

File Management

File management involves creating, viewing, copying, moving, and deleting files.

Useful Commands:

touch file.txt
cp file.txt backup.txt
mv file.txt documents/
rm file.txt
cat file.txt

---

Permissions

Linux uses permissions to control access to files and directories.

Permission Types:

- Read (r)
- Write (w)
- Execute (x)

Useful Command:

chmod 755 script.sh

Why is it important for Cybersecurity?

- Prevents unauthorized access.
- Protects sensitive files.

---

Users and Groups

Linux allows multiple users and groups.

Useful Commands:

whoami
id
useradd
passwd

Why is it important?

- Supports access control.
- Helps enforce security policies.

---

Processes

Processes are running programs in Linux.

Useful Commands:

ps
top
htop
kill

Why is it important?

- Helps identify suspicious activity.
- Useful during incident investigations.

---

Services

Services are background programs managed by the operating system.

Useful Commands:

systemctl status ssh
systemctl start ssh
systemctl stop ssh

---

Networking Commands

Linux provides tools for network troubleshooting and analysis.

Useful Commands:

ip addr
ping google.com
ss -tuln
ip route

Why is it important for SOC?

- Helps investigate connectivity issues.
- Assists in network monitoring.

---

Package Management

Package managers install and update software.

Ubuntu/Debian:

apt update
apt upgrade
apt install nginx

---

Logs

Logs record system and application events.

Common Log Locations:

/var/log

Useful Commands:

journalctl
tail -f /var/log/syslog

Why is it important for Cybersecurity?

- Logs are essential for monitoring and investigations.

---

Bash Basics

Bash is the default command-line shell in many Linux distributions.

Examples:

echo "Hello World"
mkdir test

Why is it important?

- Automates tasks.
- Improves productivity.
- Supports security operations.

---

Linux Skills Progress

✅ Linux Fundamentals

✅ Linux File System

✅ File Management

✅ Permissions

✅ Users and Groups

✅ Processes

✅ Services

✅ Networking Commands

✅ Package Management

✅ Logs

🔄 Bash Scripting

---

Career Goal

SOC Analyst → Blue Team → Cloud Security
