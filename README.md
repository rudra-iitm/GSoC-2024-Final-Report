# GSoC 2024 Report: Container Chronicles 🚀

![GSoC Logo](https://github.com/rudra-iitm/GSoC-2024-Final-Report/blob/main/GSoC_Logo.png)

## The Container Odyssey: Packaging CUPS and Printer Apps 🚢

### The Champions Behind the Quest 🏆

![Linux Foundation](https://github.com/rudra-iitm/GSoC-2024-Final-Report/blob/main/LF_Logo.png)

### Mentors

Meet the guiding lights of this journey:

- **[Till Kamppeter](https://github.com/tillkamppeter)**: Expert in CUPS and printer apps.
- **[Cristovao Cordeiro](https://github.com/cjdcordeiro)**: Rockcraft specialist.
- **[Saurav Dharwadkar](https://github.com/SauravDharwadkar)**: Docker virtuoso.

## A Journey Through Containerization: Unpacking the Project 🎁

### The Vision Unveiled 🌟

The project embarked on an ambitious journey to encapsulate the Common Unix Printing System (CUPS) and various Printer Apps into OCI (Open Container Initiative) images using Rockcraft. This move is designed to simplify the deployment of these tools across diverse, immutable distributions, making them more accessible and easier to manage.

### Mission Objectives 🏹

- **Crafting OCI-Compliant Images**: Forge official OCI images for CUPS and Printer Apps.
- **Automating the Workflow**: Develop automation scripts for smooth version control and dependency management.
- **Ensuring Excellence**: Conduct rigorous testing to guarantee reliability and performance.

## The Blueprint of Success 🗺️

### Deliverables: What We Set Out to Achieve 🏆

- **Planned Deliverables**:
    - OCI images for CUPS and Printer Apps
    - Automation scripts for maintenance and versioning
    - Comprehensive testing and validation
    - Detailed documentation for installation and usage

- **Delivered Treasures**:
    - Fully functional OCI image for CUPS 
    - OCI images for various Printer Apps (ps-printer-app, hplip-printer-app, gutenprint-printer-app, ghostscript-printer-app)
    - Automation scripts for managing dependencies and updates
    - A GitHub CI pipeline for cups-rock to streamline processes
    - Initial documentation for installation and usage

- **Pending Adventures**:
    - In-depth testing and issue reporting for Printer Apps
    - Expansion of documentation for Printer Apps

### Technical Alchemy: How the Magic Was Made 🔮

- **Tools of the Trade**:

    - Docker
    - CUPS
    - Printer Apps
    - GitHub Actions
    - Rockcraft
    - Bash Scripting

- **Challenges and Triumphs**:

    One of the greatest hurdles was configuring dbus-daemon and avahi-daemon to work harmoniously within a Docker container and ensure proper printer discovery. Through persistent debugging and iterative problem-solving, this challenge was successfully overcome.

## The Ripple Effect: Impact and Insights 🌊

### Transforming the Organization 🌍

This project equips OpenPrinting to distribute CUPS and Printer Apps efficiently across immutable distributions. The implementation of GitHub Actions will reduce manual maintenance and streamline dependency updates, enhancing operational efficiency.

### Personal Growth: A Tale of Learning and Development 📚

The journey through containerization and Docker was a profound learning experience. I developed skills in debugging, consistency, and community engagement, gaining valuable insights into project management and technical problem-solving.

## Dive Deeper: Essential Links & Resources 🌟

### 🛠️ **Project Repositories**

Explore the codebases behind various printer apps:

- **cups-rock**: [GitHub Repository](https://github.com/rudra-iitm/cups-rock)
- **ps-printer-app-rock**: [GitHub Repository](https://github.com/rudra-iitm/ps-printer-app-rock)
- **hplip-printer-app-rock**: [GitHub Repository](https://github.com/rudra-iitm/hplip-printer-app-rock)
- **gutenprint-printer-app-rock**: [GitHub Repository](https://github.com/rudra-iitm/gutenprint-printer-app-rock)
- **ghostscript-printer-app**: [GitHub Repository](https://github.com/rudra-iitm/ghostscript-printer-app-rock)

### 🔄 **Noteworthy Pull Requests**

Check out these significant contributions and updates:

- **Update Automation Extension**: [Pull Request Link](https://github.com/ubuntu/desktop-snaps/pull/635)
- **Version Automation Extension**: [Pull Request Link](https://github.com/ubuntu/desktop-snaps/pull/636)
- **Rock-Version Schema Addition**: [Pull Request Link](https://github.com/ubuntu/desktop-snaps/pull/666)

### 📚 **Documentation & Guides**

For a comprehensive guide on Rockcraft, visit the official documentation:

- **Rockcraft Documentation**: [Explore Here](https://documentation.ubuntu.com/rockcraft/en/latest/)

## A Symphony of Thanks 🎶

A heartfelt thank you to my mentors [Till Kamppeter](https://github.com/tillkamppeter), [Cristovao Cordeiro](https://github.com/cjdcordeiro), and [Saurav Dharwadkar](https://github.com/SauravDharwadkar) for their guidance and support. 

A heartfelt tribute goes out to [Till Kamppeter](https://github.com/tillkamppeter). Without his guidance and leadership, this technical journey through code would have been directionless and silent.