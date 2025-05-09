# Performance Review App
A responsive budget allocation Power Apps mockup with a Power Automate integration and SharePoint synchronization for managing employee performance reviews.

## About This Repository
This Performance Review App is available for educational and portfolio purposes only, as it represents intellectual work that showcases functionality similar to what I developed during my professional work. This demonstration version does not contain any proprietary data or information and represents a reimplementation of a common business process tool, using only sample data for illustration purposes. For developmental inquiries regarding the interface, please contact edan@analyticintelligencesolutions.com.

# Technical Architecture
### User Role-Based Access
The app provides different views based on user roles. Managers can review all direct reports, assign performance ratings, and allocate compensation up to their budget cap, 110% of total potential employee pay. Employees can document their goals, provide supporting evidence, and complete self-assessments through a simplified interface focused only on their own performance data.

### Budget Management
Managers benefit from real-time budget calculation and visualization as they make compensation decisions. The system provides visual indicators when compensation allocations exceed available budget and automatically calculates pay amounts based on performance scores, helping managers stay within their allocated compensation limits.

### Data Synchronization
The app maintains bidirectional synchronization with SharePoint twice daily through Power Automate flows. This ensures preservation of document history and edit tracking while maintaining proper permission controls for sensitive compensation data across all systems.

### User Interface
The interface provides role-appropriate views with security controls to protect sensitive information. Its responsive design works seamlessly on both desktop and mobile devices, with intuitive editing features that provide immediate feedback on changes and their budget impacts.

## Key Features and Security
The app uses a model-driven approach to track performance data with a score-based rating system using numerical scoring (70-120) that maps to performance categories. Budget allocation logic ensures total compensation stays within departmental budget limits, while automatic SharePoint integration syncs data using Power Automate flows for data consistency. The security model creates security-specific versions of records to maintain data privacy between managers and employees.

## Process Flow
Users are identified via email address, which determines their role and access level. In the manager review process, managers view all direct reports in a consolidated table, assign performance ratings and specific scores, and see real-time budget impact of compensation decisions. Employees document performance goals and supporting evidence, complete self-assessments, and view their manager's final assessment and compensation decision. All changes automatically synchronize to SharePoint lists with proper permissions applied to ensure data security.

## Development and Legal
Clone the repository to your local machine using Git. No build process is required - simply serve the files locally using a basic HTTP server. Access the development version at localhost:8080 to start exploring the easy-to-use Budget Allocation interface. Feel free to explore how it works, use it as inspiration, or adapt elements for your own projects. As with any code sample, it's always best to understand the concepts and implement your own solution rather than using it directly in production. If you're inspired by this approach, I encourage you to develop your own unique solution with substantial modifications to both design and implementation.
