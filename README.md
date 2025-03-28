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
### 2. Balanced, Unbiased Training Data  
**Objective:**  
Ensure fair representation across topics and avoid biases that can distort AI behavior.  

**Acceptance Criteria:**  
- Evaluate balance in language, topics, and demographics  
- Avoid category dominance  
- Implement bias detection and mitigation measures  

**Assumptions:**  
- “Bias” and “balanced data” are defined in agreement with the client  
- Source data may contain inherent biases  

**Validation Plan:**  
- Analyze category distribution statistics  
- Use tools to detect stereotypes and imbalances  
- Conduct audits with diverse reviewers  

**Tasks:**  
- Define balance criteria  
- Add metadata during scraping  
- Measure diversity and frequency  
- Use bias detection tools  
- Document and balance the dataset  

---
### 3. Improve the Quality of Web-Scraped Data  
**Objective:**  
Ensure scraped data is clean, well-formatted, and free from noise such as ads or unrelated content.  

**Acceptance Criteria:**  
- Maintain <5% noise threshold  
- Ensure correct formatting for all entries  
- Remove noise without impacting content integrity  

**Assumptions:**  
- Scraped data includes ads and unrelated content  
- HTML source data is available  

**Validation Plan:**  
- Human review of raw vs. cleaned samples  
- Analyze text quality and readability  
- Use pattern filters in scraping logic  

**Tasks:**  
- Review scraping scripts  
- Implement cleanup procedures  
- Log errors or failed entries  
- Provide before/after samples for comparison  

---
### 4. Build a Balanced Dataset Generation Tool  
**Objective:**  
Create a tool that enables dataset generation with customizable balance and filtering parameters.  

**Acceptance Criteria:**  
- Tool allows selection by number, category, and balance  
- Resulting datasets must pass balance tests  

**Assumptions:**  
- Cleaned Q&A data is stored in a searchable format  
- Filtering rules can be user-defined  

**Validation Plan:**  
- Test with edge cases  
- Analyze category distribution pre- and post-generation  
- Collect developer feedback  

**Tasks:**  
- Design tool UI  
- Implement filtering and balancing logic  
- Integrate with categorized Q&A data  
- Validate across multiple scenarios  

---