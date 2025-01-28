# Smart Agricultural Bird Pest Control: Utilizing Computer Vision for Pest Management

## Abstract
This project focuses on developing a smart bird detection and repellent system aimed at protecting agricultural fields from bird-related crop damage. By leveraging computer vision and sound-based repellent mechanisms, the system will detect birds and trigger distress calls or ultrasonic sounds to scare them away. The solution is designed to be cost-effective, environmentally friendly, and sustainable, reducing the reliance on harmful methods like chemicals or physical barriers. The project begins by collecting a large dataset of bird images using web scraping techniques, which will be used to train the detection model. The project will then evolve to involve the integration of IoT systems for real-time monitoring and automated responses using Raspberry Pi.

## Table of Contents
1. [Overview](#overview)
2. [Data Sources](#data-sources)
3. [Data Collection](#data-collection)
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
5. [Data Preprocessing](#data-preprocessing)
6. [Model Development](#model-development)
7. [Results and Evaluation](#results-and-evaluation)
8. [Conclusion](#conclusion)
9. [Next Steps](#next-steps)
10. [References](#references)

## Overview

### Background Information

Birds are an integral part of ecosystems worldwide, contributing to pollination, seed dispersal, and pest control. However, certain species can become pests, especially in agricultural settings. In Kenya and other regions of Africa, the invasion of specific bird species, such as the red-billed quelea, poses a significant threat to crop yields. The 2023 invasion of quelea birds in Kenya illustrates the severity of this issue, with farmers facing potential losses of up to 60 tonnes of grain. This problem is worsened by ongoing drought conditions in the Horn of Africa, which have driven these birds to invade cultivated fields in search of food.

The Food and Agricultural Organization (FAO) estimates that such crop losses amount to $50 million annually across sub-Saharan Africa, affecting food security and livelihoods. In response to this crisis, governments have often resorted to using toxic pesticides like fenthion for eradication. While these chemicals aim to protect crops, they also pose serious environmental and health risks, particularly to non-target wildlife and endangered species. The rapid reproductive capacity of birds, along with their significant daily grain consumption, highlights the urgency of finding sustainable and effective solutions to this persistent agricultural challenge.

### Problem Statement
Bird-related crop damage significantly impacts agricultural productivity and food security in Kenya and beyond. The reliance on harmful pesticides to control avian pests raises environmental and health concerns, necessitating a more sustainable approach. This project seeks to develop a smart bird detection and repellent system that leverages computer vision and sound-based mechanisms to provide an eco-friendly alternative to pesticides.

### Proposed Solution
The proposed solution involves creating an intelligent bird detection system that will identify pest birds and trigger distress calls or ultrasonic sounds to deter them from agricultural fields. By integrating computer vision technology with sound-based repellent mechanisms, this system aims to protect crops effectively while minimizing ecological disruption. The initial phase will involve collecting a comprehensive dataset of bird images through web scraping to train the detection model. Future developments will incorporate IoT systems for real-time monitoring and automated responses, empowering farmers to safeguard their crops sustainably.

### Objectives
- Develop a comprehensive dataset of bird images to train the detection model.
- Create a computer vision-based bird detection system that accurately identifies avian pests in agricultural settings.
- Integrate sound-based deterrents to provide a non-invasive repellent mechanism.
- Implement IoT solutions for real-time monitoring and automated responses to bird invasions.

The following sections will detail the data sources, methods, and results of this project, highlighting the significance of technology in modern pest control and its potential impact on agricultural sustainability.

## Data Sources

The project utilised data from various sources which was collected using various methods such as web scraping and the use of APIs.

- [African Bird Club](https://www.africanbirdclub.org/)
- [HuggingFace](https://huggingface.co/datasets/yashikota/birds-525-species-image-classification)


