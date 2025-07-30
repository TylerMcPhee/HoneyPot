Honeypot Project

## Overview

This project implements a basic SSH honeypot using Python and `paramiko`. A honeypot is a decoy system designed to attract cyber attackers and log their actions. This implementation simulates an SSH server, accepts login attempts, and provides a fake shell environment for attackers. All activity is logged for analysis.

## Features

- Emulates an SSH server using `paramiko`
- Customizable username/password for login
- Logs attacker IPs and commands
- Simulates a shell environment for deeper interaction
- Optional tarpit mode to delay responses and slow attackers
- Multi-threaded to handle multiple concurrent connections
