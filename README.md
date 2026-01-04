Vendor Audit QM Notification Q2

1. Project Overview 

            This project demonstrates how an SAP QM Functional Consultant designs and implements a Vendor Audit management process using Quality Notifications (Type Q2).
      
            The project explains:
            
                  Business Scenario & Process Flow
                  Configuration (SPRO)
                  Master Data Involvement
                  Step-by-Step Transaction Execution
                  Test Data


  2. Business Scenario

            A manufacturing company sources critical materials from multiple vendors.
      
            To maintain product quality and reduce production risks, the company conducts periodic vendor audits to evaluate:
            
                  Quality management processes
                  Documentation and compliance
                  Calibration and inspection practices
                  Corrective and preventive action effectiveness
            
            During the audit, any non-conformities or observations identified at the vendor location must be recorded, tracked, and resolved.
            
            SAP QM supports this requirement through Quality Notifications (Q2), which act as a central audit record.


4. High-Level Process Flow

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


5. Configuration Overview (SPRO)

            Please do refer Configuration Steps.pdf.


6. Master Data Involved

            Master Data	                                  Purpose
            Vendor (LFA1)	                            Supplier to be audited
            Material Master (optional)	                If audit relates to specific items
            Quality Info Record (optional)	          To link vendor-material controls
            User/Employee Master	                      Task assignment


7. Step-by-Step Transaction Execution

            Please do refer Step-by-Step Transaction Execution.pdf.


8. SAP Transaction Codes Used

             T-Code	       Purpose
             QM01 	       Create Vendor Audit Notification 
             QM02 	       Change Notification 
             QM03 	       Display Notification 
             QM15 	       Notification List 
             QM50 	       Task Monitoring


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
   
