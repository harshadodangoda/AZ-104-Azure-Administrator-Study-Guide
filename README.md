# AZ-104: Microsoft Azure Administrator - Study Guide

This repository is dedicated to preparing for the **AZ-104: Microsoft Azure Administrator** certification exam. It includes study materials, resources, and practical labs to help you get hands-on experience with Azure services.

## Table of Contents
1. [Overview](#overview)
2. [Study Plan](#study-plan)
3. [Resources](#resources)
4. [Hands-On Labs](#hands-on-labs)
5. [Exam Preparation](#exam-preparation)
6. [License](#license)

## Overview
The **AZ-104: Microsoft Azure Administrator** exam measures your ability to manage Azure subscriptions, implement storage solutions, deploy virtual machines, configure virtual networks, and monitor resources.

## Study Plan
The study plan is divided into phases:
- **Phase 1: Foundation & Basics** (Week 1-2)
- **Phase 2: Compute & Networking** (Week 3-4)
- **Phase 3: Storage & Security** (Week 5-6)
- **Phase 4: Monitoring, Backup & Governance** (Week 7-8)
- **Phase 5: Exam Preparation & Review** (Week 9-10)

Each phase includes the main concepts to learn, hands-on labs to practice, and links to the best resources.

## Resources
- [Microsoft Learn AZ-104](https://learn.microsoft.com/en-us/certifications/exams/az-104/)
- [Azure Documentation](https://learn.microsoft.com/en-us/azure/)
- [Whizlabs Practice Tests](https://www.whizlabs.com/)
- [MeasureUp Practice Exams](https://www.measureup.com/)
- [John Savill's AZ-104 Study Guide](https://www.youtube.com/user/NTFAQ)

## Hands-On Labs
This section contains practical exercises to practice the concepts covered in the study plan.

### Lab 1: Creating a Virtual Machine in Azure
```bash
# Using Azure CLI to create a VM
az vm create --resource-group MyResourceGroup --name MyVM --image UbuntuLTS --admin-username azureuser --generate-ssh-keys
