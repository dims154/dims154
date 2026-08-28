<div align="center">

<img src="./assets/profile-hero.svg" width="100%" alt="Muhammad Ilham Cyberpunk Profile">

👨‍💻 Muhammad Ilham

Information Systems Student • Backend Developer • System Enthusiast

<a href="https://github.com/dims154"><img src="https://img.shields.io/badge/GitHub-dims154-0D1117?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
<a href="https://wa.me/6287785567289"><img src="https://img.shields.io/badge/WhatsApp-Contact-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"></a>

</div>

🌌 About Me

I'm an Information Systems student with a strong interest in backend development, software architecture, automation, and building practical software systems.

I enjoy understanding what happens behind the interface — from business logic and databases to APIs, architecture, integrations, and automation.

My goal is not simply to write code.
I want to understand the system behind the code.

name: Muhammad Ilham
username: dims154
location: Jambi, Indonesia

role:
  - Information Systems Student
  - Backend Developer
  - System Enthusiast

focus:
  - Backend Development
  - System Design
  - Enterprise Architecture
  - Database Design
  - Automation
  - Data Analytics

⚙️ Tech Stack

<div align="center">

💻 Languages

<img src="https://skillicons.dev/icons?i=python,java,php,javascript" alt="Programming Languages">

⚙️ Backend

<img src="https://skillicons.dev/icons?i=laravel,nodejs" alt="Backend Technologies">

🗄️ Database

<img src="https://skillicons.dev/icons?i=mysql,sqlite" alt="Database Technologies">

🛠️ Tools

<img src="https://skillicons.dev/icons?i=git,github,vscode,postman" alt="Development Tools">

🌐 Web

<img src="https://skillicons.dev/icons?i=html,css" alt="Web Technologies">

</div>

📊 GitHub Statistics

<div align="center">

<img src="https://raw.githubusercontent.com/dims154/dims154/main/stats/github-stats.svg" width="100%" alt="GitHub Statistics">

<br>

<img src="https://raw.githubusercontent.com/dims154/dims154/main/stats/top-languages.svg" width="100%" alt="Top Languages">

<br>

<img src="https://raw.githubusercontent.com/dims154/dims154/main/stats/streak.svg" width="100%" alt="Contribution Streak">

</div>

<p align="center">
<sub>🔄 Automatically generated and updated with GitHub Actions</sub>
</p>

📈 Contribution Activity

<div align="center">

<img src="https://raw.githubusercontent.com/dims154/dims154/main/stats/contribution-activity.svg" width="100%" alt="Contribution Activity">

<br>

<sub>Last 31 days · Automatically generated with GitHub Actions</sub>

</div>

🎯 Current Focus

<table>
<tr>
<td width="50%" valign="top">

⚙️ Backend

API development

Business logic

Authentication & authorization

Database integration

System integrations

Backend architecture

</td>

<td width="50%" valign="top">

🏗️ Architecture

Modular systems

Maintainability

Scalability

Security

Reliability

Business-oriented design

</td>
</tr>

<tr>
<td width="50%" valign="top">

🤖 Automation

Bots

Workflows

GitHub Actions

Integrations

Scheduled automation

Developer tooling

</td>

<td width="50%" valign="top">

📊 Data

Database design

Data analytics

Reporting

Business intelligence

Structured data

</td>
</tr>
</table>

🚀 Featured Project

<table>
<tr>
<td width="100%">

🤖 BOT V2 — Enterprise WhatsApp Automation System

A modular backend system designed to handle WhatsApp-based business operations with structured commands, permissions, user management, and tenant isolation.

