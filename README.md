# LIA Project – Web Server VPS using Lightsail (Debian)

## Project Proposal:

The goal of this project is to set up a secure and automated web server environment using a VPS hosted on AWS Lightsail running Debian 12. The web server will serve a simple static website (index.html and style.css) and support automatic deployment triggered by GitHub commits via a webhook. This setup is aimed at a fictitious small business or developer who needs a low-cost, reliable server with minimal maintenance, basic security, and streamlined deployment.

Key components integrated into the project include:

- Basic system setup and security (user accounts, SSH keys, firewall configuration)
- Web server setup using Nginx for lightweight and efficient service
- Automated deployment triggered by webhook and GitHub commits

## Features

- Hosted on Lightsail (Debian)
- Nginx-based web server
- Auto-deployment from GitHub using webhook
- Secure setup (firewall, SSH keys)

## Repository Contents

- README.md: Overview of the project.
- LICENSE: The project's license.
- CHOICES: Details of the choices made during the setup (e.g., VPS provider, OS selection, web server choice).
- INSTALL: Step-by-step installation instructions for setting up the VPS and configuring the web server.
- `index.html` / `style.css`: Website files for the web server.

## Setup Instructions

Refer to the INSTALL.md file for the complete instructions on setting up the VPS.

## Project Timeline

## Week 2:

- Set up the project repository on GitHub with initial files:
  - README
  - LICENSE
  - CHOICES 
  - INSTALL
- Set up AWS Lightsail VPS with Debian.
- Install and configure Nginx, UFW, and update the system.
- Document initial configuration steps in the INSTALL file.
- Refined README, CHOICES, and INSTALL files with more details.
- Added Timeline.

### Week 3:

- Added `index.html` and `style.css` website files to the repository.
- Implemented a webhook service for auto-deployment from GitHub.
- Updated the `INSTALL.md` file with webhook setup instructions.
- Completed and fixed the `CHOICES` file with alternatives and final deployment strategy.
