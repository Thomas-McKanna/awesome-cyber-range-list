# Awesome Cyber Range List

A comprehensive and curated collection of tools, projects, and resources essential for building and managing cyber ranges. Whether you're setting up a training environment, conducting security assessments, or organizing Capture The Flag (CTF) competitions, this list provides the necessary infrastructure, gray zone, content tooling, pre-built environments, and educational aids to enhance your cyber range capabilities.

## Infrastructure Tooling

Tools and frameworks that facilitate the setup, deployment, and management of the underlying infrastructure for cyber ranges.

- **[Ansible](https://docs.ansible.com/)**: An open-source automation tool for configuration management, application deployment, and task automation across multiple systems.
  
- **[Molecule](https://ansible.readthedocs.io/projects/molecule/)**: A testing framework for Ansible roles, enabling the creation of reproducible and isolated testing environments.
  
- **[Chocolatey](https://github.com/chocolatey/choco)**: A package manager for Windows that simplifies the installation and management of software.
  
- **[Boxstarter](https://github.com/chocolatey/boxstarter)**: Enhances Chocolatey by providing repeatable, resilient Windows environment installations, including automatic reboots and configuration.
  
- **[Packer](https://developer.hashicorp.com/packer)**: A tool for creating identical machine images for multiple platforms from a single source configuration.
  
- **[Terraform](https://developer.hashicorp.com/terraform)**: An infrastructure as code (IaC) tool that allows you to build, change, and version infrastructure safely and efficiently.
  
- **[OpenTofu](https://opentofu.org/)**: An open-source alternative to Terraform, providing similar infrastructure provisioning capabilities.
  
- **[Apache Guacamole](https://guacamole.apache.org/doc/gug/)**: A clientless remote desktop gateway supporting standard protocols like VNC, RDP, and SSH, accessible through a web browser.
  
- **[Guacamole Terraform Provider](https://registry.terraform.io/providers/techBeck03/guacamole/latest/docs)**: Integrates Apache Guacamole with Terraform, enabling automated provisioning of remote desktop environments.
  
- **[pyguacamole](https://github.com/mohabusama/pyguacamole)**: A Python client library for interacting with the Guacamole protocol, facilitating automation and integration.
  
- **[guacapy](https://github.com/pschmitt/guacapy)**: A Python client for the Guacamole REST API, allowing for programmatic management of Guacamole resources.
  
- **[Puppeteer](https://github.com/puppeteer/puppeteer)**: A Node.js library providing a high-level API to control headless Chrome or Chromium browsers for automated testing and scraping.
  
- **[Playwright](https://github.com/microsoft/playwright)**: An end-to-end testing framework supporting multiple browsers, enabling reliable and fast browser automation.
  
- **[Docker OSX](https://github.com/sickcodes/Docker-OSX)**: Run a macOS virtual machine within Docker containers, useful for macOS-specific testing environments.
  
- **[Windows Downdate](https://github.com/SafeBreach-Labs/WindowsDowndate)**: A tool that manipulates Windows Update processes to create custom downgrades, exposing vulnerabilities that have been previously patched.
  
- **[stress-ng](https://github.com/ColinIanKing/stress-ng)**: A stress testing tool for evaluating system performance under load by exercising various subsystems.
  
- **[noVNC](https://github.com/novnc/noVNC)**: A web-based VNC client that allows remote desktop access directly through a browser without additional plugins.
  
- **[Fail2Ban](https://github.com/fail2ban/fail2ban)**: A daemon that monitors log files and bans IPs exhibiting malicious behavior, such as multiple failed login attempts.
  
- **[AWS SAM (Serverless Application Model)](https://github.com/aws/aws-sam-cli)**: A framework for building, testing, and deploying serverless applications on AWS.
  
- **[Serverless Framework](https://github.com/serverless/serverless)**: An open-source framework for building and deploying serverless applications across various cloud providers.
  
- **[Code Server](https://github.com/coder/code-server)**: Runs Visual Studio Code on a remote server, accessible through a web browser, enabling remote development environments.
  
- **[Lambda Powertools](https://github.com/aws-powertools/powertools-lambda-python)**: A Python library that simplifies the development of AWS Lambda functions by providing utilities for logging, metrics, and tracing.
  
- **[Undo WinRMConfig](https://github.com/DarwinJS/Undo-WinRMConfig)**: A utility to revert Windows Remote Management (WinRM) configurations, useful for cleaning up after provisioning Windows machine images with Packer.
  
- **[LocalStack](https://github.com/localstack/localstack)**: Provides a fully functional local AWS cloud stack, enabling testing and development of cloud applications without accessing real AWS services.
  
- **[Multi Juicer](https://github.com/juice-shop/multi-juicer)**: Manages multiple instances of Juice Shop, an intentionally vulnerable web application, to facilitate security training and CTF challenges.
  
- **[Greybox](https://github.com/cmu-sei/greybox)**: An internet simulation tool developed by CMU SEI, allowing the creation of realistic network environments for testing and training purposes.
  
- **[GHOSTS NPC Framework](https://cmu-sei.github.io/GHOSTS/)**: A framework for creating non-player characters (NPCs) in simulation environments, enhancing the realism and interactivity of cyber range scenarios.

## White Zone Tooling

Tools and frameworks for managing the white zone aspects of cyber ranges, including monitoring and competition management.

- **[Monitoror](https://github.com/monitoror/monitoror)**: A customizable monitoring dashboard that aggregates and displays various metrics and statuses from multiple sources in a single view.
  
- **[CTFd](https://github.com/CTFd/CTFd)**: An open-source platform for hosting Capture The Flag (CTF) competitions, featuring team management, scoring, and challenge integration.
  
- **[CTFd Plugins](https://github.com/CTFd/plugins)**: A collection of official and community-developed plugins that extend the functionality of the CTFd platform.
  
- **[Terraform AWS CTFd](https://github.com/1nval1dctf/terraform-aws-ctfd)**: A Terraform module for deploying the CTFd platform on AWS, automating the setup and scaling of CTF environments.

## CTF Content Creation

Tools and resources for creating engaging and challenging CTF content.

- **[Screenshot to Code](https://github.com/abi/screenshot-to-code)**: Utilizes machine learning to convert website screenshots into code (HTML, Tailwind, React, Vue), facilitating the rapid creation of CTF websites and challenges.
  
- **[Draw-a-UI](https://github.com/SawyerHood/draw-a-ui)**: Generates HTML code from hand-drawn UI mockups using large language models (LLMs), streamlining the design-to-development process.

## Intentionally Vulnerable Challenges

Platforms and environments designed with intentional vulnerabilities for training and assessment.

- **[AHHHZURE](https://github.com/gladstomych/AHHHZURE)**: An automated deployment script that sets up a vulnerable Azure cloud lab, allowing security practitioners to hone their cloud security skills.
  
- **[Damn Vulnerable Restaurant](https://github.com/theowni/Damn-Vulnerable-RESTaurant-API-Game)**: An intentionally vulnerable RESTful API game designed for developers, ethical hackers, and security engineers to practice and learn through exploitation.
  
- **[Simulator](https://github.com/controlplaneio/simulator)**: A Kubernetes-based security training platform that simulates various attack scenarios for hands-on learning.
  
- **[Damn Vulnerable Web Application (DVWA)](https://github.com/digininja/DVWA)**: An intentionally insecure web application used to practice and understand common web vulnerabilities.
  
- **[Game of Active Directory (GOAD)](https://github.com/Orange-Cyberdefense/GOAD)**: Simulates an Active Directory environment with intentional vulnerabilities, enabling security professionals to practice exploitation and defense techniques.
  
- **[XMGoat](https://github.com/XMCyber/XMGoat)**: Deployable Terraform modules for Azure that set up intentionally insecure cloud environments for penetration testing practice.
  
- **[AWSGoat](https://github.com/ine-labs/AWSGoat)**: Provides deliberately insecure AWS infrastructure setups to help users learn about cloud security by identifying and exploiting vulnerabilities.
  
- **[CloudGoat](https://github.com/RhinoSecurityLabs/cloudgoat)**: Offers intentionally insecure AWS environments designed for security practitioners to practice cloud penetration testing.
  
- **[Cloudfoxable](https://github.com/BishopFox/cloudfoxable)**: Creates vulnerable-by-design AWS penetration testing playgrounds, allowing for realistic cloud security assessments.
  
- **[CNAPPgoat](https://github.com/tenable/cnappgoat)**: Sets up intentionally insecure cloud-native application protection platform (CNAPP) infrastructures for security training and testing.
  
- **[CI/CD Goat](https://github.com/cider-security-research/cicd-goat)**: Establishes an intentionally insecure CI/CD environment to help users understand and mitigate pipeline vulnerabilities.
  
- **[Juice Shop](https://github.com/juice-shop/juice-shop)**: An intentionally vulnerable web application designed to be a security training ground and a platform for CTF challenges.

## Pre-built Cyber Range Environments and Content

Ready-to-deploy environments and applications designed to simulate real-world systems, vulnerabilities, and attack vectors for training and assessment purposes.

- **[DetectionLab](https://github.com/clong/DetectionLab)** *(stale)*: Automates the creation of a comprehensive lab environment equipped with security tools and logging best practices for threat detection and analysis.
  
- **[BadBlood](https://github.com/davidprowe/BadBlood)**: Populates a Microsoft Active Directory domain with a complex structure and thousands of objects to simulate large enterprise environments for testing and training.
  
- **[Attack Range](https://github.com/splunk/attack_range)**: Enables the creation of vulnerable environments, either locally or in the cloud, to simulate attacks and collect data for analysis in Splunk.
  
- **[Vulnhub](https://github.com/vulhub/vulhub)**: Provides a collection of pre-built vulnerable environments using Docker-Compose, suitable for penetration testing practice and training.
  
- **[Facebook CTF](https://github.com/facebookarchive/fbctf)** *(stale)*: An archived platform for hosting Capture The Flag competitions, offering a range of features for challenge management and participant engagement.
  
- **[Awesome Mobile CTF](https://github.com/xtiankisutsa/awesome-mobile-CTF)**: A curated list of CTF challenges and resources focused on mobile application security.

## Learning Management Systems (LMS)

Platforms that facilitate the creation, management, and delivery of educational content and training programs within cyber ranges.

- **[Canvas](https://github.com/instructure/canvas-lms)**: A robust and flexible LMS used by educational institutions to deliver courses, track progress, and manage learning materials.
  
- **[Moodle](https://github.com/moodle/moodle)**: An open-source LMS that provides a customizable platform for creating online courses, assessments, and collaborative learning environments.
  
- **[edX Platform](https://github.com/openedx/edx-platform)**: An open-source platform developed by edX for delivering massive open online courses (MOOCs) and other educational content.

## Tools for LMS Content Creation

Tools that assist in creating and managing educational content for Learning Management Systems.

- **[Whisper](https://github.com/openai/whisper)**: An automatic speech recognition (ASR) system that generates transcripts from audio or video files, useful for creating subtitles and searchable content.
  
- **[stable-ts](https://github.com/jianfch/stable-ts)**: Generates high-precision transcripts for videos by aligning text with timestamps, enhancing the accessibility and usability of video content.
  
- **[VHS](https://github.com/charmbracelet/vhs)**: A tool for creating clean and high-quality recordings and GIFs of terminal sessions, useful for demonstrations and tutorials.
  
- **[yt-dlp](https://github.com/yt-dlp/yt-dlp)**: A command-line program to download videos from YouTube and other platforms, enabling offline access to educational video content.

## Educational Aides

Supplementary tools that enhance the learning and training experience within cyber ranges by providing additional functionalities and utilities.

- **[TrailShark](https://github.com/Aqua-Nautilus/TrailShark)**: Captures and visualizes AWS CloudTrail events within Wireshark, aiding in the analysis of cloud activity and security incidents.
  
- **[Kathara](https://github.com/KatharaFramework/Kathara)**: A lightweight, container-based network emulation system that allows the creation of complex network topologies for testing and training.
  
- **[containerlab](https://github.com/srl-labs/containerlab)**: Facilitates the creation and management of container-based networking labs, supporting scalable and reproducible network environments.
  
- **[EdgeShark](https://github.com/siemens/edgeshark)**: Integrates with Wireshark to inspect and analyze network traffic between containers, providing insights into inter-container communications.
  
- **[Arkime](https://github.com/arkime/arkime)**: An open-source, large-scale packet capturing, indexing, and database system for network traffic analysis and security monitoring.
  
- **[Web Check](https://github.com/Lissy93/web-check)**: An all-in-one Open Source Intelligence (OSINT) tool for analyzing websites, assisting in reconnaissance and information gathering tasks.
  
- **[Insomnia](https://github.com/Kong/insomnia)**: A powerful open-source tool for testing and debugging web APIs, supporting REST, GraphQL, and other protocols.
  
- **[Evil noVPC](https://github.com/JoelGMSec/EvilnoVNC)**: A phishing framework that intercepts traffic to legitimate websites, enabling the creation of deceptive environments for training purposes.
  
- **[BOAST](https://github.com/ciphermarco/BOAST)**: An open-source out-of-band testing tool that integrates with the ZAP web application scanner to enhance security assessments.

## Security Operations Tools

Tools designed to assist in incident response, data analysis, and security investigations within cyber ranges.

- **[Iris Web](https://github.com/dfir-iris/iris-web)**: An open-source incident response platform that centralizes data collection, analysis, and reporting for security investigations.

## AI and Simulation Tools

Tools that leverage artificial intelligence for simulations, conversational interfaces, and managing machine learning models within cyber ranges.

- **[Open WebUI](https://github.com/open-webui/open-webui)**: An open-source user interface for interacting with Large Language Models (LLMs), similar to ChatGPT, facilitating conversational AI integrations.
  
- **[Tabby](https://github.com/TabbyML/tabby)**: An open-source text editor interface for interacting with and managing machine learning models, providing a user-friendly environment for AI-driven tasks.

