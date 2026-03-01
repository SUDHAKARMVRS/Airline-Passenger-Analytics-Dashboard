# ✈️ Airline Passenger Analytics Dashboard
## 📊 Project Overview

The Airline Passenger Analytics Dashboard is an interactive Power BI report designed to analyze airline passenger data, flight performance, and geographic distribution.

This dashboard provides insights into:

Total passenger count

Gender distribution

Flight status analysis (On Time, Delayed, Cancelled)

Continent & country-level analysis

Time-based trends (Year, Month, Quarter)

## 📁 File Included

Airline.pbix – Main Power BI dashboard file

## 🗂 Dataset Information

### Table Name:
Airline Dataset Updated

### Total Records: 98,619 rows
### Total Columns: 15

### Key Columns:

Passenger ID

First Name

Last Name

Gender

Age

Nationality

Airport Name

Country Name

Airport Continent

Departure Date

Arrival Airport

Pilot Name

Flight Status

## 📈 Key Features Implemented
### 1️⃣ KPI Cards

Total Passengers

Male Count ♂

Female Count ♀

On Time Flights

Delayed Flights

Cancelled Flights

### 2️⃣ Gender Analysis

Male vs Female distribution

Icon-based gender indicators

### 3️⃣ Flight Status Analysis

On Time performance

Delay percentage

Cancellation trends

### 4️⃣ Time Intelligence (Professional Calendar Table)

Year

Quarter

Month

Day

Year-Month trend analysis

### 5️⃣ Geographic Insights

Continent-wise passenger distribution

Country-wise flight analysis

### 🛠 DAX Measures Used

Examples:

Total Passengers = COUNTROWS('Airline Dataset Updated')

Male Passengers = 
CALCULATE(
    COUNTROWS('Airline Dataset Updated'),
    'Airline Dataset Updated'[Gender] = "Male"
)

Delayed Flights = 
CALCULATE(
    COUNTROWS('Airline Dataset Updated'),
    'Airline Dataset Updated'[Flight Status] = "Delayed"
)
### 🧠 Concepts Applied

Data Modeling

Calendar Table Creation

Relationships (One-to-Many)

Time Intelligence

Conditional Formatting

KPI Design

Dashboard UI Design

## 🚀 How to Use

Open Airline.pbix in Power BI Desktop

Refresh data (if needed)

Use slicers for:

Year

Month

Gender

Continent

Explore interactive visuals

## 🎯 Business Use Case

This dashboard helps airline management to:

Monitor flight performance

Understand passenger demographics

Identify delay patterns

Analyze regional traffic trends

Improve operational efficiency

## 🏆 Skills Demonstrated

Power BI Dashboard Development

Advanced DAX

Data Visualization

Time Intelligence

Business Insight Generation

## 📷 Screenshot
<img width="1157" height="668" alt="airline" src="https://github.com/user-attachments/assets/d76ff179-2c03-44b5-8a9e-c253a71fe212" />

## 🙋‍♂️ Author
Sudhakar M.
📫 [LinkedIn] 📧 sudhakar.mvrs@gmail.com
