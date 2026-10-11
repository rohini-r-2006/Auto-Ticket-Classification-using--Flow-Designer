Auto Ticket Classification using Flow Designer

Project Overview

This project automates IT ticket classification for a school IT helpdesk using ServiceNow Flow Designer. It identifies keywords in the ticket's Short Description and automatically assigns the appropriate Category and Subcategory. It also sends an email confirmation to the caller.

Problem Statement

Manually classifying IT support tickets is time-consuming and may lead to errors. This project automates the process to improve efficiency and reduce the workload of IT helpdesk staff.

Objectives

- Automatically classify IT support tickets.
- Reduce manual effort and human errors.
- Assign Category and Subcategory automatically.
- Send email confirmation to the caller.
- Provide an easy-to-maintain no-code solution.

Technologies Used

- ServiceNow Platform
- Flow Designer
- Custom Table – Incident WorkFlow
- If / Else If Conditions
- Update Record and Send Email Actions
- Update Set (XML)

Key Features

- Keyword-based ticket classification.
- Automatic ticket number generation.
- Dependent Category and Subcategory fields.
- Automated email notifications.
- Centralized ticket storage.
- Reusable configuration using Update Sets.

Ticket Classification

Issue| Category| Subcategory
Wi-Fi / Network| Network| Wi-Fi
Projector| Hardware| Projector
Forgot Password| Access| Forgot Password
Slow Computer| Performance| Slow Computer

Working Process

1. The user creates an IT support ticket.
2. The system checks the Short Description.
3. Flow Designer identifies matching keywords.
4. The appropriate Category and Subcategory are assigned.
5. A confirmation email is sent to the caller.
6. The helpdesk staff can review and manage the ticket.

Project Phases

1. Ideation Phase
2. Requirement Analysis
3. Project Design Phase
4. Project Planning
5. Project Development
6. Project Documentation
7. Project Demonstration

Testing and Results

- Mandatory field validation.
- Category and Subcategory dependency testing.
- Automatic Wi-Fi and Projector classification.
- Email notification testing.
- Ticket number generation testing.

The documented tests passed for the listed scenarios. Additional scenarios require further testing.

Advantages

- Saves time and reduces repetitive work.
- Improves classification consistency.
- Reduces manual errors.
- Provides automatic email acknowledgement.
- Easy to maintain and extend.

Limitations

- Classification depends on configured keywords.
- Currently supports four main issue types.
- Email requires a valid caller email address.
- Automatic assignment to groups or agents is not implemented.

Future Enhancements

- Automatic assignment to groups and agents.
- SLA tracking and dashboards.
- Additional ticket categories and keywords.
- Predictive intelligence for classification.

Team Details

Team ID: SWTID-2026-9175
Team Size: 5

Team Members

- Madhurasubashini C – Team Leader
- Muneeswari M
- Pappathy S
- Rohini R
- Santhiya K

Institution: Valluvar College of Science and Management (Autonomous), Karur
Department: Computer Science
Course: III BCA

Conclusion

This project demonstrates how ServiceNow Flow Designer can automate ticket classification and email notifications without custom programming. It improves helpdesk efficiency and provides a maintainable solution for school IT support.

GitHub Repository

"Auto Ticket Classification using Flow Designer" https://github.com/rohini-r-2006/Auto-Ticket-Classification-using--Flow-Designer.git