🧩 Core Architecture

                         ┌──────────────────────┐
                         │      WHATSAPP        │
                         └──────────┬───────────┘
                                    │
                                    ▼
                         ┌──────────────────────┐
                         │    COMMAND LAYER     │
                         │                      │
                         │ Command Registry     │
                         │ Command Loader       │
                         │ Command Executor     │
                         └──────────┬───────────┘
                                    │
                    ┌───────────────┼───────────────┐
                    ▼               ▼               ▼
             ┌────────────┐  ┌────────────┐  ┌────────────┐
             │   USER     │  │ PERMISSION │  │  TENANT    │
             │  RESOLVER  │  │  RESOLVER  │  │  ISOLATION │
             └──────┬─────┘  └──────┬─────┘  └──────┬─────┘
                    │               │               │
                    └───────────────┼───────────────┘
                                    ▼
                         ┌──────────────────────┐
                         │    BUSINESS LOGIC    │
                         └──────────┬───────────┘
                                    │
                                    ▼
                         ┌──────────────────────┐
                         │       DATABASE       │
                         └──────────────────────┘

⚙️ Key Components

Component

Purpose

🧩 Command Registry

Central command registration and discovery

📦 Command Loader

Loads available command definitions

⚡ Command Executor

Executes validated commands

👤 User Resolver

Resolves the active user context

🔐 Permission Resolver

Handles authorization and permission checks

🏢 Tenant Isolation

Separates data and operations between tenants

🧠 AI Pipeline

Processes structured AI-driven interactions

📊 Structured Output

Produces predictable machine-readable results

🛠️ Current Capabilities

User management

Permission management

Command-based architecture

Authentication & authorization

Tenant isolation

Structured output

Backend automation

Modular command execution

Automated testing

📌 Example Commands

/users
/user
/create

🎯 Engineering Focus

             MODULARITY
                  │
                  ▼
            MAINTAINABILITY
                  │
                  ▼
            AUTHORIZATION
                  │
                  ▼
            TENANT ISOLATION
                  │
                  ▼
              SCALABILITY

🛠️ Technology Focus

PHP · Laravel · MySQL · WhatsApp · REST API · GitHub Actions

</td>
</tr>
</table>

🏗️ Project Architecture

The project is being developed around a modular architecture rather than putting all business logic into a single application layer.

┌─────────────────────────────────────────────────────────────┐
│                      APPLICATION                            │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  ┌──────────────┐       ┌──────────────────────────────┐   │
│  │   COMMANDS   │ ────► │       COMMAND EXECUTOR       │   │
│  └──────────────┘       └──────────────┬───────────────┘   │
│                                        │                   │
│                    ┌───────────────────┼────────────────┐  │
│                    ▼                   ▼                ▼  │
│             ┌────────────┐     ┌────────────┐   ┌────────┐│
│             │    USER    │     │ PERMISSION │   │ TENANT ││
│             │  RESOLVER  │     │  RESOLVER  │   │ CONTEXT││
│             └────────────┘     └────────────┘   └────────┘│
│                    │                   │                │  │
│                    └───────────────────┼────────────────┘  │
│                                        ▼                   │
│                              ┌─────────────────┐            │
│                              │  BUSINESS LOGIC │            │
│                              └────────┬────────┘            │
│                                       │                     │
│                                       ▼                     │
│                              ┌─────────────────┐            │
│                              │    DATABASE     │            │
│                              └─────────────────┘            │
│                                                             │
└─────────────────────────────────────────────────────────────┘

🔬 What I'm Learning Through This Project

Designing modular backend architecture

Separating responsibilities between components

Building permission-aware systems

Implementing tenant isolation

Designing command-driven applications

Writing architecture-focused tests

Working with structured AI output

Building systems that can evolve without tightly coupling every component

🛠️ What I'm Building

🤖 Backend & Automation Systems

Building backend systems and automation workflows with a focus on practical architecture.

                         SYSTEM
                           │
                           ▼
                        ┌───────┐
                        │  API  │
                        └───┬───┘
                            │
              ┌─────────────┼─────────────┐
              ▼             ▼             ▼
        AUTHENTICATION    USERS       PERMISSIONS
              │             │             │
              └─────────────┼─────────────┘
                            ▼
                     BUSINESS LOGIC
                            │
                            ▼
                        DATABASE

Current areas:

API development

Command-based architecture

Authentication & authorization

Permission systems

User management

Structured output

System integrations

🏢 Enterprise Systems

