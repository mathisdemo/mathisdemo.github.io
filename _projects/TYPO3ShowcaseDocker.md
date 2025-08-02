---
layout: page
title: TYPO3ShowcaseDocker
description: 🐳 Ready-to-use TYPO3 Docker
full_name: mpek29/TYPO3ShowcaseDocker
img: assets/img/projects/TYPO3ShowcaseDocker/main.png
importance: 1
git: https://github.com/mpek29/TYPO3ShowcaseDocker
github: https://github.com/mpek29/TYPO3ShowcaseDocker
category: Computer Science
subcategory: DevOps & Automation
---

**TYPO3ShowcaseDocker** is an open-source project designed to provide a **fully containerized TYPO3 CMS development environment using Docker**, enabling fast setup, local development, and easy deployment of TYPO3-based showcase websites.

## 🎯 Purpose

- 🐳 **Dockerized Environment**: Simplifies launching TYPO3 and MySQL services in isolated containers.  
- ⚙️ **TYPO3 CMS**: Ready-to-use setup for building and showcasing TYPO3 sites.  
- 💻 **CLI-Driven Workflow**: Manage TYPO3 installation, extensions, and configuration through terminal commands.  
- 🔄 **Portable & Reproducible**: Environment can be cloned, shared, and run consistently on any Docker-enabled system.

## 📝 Features

| 🏷️ Feature                  | 🔍 Description                                      |
|----------------------------|----------------------------------------------------|
| 🐳 **Docker Compose Setup**  | Multi-container stack with TYPO3 and MySQL services|
| 🔌 **Pre-installed TYPO3**   | TYPO3 CMS installed and configured for quick start |
| 💻 **CLI Tools Included**    | TYPO3 CLI tools available for extension and config management |
| 🔄 **Volume Mapping**         | Local folder sync for TYPO3 files and data persistence |
| 🛠️ **Configurable via Env**  | Database credentials, ports, and TYPO3 settings adjustable via environment variables |
| 🧪 **Development Friendly**  | Debug mode enabled with logs accessible via CLI    |
| 📂 **Git-ready Structure**   | .gitignore optimized for TYPO3 development          |

## 🗂️ Project Structure

```bash
TYPO3ShowcaseDocker/
├── docker-compose.yml          # Docker Compose configuration
├── typo3/                     # TYPO3 files synced with container
├── .gitignore                  # Ignore sensitive files and cache
├── README.md                   # This documentation

