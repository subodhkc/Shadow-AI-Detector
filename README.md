
# Shadow AI Detector™

> Enterprise-grade AI usage detection and monitoring platform

##  What This Does

Shadow AI Detector™ helps CISOs and compliance teams monitor and detect when employees are using AI tools (ChatGPT, Claude, etc.) with company data. We focus on metadata-only detection to maintain privacy while ensuring security.

##  Architecture

- **Backend:** Node.js with Express
- **Frontend:** React with TypeScript
- **Database:** PostgreSQL on IBM Cloud
- **Deployment:** Kubernetes on IBM Cloud
- **Integrations:** Microsoft Graph (Teams/Outlook), Slack

## Quick Start

### Prerequisites
- Node.js 18+
- Docker
- IBM Cloud CLI
- kubectl

### Development Setup
```bash
# Clone the repository
git clone <your-repo-url>
cd shadow-ai-detector

# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install

# Start development environment
docker-compose up -d
