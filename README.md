# Project-4-

# Project-4: UMD Game Day Bites - Menus, Calories & Visual Guide

## Course & Team
- Course: INST326: Object-Oriented Programming for Information Science, Section 0201  
- Team: Terps  
- Team Members: Ahmad Jamshidi, Samir Uddin, Binh Do, Rish Kajale  
- Date: 10/14/25  

---

## Project Overview

### What We're Building
We have developed a complete, functional system designed to enhance the UMD football game day experience. Our application provides an interactive menu that displays food offerings at SECU Stadium, along with their nutritional information. The system allows users to:

- View food names, calories, macronutrients (protein, carbs, fat), and dietary tags (vegetarian, vegan, gluten-free).
- Filter menu items based on dietary preferences and calorie limits.
- Get suggestions for healthier alternatives.
- Persist menu data between sessions and generate exportable reports and summaries (TXT, CSV, JSON formats).
- Visualize nutrition data with bar charts for better interpretation of macronutrients.

### Problem Domain
UMD football game attendees face the following challenges:
- Nutritional information is often unavailable at food concessions.
- Individuals with health-conscious or restricted diets struggle to find suitable options.
- Patrons cannot view images or visual details of food before purchasing.

Goal: To create an interactive, informative, and visually engaging system that helps fans make informed and healthy food choices at UMD football games.

---

## System Features
- Complete Workflows: Users can browse, filter, and select menu items seamlessly.
- Data Persistence: Menu data can be saved and loaded between sessions (XML format).
- Import/Export: Support for exporting summaries and reports in multiple formats (TXT, CSV, JSON) for easy sharing and analysis.
- Interactive Visualization: Nutrition breakdowns are displayed using bar charts to help users better understand the nutritional value of their food choices.
- Professional Quality: The code follows industry best practices for maintainability, error handling, and quality assurance, with full test coverage.

---

## Team Roles
- Ahmad Jamshidi: Project Coordinator / Manager – Overall supervision, real-time support, and integration.
- Samir Uddin: Meeting Manager / Note Taker – Organizes meetings, tracks progress, and documents discussions.
- Binh Do: Coding / Technical Documentation – Implements and documents the code, ensuring all technical aspects are covered.
- Rish Kajale: Project Collaboration Support – Ensures smooth teamwork, assists with integration and testing.

Communication: The team communicates primarily via GroupMe chat and Zoom meetings, scheduled around weekends and lab times.

---

## Project Goal
Achieve an A+ (90-100%) by delivering a professional, functional, and visually interactive tool that enhances the UMD football game day experience.

---

## Setup & Installation

### Requirements
- Python version: 3.10+
- Required Libraries: `pathlib`, `xml.etree.ElementTree`, `matplotlib`
- Optional (recommended): Create a virtual environment

### Setup Instructions

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/UMD-GameDay-Bites.git
    cd UMD-GameDay-Bites
    ```

2. **(Optional) Create a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # Linux/macOS
    venv\Scripts\activate     # Windows
    ```

3. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the project:**
    ```bash
    python main.py
    ```

---

## Usage

To start using the application, run the following command:
```bash
python main.py
