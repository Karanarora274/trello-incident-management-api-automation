# Trello Incident Workflow API Automation

## Workflow Board

![Workflow Board](screenshots/trelloboard.png)

## Project Overview
This project simulates a real-world incident management workflow using the Trello REST API and Postman automation.

The workflow models operational incident lifecycle stages commonly used in SaaS support and technical operations environments:

Open Incidents → Investigating → Resolved → Closed

The project demonstrates API testing, workflow automation, request chaining, dynamic variables, negative testing, and CRUD operations.

---

## Workflow Architecture

Incident Creation
→
Incident Retrieval
→
Workflow State Updates
→
Incident Detail Updates
→
Incident Cleanup

---

## Features

- Dynamic incident generation
- Automated card ID capture
- Incident lifecycle workflow automation
- CRUD API operations
- Collection Runner automation
- Negative API testing
- Reusable environment variables
- Request chaining using Postman scripts

---

## Tech Stack

- Postman
- Trello REST API
- JavaScript (Postman Scripts)
- GitHub

---

## API Operations Covered

### Incident Creation
- Create Incident

### Incident Retrieval
- Get All Open Incidents
- Get Incident By ID

### Incident Workflow Updates
- Move Incident To Investigating
- Move Incident To Resolved
- Move Incident To Closed
- Update Incident Details

### Incident Cleanup
- Delete Incident

### Negative Testing
- Invalid API Token
- Invalid Card ID
- Create Incident Without Name

---

## Automation Features

- Dynamic incident generation using Pre-request Scripts
- Automatic card ID storage using Post-response Scripts
- Environment variable management
- Collection Runner workflow execution

---

## Screenshots

(Add screenshots here)

---

## How To Run

1. Import Postman collection
2. Import environment file
3. Add Trello API credentials
4. Run collection using Collection Runner

---

## Future Improvements

- Newman CLI integration
- HTML reporting
- GitHub Actions CI/CD pipeline
- REST Assured implementation
- Slack/Webhook integrations
