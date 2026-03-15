# GapHack

GapHack is a hackathon project that connects companies and cybersecurity specialists to discover and solve cybersecurity gaps together.

The platform enables companies to post security-related tasks or potential vulnerabilities, while cybersecurity users analyze them, submit findings, and build a public portfolio that showcases their practical work and skills.

## Overview

Many companies have cybersecurity gaps but cannot afford expensive security audits or full-scale bug bounty programs. At the same time, cybersecurity learners and junior specialists often struggle to find real-world tasks to practice on and lack a place to publicly demonstrate their abilities.

GapHack addresses both problems by creating a collaborative platform where companies and cybersecurity users can work together in a practical, community-driven environment.

## Problem

Organizations often face security issues such as:

- Unidentified vulnerabilities
- Misconfigurations
- Weak security practices
- Limited access to affordable cybersecurity expertise

Meanwhile, cybersecurity enthusiasts and learners often need:

- Real-world tasks to improve their skills
- Practical experience beyond theory
- A portfolio to demonstrate their abilities to employers or clients

## Solution

GapHack creates a community ecosystem where:

- Companies post cybersecurity challenges or possible vulnerabilities
- Cybersecurity users investigate tasks and submit findings
- Submitted work becomes part of the user’s public cybersecurity portfolio
- Companies recognize valuable contributions with badges and reputation
- A leaderboard motivates participation and rewards top contributors

## Key Features

- User and company registration
  - Separate onboarding for individuals and organizations

- Cybersecurity task posting
  - Companies can publish tasks, challenges, or suspected vulnerabilities

- Thread-style solution submissions
  - Users can submit findings in a discussion-style format

- Public user portfolios
  - Contributions and findings can be displayed as proof of practical experience

- Badge and reputation system
  - High-quality contributions can be rewarded and recognized

- Leaderboard
  - Encourages engagement and highlights top contributors

## Tech Stack

### Frontend
- Vue.js

### Backend
- FastAPI

## Project Goal

GapHack aims to create a collaborative cybersecurity ecosystem where companies can identify vulnerabilities more easily, and cybersecurity specialists can gain real-world experience, grow their reputation, and build a credible public portfolio.

## How It Works

1. A company registers on the platform
2. The company posts a cybersecurity-related task or vulnerability challenge
3. Cybersecurity users review the task and investigate possible issues
4. Users submit their findings through thread-style responses
5. The company reviews submissions and rewards valuable work with badges or recognition
6. The user’s accepted or notable contributions help strengthen their public profile and portfolio

## Local Development

### Backend

#### Requirements
- Python installed
- pip installed

#### Run locally

```bash
python.exe -m venv venv
pip install -r requirements.txt
uvicorn main:app --host 0.0.0.0 --port $PORT
