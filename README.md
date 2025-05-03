# Author: Manal Waqas (P2768537)

# Digital forensics in social media investigations 
This is my Final Year BSc Cyber Security (Hons) Project

This repository contains the resources, methodologies, and findings from a digital forensics project focused on social media investigations, specifically targeting cyberbullying and online harassment. The project utilizes forensic tools like Maltego Community Edition and FTK Imager to investigate real-world use cases, recover digital artifacts, and analyze evidence from publicly available social media accounts sourced from Kaggle datasets.

## Key Features
- **Use Cases**: Simulated cyberbullying scenarios using real social media accounts (Instagram and Twitter from Kaggle datasets) to demonstrate interactions, connections, and recovery of deleted data.
- **Forensic Tools**: Utilizes **Maltego CE** and **FTK Imager**, as well as additional tools like **Dumpit** for capturing memory.
- **Publicly Available Data**: Analysis performed on publicly available social media data to ensure compliance with ethical guidelines.
- **BYOK (Bring Your Own Key) Transforms**: Demonstrates how users can extend Maltego CE’s functionality by integrating third-party APIs.

I utilized Maltego on Kali Linux to analyze findings across various social media platforms and employed FTK Imager by Exterro to investigate and recover deleted social media content in cases related to cyberbullying and cybercrime.

# Setup And Tools
**Setup**
- VMware Workstation for Windows
- UTM for MacOS
- Kali Linux Virtual Machine

UTM and Kali Linux for Mac OS is available to download from here [OneDrive 🔗](https://demontfortuniversity-my.sharepoint.com/:f:/g/personal/p2768537_my365_dmu_ac_uk/EkFH2_VSyvVLtDvV82h8K_IBUkU3Co1yPD3309VRok4o-A?e=b9egLZ) (Only accessible through a DMU email account)

**Tools**
- Maltego CE: Pre-installed with Kali Linux, providing an open-source intelligence (OSINT) and graphical link analysis tool for investigating relationships and connections across the internet.
- FTK Imager: Available for installation through Exterro, the official provider.
- Dumpit: Used for capturing live memory

## Objectives
- Detect cyberbullying patterns on platforms like Facebook, Instagram, and Twitter.
- Recover deleted social media content using FTK Imager.
- Visualize relationships and connections between the attacker and the victim.

## Contents
- `Final Project/`: \.mtgx`: Main folder containing Maltego graph files
-  `Test Case 01.mtgl/`: Maltego graph file for test case 01.
-  `Test Case 03.mtgl/`: Maltego graph file for test case 03.
-  `Test Case 04.mtgl/`: Maltego graph file for test case 04.
- `evidence_screenshots/`: Folder with screenshots

## License
This project is strictly for academic and educational purposes only.
