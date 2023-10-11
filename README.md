# Windows_Registry_Analysis
This repository provides a guide on how to perform Windows Registry analysis using FTK Imager, a powerful digital forensics tool designed for capturing and analyzing data from digital devices. In this guide, you will learn how to use FTK Imager to extract and analyze the Windows Registry, an essential component for digital forensics investigations.

Table of Contents
Introduction
Getting Started
Prerequisites
Installation
Using FTK Imager for Registry Analysis
Loading a Disk Image
Registry Extraction
Registry Analysis
Prerequisites
Before you begin, make sure you have the following prerequisites:

FTK Imager installed on your system.
A disk image or forensic image containing the Windows Registry data.
Installation
Download and install FTK Imager on your forensic workstation.
Using FTK Imager for Registry Analysis
Loading a Disk Image
Launch FTK Imager on your forensic workstation.

Click on "File" and select "Add Evidence Item."

Browse to the location of your disk image and select it.

Click "Finish" to load the disk image into FTK Imager.

Registry Extraction
In FTK Imager, locate the loaded disk image in the Evidence Tree.

Expand the disk image to reveal its partitions and file systems.

Right-click on the partition where the Windows Registry is located and select "Export Files."

Choose a destination folder for the extracted files and click "OK" to start the extraction process.

Registry Analysis
Once the registry files are extracted, you can analyze them using various tools, such as RegEdit, RegRipper, or other forensic analysis software.

FTK Imager also provides a basic viewer for registry files, which you can access by clicking on the "View Registry" button in the toolbar.

Use FTK Imager's built-in search and bookmarking features to navigate and highlight important registry keys and values.

Document your findings and save relevant information for your investigation.
