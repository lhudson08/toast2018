# Introduction To Nanopore Sequencing - TOAST2018
Prac material and presentations from The Omics Analysis Sydney Tutorials (TOAST) 2018 workshop 19th-20th of March 2018, University of Technology Sydney.

TOAST2018 was a two days workshop focussing on nanopore sequencing and sequence analysis: a lab day with hands-on sequencing and a bioinformatics day with hands-on tutorial including basecalling, read assembly and error correction.

This github repo provides the presentations and talks of the workshop as well as all materials, data and the course virtual machine files that are needed to re-do the bioinformatics tutorial at home.

[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/AdvancedTwigTec.svg?style=social&label=Follow%20%40AdvancedTwigTec)](https://twitter.com/AdvancedTwigTec)

## Day 1

After training on "dead" flow cell participants were prvided with DNA from 3 organisms and were asked to prepare a library using the 1D ligation kit SQK-LSK108 and subsequently sequence it on a Minion flow cell FLO-MIN106.


### Presentations

Presentations given on Day1 can be found in day1/Presentations
* Tonia Russel (Ramaciotii Center for Genomics, UNSW, Sydney, NSW, Australia) 
* Benjamin Schwessinger (Australian National University, Canberra, Australia) 

Additionally, presentations *Introduction to MinION* and *Introduction to MinKNOW* can also be found in that directory.

### Handouts
Handouts of Day1 include the Oxford Nanopore library preparation manual for SQK-LSK108 and the Flow Cell wash kit as well as a short prac manual.


## Day 2
The Bioinformatics practical of day 1 included the analysis of sequencing data from day1 as well as analysis and assembly of pre-compiled data including:
* base calling with albacore
* Ploting using nanoplot
* extraction of reads using poretools and identification of the organisms sequenced on day1
* assembly with minimap2 & miniasm
* consensus building with Racon
* comparison to reference using mummer

### Material
The following Day2 presentations can be found in directory /day2/presentations:
* Introduction to Nanopore Sequencing
* Introduction to Genome Assembly
* Error correction, consensus & polishing

The step-by-step handout for the bioinformatics tutorial can be found in the directory /day2/handouts.

# Bioinformatics tutorials

## Virtual machine

The Virtual machine file TOAST2018.zip can be found at https://drive.google.com/file/d/1FMEGsI7lB1hvA8QO5SEmtLrG47sRsIdS/view?usp=sharing

MD5 sum: 8ed9ac62569827b699c2b6dac178e28c

### Using the TOAST2018 VirtualBox 

1. Download and install VirtualBox (https://www.virtualbox.org/wiki/Downloads). 
2. Download and unpack the TOAST2018.zip file
3. In VirtualBox go to Machine->Add and choose the Virtual Machine file TOAST2018.vbox from the unpacked directory TOAST2018
4. Double-click the TOAST2018 VM on the left side of the VirtualBox GUI.

Detailed instructions can also be found in the presentation "Introduction to Nanopore Sequencing" in the day2 folder and in the "Introduction to command-line" section below.

#### Trouble shooting

##### USB2 error
If the VM does not start you might have to de-activate USB2 support:
1. Right-click on the TOAST2018 VM in the VirtualBox GUI (left menu)
2. Uncheck the "Enable USB support" check box (Windows: Settings->USB; MacOSX Settings->Ports->USB)
3. Save and close 

##### Virtualisation
For some Windows versions Virtualisation will have to be enabled in the BIOS.



## Pre-compiled data

The pre-compiled data is included in the virtual machine but can also be found at https://drive.google.com/file/d/1M1gdwoJUZJ4uOsk0Jm3Z1GvGMfc_aIYe/view?usp=sharing

## Day1 Sequencing data

Sequencing data of two of the groups can be found at https://drive.google.com/drive/folders/1LE27O3ljP2Xwc-lb2juPvkR63RbmXRoe?usp=sharing


 ## Software used 
 
 * NanoPlot v1.8.1
 * Mummer v3
 * poretools 0.6.0
 * Albacore v2.1.10
 * porechop v0.2.3
 * FastQC v.0.11.7
 * NanoFilt v2.0.1
 * minimap2 v2.9-r720
 * miniasm 
 * assembly-stats
 * nanopolish v0.9.0
 

# Introduction to Command-line
For course participants not yet familiar with command-line and linux I created a virtual machine and tutorial to get familiar with basic command-line usage.

## Virtual machine 
The CLI tutorial virtual machine, the tutorial and a video how to start the VM can be found in directory Commandline_tutorial at https://drive.google.com/drive/folders/1rgUZBfh9RShS7P0QDYZ-qGCUeykJWUeD?usp=sharing

VirtualBox installation instructions can be found there in directory VirtualBox_Install

 



