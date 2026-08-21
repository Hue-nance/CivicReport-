
CivicReport
CivicReport is a civic issue reporting platform built for Nigerian communities. It gives citizens a simple way to report local issues — bad roads, waste dumps, water leaks, broken streetlights, and more — and track their status until resolved.
The Problem
Community issues in Nigeria often go unreported because there is no easy, centralized channel to flag them or follow up on their progress. Complaints get lost in word-of-mouth or informal channels, and there's no way for residents to see whether anything is actually being done.
Features
Authentication — users sign up and log in with email and password
Report Submission — submit an issue with a category (Road, Waste, Water, Electricity, Security, Other), description, photo, and location
Status Tracking — every report moves through Submitted → In Review → Resolved
View Reports — browse all community reports, filterable by category and status
My Reports — view the status of reports you personally submitted
Admin Panel — an authorized admin account can update the status of any report
Tech Stack
Frontend: React
Authentication & Database: Firebase (Authentication, Firestore)
Photo Storage: Cloudinary
Hosting: Rocket (deployed)
How It Works
A user signs up or logs in
They submit a report: choosing a category, writing a description, attaching a photo, and sharing their location
The report appears in the public reports list with a "Submitted" status
An admin reviews reports and updates their status as work progresses
Users can check their own submissions and current status anytime under "My Reports"
Live Demo
Live app link
Project Context
CivicReport was built as a capstone project for the 3MTT NextGen Programme, based on Project Brief SD-12: Civic Reporting App.