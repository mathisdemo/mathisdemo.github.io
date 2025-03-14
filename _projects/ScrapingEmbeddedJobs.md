---
layout: page
title: ScrapingEmbeddedJobs
description: 🤖 Automate job search for interns!
full_name: mpek29/ScrapingEmbeddedJobs
img: assets/img/projects/ScrapingEmbeddedJobs/main.png
importance: 1
git: https://github.com/mpek29/ScrapingEmbeddedJobs
github: https://github.com/mpek29/ScrapingEmbeddedJobs
category: Computer Science
subcategory: Software Development
---

This project is an automated job scraping tool designed to collect **Embedded Systems Engineering internships** from multiple job listing websites (Indeed, LinkedIn, StepStone, etc.). The goal is to **simplify the job search process** by extracting relevant job offers and storing them in a structured format for analysis and application.

## 🎯 Purpose

- 🤖 **Automation**: Eliminates the need for manual job searches.
- ⏱️ **Efficiency**: Gathers job offers in seconds.
- 📊 **Data Organization**: Stores job offers in CSV format for easy filtering.
- 🌍 **Multi-Country Support**: Focused on high-paying regions (**Germany, Netherlands, Denmark, Norway, Sweden, UK, Austria, Switzerland**).

## 🏗️ Project Architecture

```
ScrapingEmbeddedJobs/
│── data/                # Folder to store extracted job listings
│   ├── embedded_jobs.csv # Output file containing scraped job data
│
│── src/                 # Source code directory
│   ├── scraping_jobs.py  # Main script for job scraping
│   ├── config.py         # Configuration settings (URLs, search terms, etc.)
│   ├── parser.py         # Functions to extract and clean data
│
│── docs/                # Documentation and guides
│
│── requirements.txt      # Required Python dependencies
│── README.md             # Project documentation
│── .gitignore            # Ignore unnecessary files
```

## 📋 Requirements

- **Python**: Version 3.7 or higher
- **Required Libraries**:
  - `selenium` (for website interaction)
  - `beautifulsoup4` (for HTML parsing)
  - `pandas` (for structured data storage)
  - `chromedriver` (for Selenium automation, ensure it's installed and configured)

## 🚀 Installation Instructions


### 🛠️ Setup


1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/ScrapingEmbeddedJobs.git
   cd ScrapingEmbeddedJobs
   ```
2. **Install dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

3. **Ensure ChromeDriver is installed**:
   - Download ChromeDriver from [here](https://chromedriver.chromium.org/downloads)
   - Place it in the project directory or configure it in your system PATH

4. **Run the scraping script**:
   ```sh
   python src/scraping_jobs.py
   ```

5. **View the results**:
   - The job listings will be saved in `data/embedded_jobs.csv`
   - Open it with Excel, Google Sheets, or any CSV viewer

## 📂 Output Example

| Title | Company | Location | Link |
|------|---------|----------|------|
| Embedded Software Intern | Bosch | Germany | [Apply](https://example.com) |
| Hardware Engineer Intern | NXP | Netherlands | [Apply](https://example.com) |
| Embedded AI Engineer | Tesla | Sweden | [Apply](https://example.com) |

## 🤝 Contributions

If you'd like to contribute to the project, please follow these steps:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a pull request

We welcome any contributions to improve the automation and add support for more job boards! 🎉

