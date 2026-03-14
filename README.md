# SDLC-Assignment-Harshvardhan
Smart-Attend SDLC Assignment
Project Overview
Smart-Attend is a mobile application designed to automate student
attendance in universities. The system uses geofencing technology to
detect when a student enters the classroom area and automatically marks
their attendance.
During development, a new requirement was introduced to integrate Face
ID biometric verification to prevent proxy attendance. This assignment
analyzes how different software development models handle such
requirement changes.
Waterfall vs Agile
The Waterfall model follows a linear sequence of phases and struggles
when requirements change mid-development. Adding biometric verification
late in the project would require redesigning architecture, updating the
database, modifying the user interface, and repeating testing.
Agile methodology, particularly the Scrum framework, allows the
project to adapt to new requirements easily through short development
cycles called sprints.
Sprint Plan
Sprint 1 (MVP)
Focus on building the core system: - User login and authentication -
Basic mobile UI - Geofencing attendance detection - Attendance history
view
Sprint 2
Add enhanced functionality: - Face ID enrollment - Face ID verification
when entering classroom - Improved reporting dashboard - Security
enhancements
CI/CD Implementation
Continuous Integration and Continuous Deployment help automate the
software delivery process.
Continuous Integration (CI) - Developers push code to the
repository - Automated builds and tests run immediately - Bugs are
detected early
Continuous Deployment (CD) - Successfully tested code is
automatically deployed - Students receive updates faster - Smaller
updates reduce deployment risk
Using CI/CD ensures the Smart-Attend app can be updated quickly and
reliably as new features such as biometric verification are added.
Repository Structure
    SDLC-Assignment-Harshvardhan
    │
    ├── analysis.pdf
    ├── Sprint_Backlog_Smart_Attend.xlsx
    └── README.md

This repository demonstrates how Agile development and DevOps practices
can be applied to modern software projects where requirements may evolve
during development.
