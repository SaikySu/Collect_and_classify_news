# Collect news from VNExpress newspaper.
## Introduction
This project is built to automate the process of getting news data from [VNExpress](https://vnexpress.net/) using [Selenium](https://www.selenium.dev/) and storing the data as a Json file.

<p align="center">
  <img src="https://github.com/SaikySu/Yolov8-Vehicles-and-Human-face-Detection/blob/main/Example/Face_before.gif" width="400">
  <img src="https://github.com/SaikySu/Yolov8-Vehicles-and-Human-face-Detection/blob/main/Example/Face_after.gif" width="400"><br/>
  <img src="https://github.com/SaikySu/Yolov8-Vehicles-and-Human-face-Detection/blob/main/Example/Vehicles_before.gif" width="400">
  <img src="https://github.com/SaikySu/Yolov8-Vehicles-and-Human-face-Detection/blob/main/Example/Vehicles_after.gif" width="400"><br/>
  <i>Sample results</i>
</p>

## How to use
1. Download the source code in the repository.
2. Install all requirements libraries
3. Run this code with run all button

## Features
**Collect topics on demand**: This code will focus on collecting the topics in the homepage: News, politics, society,.... and save some articles in that topic.

**Collect article information**: The data will be saved in a Json file with information such as: Url, title, description, content and detailed data.

## Requirements
* Selenium
* Json
* Os

## Some notes:
* Because VNExpress is a newspaper written in Vietnamese, the data will also be stored in Vietnamese. For other websites, this model cannot be used.

* Some articles may have errors during saving.

* This code was run on 1/3/2025
