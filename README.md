Project Title: AI-Powered Identity Verification and Fraud Detection for KYC Compliance
_______________________________________________________________________________________

Project Statement:
This project aims to develop an advanced AI-driven identity verification system tailored for BFSI (Banking, Financial Services, and Insurance) KYC and AML (Anti-Money Laundering) compliance. By leveraging technologies such as Graph Neural Networks (GNNs), Natural Language Processing (NLP), and Computer Vision, the solution will validate customer identities and verify the legitimacy of documents like AADHAR cards—particularly focusing on address verification. Utilizing platforms like Azure OpenAI, the system will reduce manual verification overhead while enhancing fraud detection accuracy and regulatory compliance.
_______________________________________________________________________________________

Outcomes:

•	Enhanced Identity Verification: Use of AI and deep learning to automate and improve identity checks for KYC/AML.

•	Fraudulent Address Detection: Robust mechanisms for verifying the authenticity of AADHAR addresses.

•	Improved Compliance: Automatic checks aligned with regulatory frameworks to prevent fraud and money laundering.

•	Cost Reduction: Minimization of manual effort and associated costs through automation and intelligent validation.

_______________________________________________________________________________________

Module 1: Data Collection and Preprocessing for Identity Verification
Collected real Aadhaar card images
Collected fake Aadhaar card images
Organized images into two separate folders:
real_aadhaar/ - for genuine Aadhaar cards
fake_aadhaar/ - for counterfeit Aadhaar cards
Removed noise from images using filtering techniques
Reduced image complexity for easier processing
Standardized image sizes and formats
Enhanced image quality for better feature extraction
Created labeled dataset for real vs fake classification
Prepared images for machine learning model training

work done by: Devansh, Dimple, Neeharika


Module 2: Model Development for Identity and Address Verification
Developed code to distinguish between real and fake Aadhaar cards
Used image processing techniques to analyze document authenticity
Implemented feature extraction from Aadhaar images
Created classification logic for real vs fake detection
Machine learning model learned patterns from real Aadhaar cards
If all details are present and clear → "Real Aadhaar"
If data is missing or incomplete → "Not Fake" (needs manual review)

work done by: Devansh, Sanuth, Vinutha


Module 3: AML and KYC Compliance System Integration
1. API Development
Developed Flask REST API for Aadhaar verification
Created endpoints for search and verification functionality
Implemented both GET and POST request handling
Built image delivery system for document retrieval
work done by: Sanuth, Dinesh

2. Integration System
Integrated Aadhaar database with API backend
Connected image storage with search functionality
Enabled seamless data flow between components
Built system for external platform integration
work done by: Dimple, Sanuth

3. Database
Extracted Aadhaar numbers from genuine Aadhaar card images
Processed and validated 12-digit Aadhaar number format
Stored extracted data in structured CSV format
Stored all genuine Aadhaar card images locally
Organized images with consistent naming convention
work done by: Devansh

4. Dashboard & Analytics
Developed stats endpoint for system monitoring
Created user-friendly web interface
Built system status reporting
Implemented search analytics
work done by: Vinutha, Muskan, Sridevi
