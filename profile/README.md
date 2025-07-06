# Online Judge Platform

A comprehensive online coding platform that provides a complete ecosystem for competitive programming, learning, and community engagement. Built with modern web technologies and designed for scalability.

## 🏗️ Architecture Overview

This platform consists of three interconnected repositories that work together to deliver a seamless coding experience:

### 🎯 Core Features

- **Problem Management**: Create, solve, and manage coding problems with automated test case evaluation
- **Real-time Code Execution**: Execute code in multiple programming languages with instant feedback
- **Competitive Programming**: Host time-bound coding contests with leaderboards and rankings
- **Community Features**: Blog system, social interactions, and user profiles
- **Learning Paths**: Structured learning journeys for different programming concepts
- **Admin Dashboard**: Comprehensive management tools for content and user administration

## 📦 Repository Structure

### 1. **Online_Judge_Frontend** - React Frontend Application

**Tech Stack**: React, Redux, Material-UI, Tailwind CSS, React Router

**Key Features**:
- Modern, responsive UI with dark/light theme support
- Real-time code editor with syntax highlighting
- Authentication with Google/Microsoft OAuth and email/password
- Redux state management for seamless user experience
- Protected routes and role-based access control
- Mobile-responsive design with custom hooks

**Core Components**:
- Problem listing and filtering with search functionality
- Interactive code editor with multiple language support
- Competition interface with live leaderboards
- Blog system with markdown support
- User profile management and social features
- Admin dashboard for content management

### 2. **Online_Judge** - Node.js Backend Server

**Tech Stack**: Node.js, Express, MongoDB, PostgreSQL, Redis, BullMQ

**Database Architecture**:
- **MongoDB**: Primary data store for problems, submissions, competitions, blogs, and community content
- **PostgreSQL (Neon)**: User authentication and identity management with strong consistency
- **Redis (Upstash)**: Caching layer for improved API performance
- **Hybrid User Model**: Combines PostgreSQL for auth with MongoDB for references

**Key Services**:
- JWT-based authentication with OAuth integration
- Code execution via external Piston API
- Background job processing with BullMQ
- File storage with Backblaze B2 and Cloudflare R2
- Email verification system with OTP
- Comprehensive caching strategy

**API Endpoints**:
- Authentication routes (register, login, OAuth)
- Problem management (CRUD operations)
- Code execution and submission
- Competition hosting and participation
- Community features (posts, likes, comments)
- Blog system with markdown support
- User profile and social interactions

### 3. **code-execution-server** - Dedicated Code Execution Service

**Purpose**: Isolated service for secure and scalable code execution

**Features**:
- Sandboxed code execution environment
- Support for multiple programming languages
- Security measures against malicious code
- Integration with the main platform via API
- Optimized for high-throughput execution

## 🚀 Key Capabilities

### Code Execution & Evaluation
- Multi-language support (C++, Python, JavaScript, Java, etc.)
- Automated test case evaluation
- Real-time compilation and execution
- Secure sandboxed environment
- Performance optimization with job queues

### Competition System
- Time-bound coding contests
- Real-time leaderboards
- User registration and participation tracking
- Problem assignment and scoring
- Submission history and analytics

### Community & Learning
- Blog creation and management with markdown support
- Social features (follow, like, comment)
- Learning paths with structured content
- User profiles and achievements
- Community engagement tools

### Admin & Management
- Comprehensive admin dashboard
- Problem creation and management
- User administration and role management
- Competition hosting and monitoring
- Analytics and reporting

## 🛠️ Technical Highlights

### Scalability
- Microservices architecture with dedicated code execution
- Redis caching for improved performance
- Background job processing for heavy operations
- Polyglot persistence strategy for optimal data storage

### Security
- JWT-based authentication
- OAuth integration (Google, Microsoft)
- Email verification system
- Role-based access control
- Secure code execution sandboxing

### Performance
- Redis caching layer
- Optimized database queries
- Background job processing
- CDN integration for static assets
- Efficient file storage with multiple providers

### Developer Experience
- Comprehensive API documentation
- Modular codebase structure
- Type-safe development
- Automated testing capabilities
- Easy deployment with Docker support

## 🎯 Use Cases

- **Educational Institutions**: Host coding competitions and track student progress
- **Tech Companies**: Technical hiring and skill assessment
- **Coding Bootcamps**: Practice platform for students
- **Individual Learners**: Self-paced programming practice
- **Competitive Programming**: Host contests and tournaments

## 🔧 Getting Started

Each repository contains detailed setup instructions and documentation for local development, deployment, and contribution guidelines.

---

*Built with modern web technologies and designed for the next generation of programmers.*
## Hi there 👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
