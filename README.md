# RGPV Result SGPA Calculator Bot - UiPath RPA

This repository contains a **UiPath RPA (Robotic Process Automation)** project that automates the process of calculating the **SGPA (Semester Grade Point Average)** based on the result information from the **RGPV (Rajiv Gandhi Proudyogiki Vishwavidyalaya)** portal. The bot scrapes the results from the RGPV website, processes the marks, and calculates the SGPA for the student.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

The **RGPV Result SGPA Calculator Bot** automates the task of fetching student result data from the RGPV portal, parsing the relevant marks and grades, and calculating the SGPA. The bot then presents the calculated SGPA to the user and can also save the results in a specified format, such as **Excel** or **CSV**.

The bot works by performing the following steps:
1. **Navigates** to the RGPV result portal.
2. **Logs in** to the portal using the student's credentials (username, password).
3. **Scrapes** the result page for marks and grade points.
4. **Calculates** the SGPA based on the scraped data.
5. **Exports** the result and SGPA to an **Excel file** or **CSV** for record-keeping.

## Features

- **Automatic Result Scraping**: Scrapes student result data from the RGPV result portal.
- **SGPA Calculation**: Calculates SGPA based on scraped marks and grades.
- **Result Export**: Exports the SGPA and marks in an **Excel** or **CSV** format for easy reference.
- **Automated Login**: Logs into the RGPV portal automatically with the user's credentials.
- **Error Handling**: Includes basic error handling to manage login failures or scraping issues.

## Prerequisites

To run the **RGPV Result SGPA Calculator Bot**, ensure that you have the following:

1. **UiPath Studio**: The bot is built using **UiPath** RPA Studio. You can download it from the [UiPath website](https://www.uipath.com/start-trial).
   
2. **UiPath Robot**: Ensure that the UiPath Robot is installed to execute the automation tasks.

3. **RGPV Result Portal Access**: The bot requires access to the RGPV result portal, and the student should have their login credentials (username and password).

4. **Excel** (for Result Export): Install **Microsoft Excel** (or an alternative compatible spreadsheet software) if you want to export the SGPA and result data.

5. **Web Browser**: The bot works with **Google Chrome**, **Mozilla Firefox**, or **Microsoft Edge** for scraping the data from the portal.

## Installation

Follow the steps below to set up the bot on your machine:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/rgpv-sgpa-calculator-bot-uipath.git
   cd rgpv-sgpa-calculator-bot-uipath
