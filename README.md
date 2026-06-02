# Car-lease--AI
Car Lease Contract AI Negotiation is an AI-based system that helps customers and car dealers negotiate lease agreements automatically. 


Overview

The Car Contract Review – AI Negotiation Assistant is a Python-based project that automates the analysis of vehicle lease contracts. The system extracts important financial and contractual details from PDF lease agreements and presents them in a structured format to help users better understand contract terms and make informed negotiation decisions.

Features

- Extracts text from vehicle lease agreement PDFs.
- Identifies key lease parameters using Regular Expressions (Regex).
- Extracts:
  - Annual Percentage Rate (APR)
  - Monthly Payment
  - Lease Term
  - Down Payment
  - Residual Value
  - Mileage Allowance
  - Mileage Overage Fee
  - Early Termination Fee
  - Purchase Option Price
  - Insurance Requirements
  - Maintenance Responsibilities
  - Warranty Summary
  - Late Fee Policy
- Decodes Vehicle Identification Number (VIN) using the NHTSA Vehicle API.
- Retrieves vehicle details such as:
  - Make
  - Model
  - Manufacturing Year
- Stores extracted data in JSON format.
- Provides user-friendly explanations for lease contract terms.

Technologies Used

- Python
- PyPDF2
- Regular Expressions (Regex)
- JSON
- Requests Library
- NHTSA Vehicle API
- Google Colab

Project Workflow

1. Upload the vehicle lease agreement PDF.
2. Extract text from the PDF using PyPDF2.
3. Identify important lease fields using Regex patterns.
4. Decode VIN information through the NHTSA API.
5. Combine contract data and vehicle details.
6. Save the results in JSON format.
7. Generate explanations for extracted lease terms.

Sample Output

{
    "apr_percent": "5",
    "term_months": "36",
    "monthly_payment": "450",
    "down_payment": "3000",
    "residual_value": "18000"
}

Future Enhancements

- AI-based contract risk assessment.
- Lease offer comparison system.
- Contract summarization using Large Language Models (LLMs).
- Web application interface using Flask or Streamlit.
- Automatic negotiation recommendation engine.

Learning Outcomes

- PDF document processing
- Text extraction and pattern matching
- API integration
- JSON data handling
- Financial contract analysis
- Python automation

Author

B. Shalini
B.Tech Artificial Intelligence & Data Science
Velammal Institute of Technology
