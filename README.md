# Clod

# Cold Email Generator

This tool automatically creates personalized cold emails tailored to specific job descriptions using **GROQ**, **Llama 3.1**, and **Chroma DB**.

## Overview

The Cold Email Generator is designed to help job seekers craft effective, customized cold emails to improve outreach success. By inputting a link to a company's job description (JD), the generator retrieves relevant data and leverages natural language processing (NLP) to draft a targeted email that aligns with the company’s requirements.

## How It Works

1. **Input the JD Link**: Provide the URL to the company's job description.
2. **Job Description Parsing**: Using **GROQ**, the tool retrieves and structures key information from the job description.
3. **Relevance Matching with Chroma DB**: Essential JD components are matched against a custom database in **Chroma DB**, aligning the email’s content with the company’s requirements.
4. **Personalized Draft Generation**: Finally, **Llama 3.1** constructs a well-crafted, personalized email draft that is specific to the job's responsibilities, desired qualifications, and company culture.

## Features

- **Customizable**: Modify or fine-tune email parameters to match different tones or styles.
- **Automated Matching**: Ensures the email reflects the qualifications and keywords used in the JD for greater relevance.
- **Easy to Use**: Simply provide a link, and the generator does the rest.

## Setup and Usage

### Prerequisites

- **GROQ** and **Chroma DB** should be set up and configured for database access.
- **Llama 3.1** model should be downloaded and accessible for email generation.

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

