# 👋 Hi, I'm Joydip Dutta

## 🚀 About Me  
I'm a passionate **Software Development Engineer** with over two years of experience building robust, scalable, and intelligent software solutions. My expertise lies in **full-stack development** with a strong focus on architecting and optimizing **AI-driven systems**. I thrive on solving complex technical challenges and leveraging **cutting-edge technologies** to deliver impactful products.

---

## 🛠️ Tech Stack & Expertise  

### AI/ML & Search  
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-121212?style=flat&logo=chainlink&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat&logo=elasticsearch&logoColor=white)

**Skills**: LLM APIs · RAG Systems · Vector Databases · Semantic Search

### Programming Languages  
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Golang](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

### Full Stack Development  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat&logo=graphql&logoColor=white)

### Databases & Caching  
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)

**Tools**: Mongoose · DynamoDB · Vector Stores

### Cloud & DevOps  
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoft-azure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

---

## 🧠 Featured Project: Enhanced RAG System  

### **[📂 Enhanced RAG System](https://github.com/joydipdutta9943/Enhanced-RAG-System)**  

A **production-ready, multi-modal Retrieval-Augmented Generation (RAG)** system that demonstrates enterprise-grade architecture combining **AI processing**, **real-time features**, and **scalable full-stack engineering**.

![RAG System Architecture](https://img.shields.io/badge/Status-Production_Ready-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)

---

### ✨ What It Does

This system transforms how users interact with documents by combining **intelligent document processing** with **AI-powered search capabilities**. It handles everything from uploading and parsing multi-format documents to providing semantic search results with AI-generated insights—all in real-time.

#### 🔹 Core Features

- **Multi-Modal Document Processing**: Automatically extracts, analyzes, and indexes content from PDFs, images, and text files with OCR support
- **AI-Powered Semantic Search**: Uses LangChain and vector embeddings to understand context and deliver highly relevant search results
- **Real-Time Collaboration**: WebSocket-powered live updates for document processing status and system notifications
- **Enterprise Security**: JWT authentication, role-based access control, and secure session management
- **Analytics Dashboard**: Comprehensive insights into usage patterns, search performance, and system metrics

---

### 🏗️ Technical Architecture

```
┌─────────────────┐      ┌──────────────────┐      ┌─────────────────┐
│   Next.js 15    │◄────►│   Node.js API    │◄────►│   MongoDB       │
│   Frontend      │      │   + WebSockets   │      │   + Prisma      │
└─────────────────┘      └──────────────────┘      └─────────────────┘
                                  │                          │
                                  │                          │
                         ┌────────▼──────────┐      ┌────────▼─────────┐
                         │  Redis Cache      │      │  Vector Store    │
                         └───────────────────┘      └──────────────────┘
                                  │
                         ┌────────▼──────────┐
                         │    LangChain      │
                         │  + Google Gemini  │
                         │  + Hugging Face   │
                         └───────────────────┘
```

---

### 💻 Tech Stack

#### **Frontend**
- **Next.js 15**: App Router with React Server Components for optimal performance
- **TypeScript**: Full type safety and enhanced developer experience
- **TailwindCSS + Shadcn UI**: Modern, responsive UI components

#### **Backend**
- **Node.js + Express**: RESTful API with WebSocket support for real-time features
- **Bun Runtime**: Ultra-fast JavaScript runtime (v1.2.16+)
- **Prisma ORM**: Type-safe database operations with MongoDB

#### **AI & Data Layer**
- **LangChain**: Orchestrates LLM workflows and RAG pipelines
- **Google Gemini API**: Advanced language understanding and generation
- **Hugging Face Models**: Open-source embeddings for semantic search
- **Vector Store**: Efficient similarity search and retrieval
- **Redis**: High-performance caching and session management

#### **DevOps**
- **Docker + Docker Compose**: Containerized deployment for consistency
- **Biome + Prettier**: Automated code quality and formatting

---

### 🎯 Why This Project Stands Out

- ✅ **Production-Grade Architecture**: Designed for scalability with efficient caching, error handling, and monitoring
- ✅ **Modern AI Stack**: Leverages LangChain for flexible LLM orchestration and RAG implementation
- ✅ **Real-World Application**: Solves actual enterprise problems in knowledge management and document search
- ✅ **Developer-Friendly**: Well-documented, type-safe codebase that's easy to understand and extend
- ✅ **Full-Stack Mastery**: Demonstrates expertise across frontend, backend, databases, and AI integration

---

### 🚀 Quick Start

```bash
# Clone and setup
git clone https://github.com/joydipdutta9943/Enhanced-RAG-System.git
cd Enhanced-RAG-System

# Install dependencies
bun install

# Configure environment
cp .env.example .env

# Initialize database
bun run db:generate
bun run db:push

# Start development
bun run dev
```

---

## 📈 GitHub Stats

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=joydipdutta9943&layout=compact&theme=radical)

---

## 💼 Professional Experience Highlights

- 🔧 **2+ years** of professional software development experience
- 🏗️ Architected and deployed **scalable microservices** on AWS
- 🤖 Built **AI-powered features** using LangChain, LLMs, and vector databases
- 📊 Optimized **database performance** reducing query latency by 60%
- 🚀 Led **full-stack development** of enterprise applications serving thousands of users

---

## 📫 Let's Connect!

I'm always interested in collaborating on exciting projects or discussing technology!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joydip-dutta-569428141/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:joydip.dutta9943@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/joydipdutta9943)

---

<div align="center">

### 🌟 If you find my work interesting, consider starring my repositories!

**"Building the future, one commit at a time."** 💻✨

</div>
