# Project: Automated Enterprise Onboarding (ServiceNow)

## Overview
This project automates the manual onboarding process for new employees. It ensures that IT accounts are created and hardware is provisioned automatically based on manager input, reducing human error and ticket resolution time.

## Key Technical Features
- **Dynamic Catalog Item:** Built a "New Hire Request" form with mandatory fields and data validation.
- **Client-Side Intelligence:** Implemented a **Catalog UI Policy** to dynamically show/hide the "Laptop Type" field based on user selection.
- **Backend Automation:** Engineered a **Flow Designer** workflow with conditional branching:
  - **Task 1:** Automated creation of Service Desk tasks for Active Directory setup.
  - **Task 2 (Conditional):** Automated hardware procurement tasks triggered only if a laptop is requested.

## Project Evidence
### 1. Dynamic User Interface
*The form automatically hides hardware options until the 'Need Laptop' box is checked.*
<img src="1_dynamic_form_hidden.png" width="400"> <img src="2_dynamic_form_visible.png" width="400">

### 2. Automation Logic (Flow Designer)
*Visualizing the 'If/Then' logic that powers the task creation.*
<img src="3_flow_designer_logic1.png" width="800">

### 3. Execution Success
*Evidence of a successful system run with a 'Complete' status.*
<img src="6.png" width="800">
