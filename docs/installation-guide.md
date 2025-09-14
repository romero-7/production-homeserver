# Ubuntu Server Installation Guide

Documentation of the complete server setup process for the Dell OptiPlex 3070.

## Pre-Installation

### Hardware Preparation
- Dell OptiPlex 3070 with RAM upgraded to 32GB
- Storage configuration: SSD (256GB) + 2x HDD (1TB each)
- Network: Gigabit Ethernet connection

### Installation Media
- Ubuntu Server 22.04 LTS ISO
- USB drive creation method: Balena Etcher

## Installation Process

### Step 1: BIOS Configuration
- Boot order: USB first
- UEFI/Legacy: Legacy (server does not support UEFI BIOS)
- Secure Boot: Disabled

### Step 2: Ubuntu Server Setup
- Language: English
- Keyboard: English UK
- Network: DHCP (automatic IP assignment)
- Storage: Manual partitioning

### Step 3: System Configuration  
- Username: romero
- Hostname: romser
- SSH: OpenSSH server installed for remote access

## Post-Installation Configuration

### Initial Setup
- System updates: `sudo apt update && sudo apt upgrade`
- Network configuration: [Static IP configured later]
- Storage mounting: Additional HDDs configured for data and backup

### Security Configuration
- SSH key-based authentication setup
- Firewall configuration: `ufw enable`
- User permissions and sudo access
