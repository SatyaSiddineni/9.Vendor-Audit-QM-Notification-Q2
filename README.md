Vendor Audit QM Notification Q2


1. Project Overview 

            This project demonstrates the Vendor Audit process in SAP Quality Management (QM) using Quality Notification Type Q2.
            It is designed from an SAP QM Functional Consultant perspective and explains how organizations perform, track, and close vendor audits in SAP.

            The repository contains business explanation, process flow, configuration overview, test data, and documentation, making it easy for beginners and interviewers to understand.


How to Use This Project

            Read the Business Scenario  
            Review the Process Flow Diagram
            Check Sample Test Data 
            Refer to Step-by-Step SAP Transaction Document
            Understand Configuration Overview
            

  2. Business Scenario

            Organizations depend on vendors for raw materials and services.
            To ensure consistent quality, compliance, and risk control, vendors must be audited periodically.
            
            In this scenario:
            
                        A vendor is selected for audit
                        A Vendor Audit Notification (Q2) is created
                        Audit findings are recorded
                        Corrective actions are assigned and tracked
                        Vendor responses are verified
                        Audit is closed after successful follow-up
            
            SAP QM supports this entire lifecycle using Quality Notifications (Q2).


3. Vendor Audit Process Flow

            Vendor Selection / Vendor Identification
                    ↓
            Create QM Notification (Q2)
                    ↓
            Record Audit Findings
                    ↓
            Assign Tasks & Corrective Actions
                    ↓
            Vendor Submits Action Plan
                    ↓
            Verification & Follow-Up
                    ↓
            Close Notification


4. SAP Transactions Used

             T-Code	       Purpose
             QM01 	       Create Vendor Audit Notification (Q2)
             QM02 	       Change Notification 
             QM03 	       Display Notification 
             QM15 	       Notification List / List of Vendor Audit Notifications
             QM50 	       Task Monitoring


5. Master Data Involved

            Vendor Master
            Quality Info Record (Optional)
            Material Master (Optional)
            User / Employee Master


6. Configuration Overview (SPRO)

            Please do refer Configuration Steps.pdf.


7. Roles & Responsibilities
   
            Role	                        Responsibility
            SAP QM Functional Consultant	Process design & configuration
            Quality Engineer	            Conduct audit & record findings
            Vendor QA Team	            Submit corrective action plan
            Quality Manager	            Review & approve audit closure


8. Step-by-Step Transaction Execution

            Please do refer Step-by-Step Transaction Execution.pdf.


9.  Project Structure

             Vendor Audit QM Notification Q2/
             │   
             ├── README.md
             ├── Documents/
             │     ├── Configuration Steps.pdf     
             │     └── Step-by-Step Transaction Execution.pdf
             │
             ├── Flowchart/
             │     └── Vendor Audit Process Flow.png
             │
             └── Test_Data/
                   └── Vendor audit test data.xlsx



🙌 Author

Satyanarayana Siddineni SAP Functional Consultant
   
