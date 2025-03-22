# Assignment 3 – SENG8091 Software Engineering Principles  
**Author:** Yash Patel  
**Student ID:** 9049539  

## Overview  
This project addresses key requirements for processing, validating, and improving web-scraped training data for AI development. The goal is to ensure high-quality, unbiased, and well-structured datasets that can be used effectively for modular and balanced training of machine learning models.

---
## Features & Requirements  

### 1. Separate and Categorize Training Questions from Answers  
**Objective:**  
Ensure clear separation between questions and answers with proper categorization to support modular AI training.  

**Acceptance Criteria:**  
- Store questions and answers in separate files or datasets  
- Attach one or more related groups to each question  
- Ensure structure is programmatically parseable and consistent  
- No textual overlap between questions and answers  

**Assumptions:**  
- Questions and responses exist within the current scraped data  
- Categories can be predefined or inferred from context  

**Validation Plan:**  
- Use scripts to verify no overlap between Q&A files  
- Conduct frequent inspections for accurate tagging  
- Review with development team for usability  

**Tasks:**  
- Analyze existing data structure  
- Design schemas for Q&A datasets  
- Implement categorization logic  
- Build and validate the separation pipeline  

---
