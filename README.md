# Airline_delays

# 603 Final Project

This repository contains all the necessary files for the 603 Final Project, which involves a detailed analysis of airline data, the development of models and visualizations, and a presentation of findings.

- kaggle source file: https://www.kaggle.com/datasets/bulter22/airline-data
## Project Files Description

- `airline.csv`: The dataset containing airline-related information used for analysis.
- `603_Final_project.ipynb`: A Jupyter Notebook that contains the code for data analysis and visualization. This file is intended to be run in Google Colab.
- `603_Final_PPT.pptx`: A PowerPoint presentation summarizing the project's objectives, methodology, results, and conclusions.
# The Big Picture of Airline Punctuality

## Introduction
Today, we'll explore how data from 2022 can enhance the flying experience for everyone. Our analysis focuses on understanding and addressing the challenges of airline punctuality, leveraging extensive data to improve operational efficiency and passenger experience.

## Project Overview
We've delved deep into the issues surrounding flight delays, utilizing Apache Spark and Hadoop for data analysis. Our goal is to comprehend the causes of delays and devise strategies to minimize them.

## Stakeholder Impact
Our study extends beyond mere data. We consider various aspects like Operational Efficiency, Passenger Experience, Regulatory Insights, Economic Benefits, and Future Planning. This analysis affects everyone from airlines seeking smoother operations to passengers desiring timely flights and authorities overseeing air travel.

## Real-World Impact
Our analysis leads to improvements in operational optimization, passenger experience, data-driven decision-making, policy and regulation, safety, and economic benefits. By addressing delays, we aim to make air travel more reliable and efficient.

## Data Overview
Our primary dataset, sourced from Kaggle, details airline operations. We supplemented this with mock-generated data to enrich our analysis. In total, we examined 1,524,000 rows across 29 columns, encompassing various flight aspects throughout 2022.

## Methodology
We meticulously cleaned and organized the data using Apache Spark and Hadoop. Our analysis aimed to identify patterns and insights that could help mitigate flight delays.

---

## Dataset Key Variables
- **ActualElapsedTime**: Total time from takeoff to landing.
- **AirTime**: Duration the plane was in the air.
- **ArrDelay**: Arrival delay compared to scheduled time.
- **ArrTime**: Actual landing time.
- **CRSArrTime**: Scheduled arrival time.
- **CRSDepTime**: Scheduled departure time.
- **CRSElapsedTime**: Expected flight duration.
- **CancellationCode**: Reason for flight cancellation.
- **Cancelled**: Indicator if the flight was canceled.
- **CarrierDelay**: Part of the delay caused by the airline.
- **DayOfWeek**: Day of the week (1-7).
- **DayOfMonth**: Date of the month the flight took place.
- **DepDelay**: Departure delay from scheduled time.
- **DepTime**: Time of takeoff.
- **Dest**: Airport code for the destination.
- **Distance**: Flight distance in miles.
- **Diverted**: Indicator if a flight was diverted.
- **FlightNum**: Flight number.
- **LateAircraftDelay**: Delays due to late arrival of the aircraft.
- **Month**: Month (1-12).
- **NASDelay**: Delays attributed to the National Aviation System.
- **Origin**: Departure airport code.
- **SecurityDelay**: Delays due to security issues.
- **TailNum**: Airplane's unique ID number.
- **TaxiIn**: Time spent taxiing to the gate after landing.
- **TaxiOut**: Time spent taxiing to the runway before takeoff.
- **UniqueCarrier**: Airline identifier.
- **WeatherDelay**: Delays due to weather.
- **Year**: Year of flight data recording.

## How to Run the Notebook

To run the `603_Final_project.ipynb`, follow these steps:

1. Upload the notebook to your Google Drive.
2. Navigate to the folder containing the notebook.
3. Open the notebook with Google Colab.
4. Run the cells in sequence by pressing the play button next to each cell or using the `Runtime` > `Run all` menu option.

## Data

The `airline.csv` file contains the data used for analysis in the project. Ensure this file is in the same directory as the Jupyter Notebook when running it in Google Colab.

## Presentation

The `603_Final_PPT.pptx` file is a PowerPoint presentation that can be viewed using Google Slides or Microsoft PowerPoint. It contains a summary of the project and its findings.



