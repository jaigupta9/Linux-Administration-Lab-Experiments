# Linux Command Line Laboratories

<div align="center">

![Linux Labs Banner](screenshots/linux.gif)

</div>

<div align="center">
  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Linux](https://img.shields.io/badge/Platform-Linux-blue.svg)](https://www.linux.org/)
[![RedHat](https://img.shields.io/badge/RedHat-Academy-red.svg)](https://www.redhat.com/academy)
  
</div>

## 📚 Repository Overview

This repository contains a comprehensive collection of Linux command-line laboratory exercises designed to build proficiency in essential system administration tasks. Each lab is meticulously documented with clear instructions and screenshot evidence of command execution.

## 📊 Repository Structure

```mermaid
graph TD
    A[Linux Command Line Labs] --> B[Lab Files]
    A --> C[Screenshots Directory]
    B --> D[Lab-1,2.md]
    B --> E[Lab-3,4.md]
    B --> F[Lab-5,6.md]
    B --> G[Lab-7,8.md]
    B --> H[Lab-9,10.md]
    B --> I[Lab-11,12.md]
    B --> J[Lab-13,14.md]
    B --> K[Lab-15,16.md]
    C --> L[File Operations]
    C --> M[System Info]
    C --> N[User Management]
    C --> O[Permissions]
    C --> P[Text Editors]
    C --> Q[Process Management]
    C --> R[Package Management]
```

## 📋 Complete Lab Plan


| Sr. No. | Lab Number | Experiments |
|---------|------------|-------------|
| 1       | 1-2        | Use the touch command to create sets of empty practice files. Create six files with names of the form `songX.mp3`, `snapX.jpg`, `filmX.avi`. Create three subdirectories: `friends`, `family`, and `work` using a single command. |
| 2       | 3-4        | View the `gedit` man page. Use `man -k ext4` to find the command to tune ext4 file-system parameters. Use brace expansion and wildcards for file matching. Explore `cat`, `less`, and `more` commands. |
| 3       | 5-6        | Use `vim` and `nano` to edit files. Use the `lab_file` shell variable. Enter visual mode in Vim, remove the last seven characters of the first column, and preserve only the first four characters. |
| 4       | 7-8        | Create the `/home/consultants` directory. Add write permission to the `consultants` group using symbolic method. Forbid access to others. Change the `umask` for `operator1` user to prohibit all access for non-group users. |
| 5       | 9-10       | Implement `ps`, `top`, and `kill` commands with their options. Install, update, and remove software using `apt-get`. |
| 6       | 11-12      | Create the `operator1` user and set the password. Add `operator2` and `operator3` users with passwords. Use `usermod -c` to update comments for `operator1`. Remove `operator3` from the system. |
| 7       | 13-14      | Use `chown` and `chmod` commands with their options to modify ownership and permissions. |
| 8       | 15-16      | Write shell scripts to print system information and perform basic mathematical calculations. Use redirection operators to store command outputs. |
| 9       | 17-18      | Implement `fdisk`, `parted`, `df`, and `du` commands with their options for disk management. |
| 10      | 19-20      | Use `rsync`, `tar`, and compression commands to efficiently store and transfer files. |
| 11      | 21-22      | Configure system networking using `netplan` and `nmcli`. Set up and configure the system firewall. |
| 12      | 23-24      | Use `top`, `htop`, `iostat`, and `vmstat` to monitor system performance. Tune the system using `sysctl` and `tuned`. Perform log management and analysis using `syslog` and `journalctl`. |
| 13      | 25-26      | Execute `ssh` commands to securely access remote computers. |
| 14      | 27-28      | Run shell scripts to create functions and perform advanced string manipulations. Use `cron` and `at` commands to schedule future tasks. |
| 15      | 29-30      | Create and manage containers to create virtual machines on the system. |


## 🔥 Embark on Your Linux Adventure

<div style="display: flex; justify-content: center; align-items: center; gap: 20px;">
  <div style="flex: 1;">
    <h3>🧭 Begin Your Quest</h3>
    <ol>
      <li><b>Summon the repository:</b>
        <pre><code>git clone https://github.com/Anuj-er/Linux-Administration-Lab-Experiments/ </code></pre>
      </li>
      <li><b>Enter the training grounds:</b>
        <pre><code>cd linux-command-labs</code></pre>
      </li>
      <li><b>Study the ancient scrolls:</b> Each Lab-X,X.md file contains wisdom and challenges</li>
      <li><b>Consult the visual tomes:</b> Screenshots directory holds visual proof of successful incantations</li>
    </ol>
  </div>
  
  <div style="flex: 1;">
    <blockquote>
      "The journey of a thousand commands begins with a single terminal."
    </blockquote>
  </div>
</div>

## 🧠 The Philosophy of Learning Linux

These laboratories are crafted with the wisdom of Red Hat's time-tested pedagogical approach. They embrace a holistic learning philosophy that transforms novices into masters through progressive challenges and hands-on experience.

<table>
  <tr>
    <td width="50%">
      <h3>🔨 Forge Knowledge Through Practice</h3>
      <p>Theoretical concepts come alive through hands-on exercises that build muscle memory and deep understanding.</p>
    </td>
    <td width="50%">
      <h3>👁️ See To Believe, Do To Understand</h3>
      <p>Visual demonstrations and verified outputs create a feedback loop that reinforces learning.</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🏗️ Scaffold Your Linux Knowledge</h3>
      <p>Each lab builds upon previous concepts, creating a solid foundation that supports advanced skills.</p>
    </td>
    <td width="50%">
      <h3>🌐 Learn As You Would Work</h3>
      <p>Labs simulate real-world scenarios, preparing you for actual system administration challenges.</p>
    </td>
  </tr>
</table>

## 📚 Wisdom Sources

<div style="display: flex; flex-wrap: wrap; gap: 15px; justify-content: center;">
  <div style="border: 1px solid #ddd; border-radius: 8px; padding: 10px; width: 200px; text-align: center;">
    <h3>Red Hat Academy</h3>
    <p>The foundation of enterprise Linux education</p>
  </div>
  
  <div style="border: 1px solid #ddd; border-radius: 8px; padding: 10px; width: 200px; text-align: center;">
    <h3>RH124</h3>
    <p>System Administration I</p>
  </div>
  
  <div style="border: 1px solid #ddd; border-radius: 8px; padding: 10px; width: 200px; text-align: center;">
    <h3>RH134</h3>
    <p>System Administration II</p>
  </div>
  
  <div style="border: 1px solid #ddd; border-radius: 8px; padding: 10px; width: 200px; text-align: center;">
    <h3>Linux Documentation Project</h3>
    <p><a href="https://tldp.org/">tldp.org</a></p>
  </div>
  
  <div style="border: 1px solid #ddd; border-radius: 8px; padding: 10px; width: 200px; text-align: center;">
    <h3>Man Pages</h3>
    <p>The original Linux knowledge base</p>
  </div>
</div>

## 📜 Freedom License

<div align="center">
  <p>This project is licensed under the MIT License - a beacon of open source collaboration that lights the path for all who wish to learn, modify, and share.</p>
  <p>See the LICENSE file for the full text of digital liberty.</p>
</div>