Exploring enterprise-oriented software architecture through practical projects.

                       APPLICATION
                            │
                            ▼
                      BUSINESS LOGIC
                            │
              ┌─────────────┼─────────────┐
              ▼             ▼             ▼
           USERS         TENANTS       WORKFLOWS
              │             │             │
              ▼             ▼             ▼
        PERMISSIONS      ISOLATION     TRANSACTIONS
              │             │             │
              └─────────────┼─────────────┘
                            ▼
                         DATABASE

Focus areas:

Modular architecture

Multi-tenant systems

Tenant isolation

Authentication & authorization

Database design

Scalable backend architecture

System integration

🧠 Development Philosophy

              ┌───────────┐
              │   LEARN   │
              └─────┬─────┘
                    │
                    ▼
              ┌───────────┐
              │   BUILD   │
              └─────┬─────┘
                    │
                    ▼
              ┌───────────┐
              │   BREAK   │
              └─────┬─────┘
                    │
                    ▼
              ┌───────────┐
              │   DEBUG   │
              └─────┬─────┘
                    │
                    ▼
              ┌───────────┐
              │UNDERSTAND │
              └─────┬─────┘
                    │
                    ▼
              ┌───────────┐
              │  IMPROVE  │
              └─────┬─────┘
                    │
                    └──────────────► REPEAT

I don't aim to write perfect code from the beginning.

I aim to understand why it works, why it fails, and how it can be improved.

📚 Currently Learning

Technology / Concept

Focus

🐍 Python

Programming & automation

🐘 PHP / Laravel

Backend development

🟨 JavaScript / Node.js

Backend & integrations

🏗️ System Design

Scalable software architecture

🏢 Enterprise Architecture

Business-oriented system design

🗄️ Database Design

Data modeling & optimization

🤖 GitHub Actions

CI/CD & automation

🔥 Areas of Interest

<div align="center">

<table>
<tr>

<td width="25%" align="center">

⚙️ BACKEND

APIs
Business Logic
Databases
Integrations

</td>

<td width="25%" align="center">

🏢 ENTERPRISE

Architecture
Scalability
Modularity
Maintainability

</td>

<td width="25%" align="center">

🤖 AUTOMATION

Bots
Workflows
Integrations
CI/CD

</td>

<td width="25%" align="center">

📊 DATA

Analytics
Reporting
Business Intelligence
Data Systems

</td>

</tr>
</table>

</div>

🔄 Development Workflow

<div align="center">

IDEA → DESIGN → CODE → TEST → DEBUG → IMPROVE → DEPLOY → LEARN → REPEAT

</div>

🤖 GitHub Automation

This profile uses GitHub Actions to automatically generate and update profile statistics.

GitHub API
    │
    ▼
GitHub Actions
    │
    ├── Contributions
    ├── Repositories
    ├── Followers
    ├── Contribution Streak
    └── Top Languages
    │
    ▼
Generate SVG
    │
    ▼
stats/
 ├── github-stats.svg
 ├── top-languages.svg
 ├── streak.svg
 └── contribution-activity.svg
    │
    ▼
README.md

🧩 Profile Components

dims154/
│
├── README.md
│
├── assets/
│   └── profile-hero.svg
│
├── stats/
│   ├── github-stats.svg
│   ├── top-languages.svg
│   ├── streak.svg
│   └── contribution-activity.svg
│
└── .github/
    └── workflows/
        └── update-profile.yml

🌐 Connect With Me

<div align="center">

<a href="https://github.com/dims154">
<img src="https://img.shields.io/badge/GitHub-dims154-0D1117?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a>

<a href="https://wa.me/6287785567289">
<img src="https://img.shields.io/badge/WhatsApp-Contact-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=dims154&style=for-the-badge&color=58A6FF&label=PROFILE+VIEWS" alt="Profile Views">

</div>

<div align="center">

⚡ CODE • BUILD • LEARN • IMPROVE • REPEAT

"Every expert was once a beginner."

<br>

<sub>Thanks for visiting my profile 🚀</sub>

</div>
