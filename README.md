HID SCT Self-Assessment Tool

A comprehensive web-based self-assessment tool for Highly Infectious Disease (HID) Specialized Care Teams (SCT) to evaluate their readiness and capabilities according to established minimum standards.
Overview

This digital tool helps HID SCTs complete their assessment, track progress, and generate reports for organizational use and coordination mechanisms. The application follows the "Minimum standards and recommendations for medical teams responding to highly infectious disease outbreaks" framework.
Features
📊 Assessment Modules

    Guiding Principles - Ethical and operational foundation standards

    Core Standards - Administrative and organizational requirements

    Clinical Standards - Patient care and treatment protocols

    Logistic Standards - Operational support and resource management

    WASH Standards - Water, sanitation, and hygiene requirements

🔄 Progress Tracking

    Real-time progress indicators for each section

    Visual progress bars and completion percentages

    Sidebar overview showing current status across all sections

    Weighted scoring system reflecting section importance

💾 Data Management

    Auto-save functionality - All changes are automatically saved to browser storage

    Export to Excel - Generate comprehensive Excel reports with multiple sheets

    Export to JSON - Backup data in structured JSON format

    Import from Excel - Load previously exported data back into the application

📋 Reporting Capabilities

    Team information and contact details

    Section-by-section assessment results

    Evidence, gaps, and action plans

    Mentor comments and observations

    Summary and action plan with timelines

Quick Start
Using the Application

    Open the deepseek_html_20250924_40a916.html file in any modern web browser

    Navigate through sections using the left sidebar

    Complete assessments by selecting scores and providing evidence/gaps/actions

    Review progress in the right sidebar overview

    Export your completed assessment using the action buttons

Data Persistence

    All data is automatically saved to your browser's local storage

    No server required - works completely offline

    Data remains available between browser sessions on the same device

Export Features
Excel Export Includes:

    Team Information Sheet - Contact details and organizational info

    Progress Overview - Section weights, status, and completion percentages

    Assessment Data - Detailed scores, evidence, gaps, and actions

    Summary Sheet - Strengths, gaps, action plans, and next steps

JSON Export:

    Complete dataset in structured JSON format

    Suitable for backup or integration with other systems

Import Functionality
Supported Import Format:

    Excel files with the same structure as exported files

    Must contain the following sheets:

        Team Info

        Progress Overview (optional)

        HID SCT Assessment

        Summary

Import Process:

    Click the "Import Excel" button

    Select a previously exported Excel file

    Data will be automatically loaded and forms populated

    Progress indicators will update to reflect imported data

Technical Details
Built With:

    HTML5 - Structure and layout

    CSS3 - Styling with Bootstrap 5 framework

    JavaScript - Application logic and interactivity

    SheetJS (xlsx) - Excel import/export functionality

    Bootstrap 5 - Responsive UI components

    Font Awesome - Icons and visual elements

Browser Compatibility:

    Chrome 60+

    Firefox 55+

    Safari 12+

    Edge 79+

Storage:

    Uses browser's LocalStorage API

    No data is sent to external servers

    All data remains on the user's device

Assessment Scoring System
Rating Scale:

    0 - Not started - No work initiated

    1 - Initial - Basic planning stages

    2 - In progress - Implementation underway

    3 - Completed - Fully implemented and operational

    N/A - Not applicable to this team

Section Weights:

    Guiding Principles: 2%

    Core Standards: 18%

    Clinical Standards: 20%

    Logistic Standards: 10%

    WASH Standards: 10%

Usage Guidelines
For Assessment Teams:

    Complete organizational details first

    Work through each section systematically

    Provide specific evidence for each standard

    Document gaps and required actions clearly

    Use mentor comments for external feedback

For Mentors/Coordinators:

    Review completed assessments in Excel format

    Provide feedback using the comments sections

    Use the summary section for overall recommendations

    Track progress across multiple teams using exported data

File Structure
text

HID_SCT_Assessment/
├── deepseek_html_20250924_40a916.html  # Main application file
├── exported_files/                      # Generated export files
│   ├── HID_SCT_Assessment_YYYY-MM-DD.xlsx
│   └── HID_SCT_Assessment_YYYY-MM-DD.json
└── imports/                             # Files for import
    └── previously_exported_assessment.xlsx

Troubleshooting
Common Issues:

Data not saving:

    Check if browser supports LocalStorage

    Ensure cookies are enabled

    Try using a different browser

Import not working:

    Verify Excel file matches export format

    Check file is not corrupted or password protected

    Ensure all required sheets are present

Layout issues:

    Use a modern, updated browser

    Check browser zoom level (should be 100%)

    Ensure screen resolution is adequate

Support:

For technical issues or questions about the assessment standards, consult your organization's EMT coordination mechanism or the relevant technical guidance documents.
Version Information

    Current Version: 1.0/2025

    Last Updated: September 2024

    Compatibility: EMT Minimum Standards for HID SCT

License & Usage

This tool is designed for use by authorized medical teams and coordination mechanisms. The assessment standards are based on established international guidelines for emergency medical teams.

For more information about HID SCT standards and deployment guidelines, consult the relevant WHO and EMT coordination mechanism documents.
