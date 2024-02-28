# 💸 Better Budget (Web App)

 - 🎯 **Purpose**: BetterBudget, is a project dedicated to empowering individuals and families to take control of their finances. I believe that with the right tools and insights, people can make more informed financial decisions, achieve their financial goals, and secure their financial future.

 - 👉 **Features**: *Personalized Expense Tracking - AI Assistant - Goal Setting/Tracking - Simplistic Usage*

 - 💻 **Tech Stack**:\
        - Frontend: *React.js/Vite/MantineUI*\
        - Backend: *Node.js/Express/PostgreSQL*\
        - Utilities: *Nodemon/dayjs/Postman/TailwindCSS/*

 - ⚡ **Quick Start**:\
        1. ```cd <desired location>```\
        2. ```git clone https://github.com/aqzx127/Better-Budget.git```\
        3. ```cd frontend | backend```\
        4. ```npm install```\
        5. ```npm run dev | npm start```

## 📚 Main Feature Todo's for a MVP:
    - User Registration/Account Creation (Feature 1) [X]

        - User Account Data Model (Auth0/JWT)
            - UserId [string, unique]
            - Email [string, unique] (Must Receive email conformation after registration!)
            - Name
            - Bio
            - Region

            // Creating an initial user record until they add more personalized info

        - Profile Setup/Page [X]
                - Settings []
                - Notifications []
                - Bio/About
        
        - Bank Linking [ ]
                - Plaid API [X] (Still need to save Plaid data to local postgreSQL DB)
                - Populate Balance [X], 
                - Populate/List Transactions []
                - Categorize Expenses []
---
    - User Expense Tracking (Feature 2) [ ]

        - Data Entry
           - Form Fields
           - Categorization
           - Date Picker
           - File Upload (Receipt/Photo)

           - User Statement/Transaction Data Model
                - Amount [int]
                - Date/Time [string] (dayJS autofill)
                - Category [string]
                - Payment Method [string]
                - Description/Notes [string]
                - Receipts/Images [file upload] (optional)
        
        - Data Privacy & Security
           - Privacy Policy
           - Data Encryption (Transit/Rest)
           - Secure Authentication
           - Ensure Legal Compliance [GDPR/CCPA] (Financial Data)

        - Analytics & Reporting
           - Dashboard: Shows recent expenses, total spendings by category, ect
           - Reports: Allow users to generate monthly detailed reports
           - Transaction History: Show users a list of all their previous transactions
---
    - AI Insights Chatbot via OpenAI API (Feature 3) [ ]
        - BudgetBuddy Main Features:
           - Analyze user income/expense and savings goals
           - Provide recommendations based on user data
           - Ensure security and privacy of user financial data while delivering insights
--- 
    - User Goal Setting and Tracking (Feature 4) [ ]

        - Set Specific Goals with target amounts/deadlines
        - System must track users progress toward goal in real-time
        - Users should receive feedback on goals to help them stay on track
        - System to adapt and mention goal recommendations based on user data

### ❓ Other Thoughts & Concerns
 - Framer Motion?
 - Banking API? (Plaid)
 - Payment of OpenAI API Services?
 - Hosting for Frontend/Backend & Database?
 - Ability to Scale?
 - Overall Theme/Design of UI?
 - State Management Library?
 - Testing? (Unit/Integration/End-to-End)
 - API Documentation?
 - Rate Limiting?
 - Helmet? (Security)
 - Possible External Security Risks?
 - Input Validation/Sanitize?
 - Error Logging/ App Monitoring?
 - Performance Optimizations?
 - Responsive Design?
 - Docker/Kubernetes?
 - CI/CD?
 - Accessibility?
 - Internationalization/Localization? (Currency, Language)