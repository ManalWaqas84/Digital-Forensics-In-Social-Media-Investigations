# Author: Manal Waqas (P2768537)

# Digital forensics in social media investigations 
This is my Final Year BSc Cyber Security (Hons) Project

This repository contains the resources, methodologies, and findings from a digital forensics project focused on social media investigations, specifically targeting cyberbullying and online harassment. The project utilizes forensic tools like Maltego Community Edition and FTK Imager to investigate real-world use cases, recover digital artifacts, and analyze evidence from publicly available social media accounts sourced from Kaggle datasets.

## Key Features
- **Use Cases**: Simulated cyberbullying scenarios using real social media accounts (Instagram and Twitter from Kaggle datasets) to demonstrate interactions, connections, and recovery of deleted data.
- **Forensic Tools**: Utilizes **Maltego CE** and **FTK Imager**, as well as additional tools like **Dumpit** for capturing memory.
- **Publicly Available Data**: Analysis performed on publicly available social media data to ensure compliance with ethical guidelines.
- **BYOK (Bring Your Own Key) Transforms**: Demonstrates how users can extend Maltego CE’s functionality by integrating third-party APIs.

I used Maltego from Kali Linux to analysis findings from various social media sites and FTK Imager from Exterro to conduct an investigation of recovering deleted social media in instances of cyberbullying or cybercrime

# Setup And Tools
**Setup**
- VMware Workstation for Windows
- UTM for MacOS
- Kali Linux Virtual Machine

**Tools**
- Maltego CE: Comes pre-installed in Kali Linux
- FTK Imager: Can be installed by Exterro
- Dumpit: Used for capturing live RAM memory

## Objectives
- Detect cyberbullying patterns on platforms like Facebook, Instagram, and Twitter.
- Recover deleted social media content using FTK Imager.
- Visualize relationships and connections between the attacker and the victim.

## Contents
- `Final Project/`: \.mtgx`: Main folder containing Maltego graph files
-  `Test Case 01.mtgl/`: Maltego graph file for test case 01.
-  `Test Case 03.mtgl/`: Maltego graph file for test case 03.
- `Test Case 03.mtgl/`: Maltego graph file for test case 04.
- `evidence_screenshots/`: Folder with screenshots

## License
This project is strictly for academic and educational purposes only.
