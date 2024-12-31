# Project README
## Unified Site Health Dashboard & CI/CD Pipeline
### Overview
This project aims to create a comprehensive monitoring and CI/CD pipeline solution using Vue.js, Node.js, and Jenkins.

### Goals
1. Unified Dashboard: Display health metrics for multiple sites/apps, test reports, and other relevant data.
1. Jenkins CI/CD Server: Automate testing and deployment upon GitHub repository updates.
1. GitHub Integration: Link Jenkins server to GitHub repository for real-time updates.

### Tech Stack
- Frontend: Vue.js
- Backend: Node.js with Express
- CI/CD: Jenkins with Node.js scripting
- GitHub Integration: GitHub Webhooks

### Project Structure
- dashboard: Vue.js frontend application
- server: Node.js backend server with Express
- jenkins: Jenkinsfile and Node.js scripts for CI/CD pipeline
- github: GitHub Webhook configuration and event handling