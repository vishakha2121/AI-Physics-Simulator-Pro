# 🚀 AI Physics Simulation Generator

[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/vishakha2121/AI-Physics-Simulator-Pro)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.9+-blue)](https://python.org)
[![React](https://img.shields.io/badge/React-18.2+-61DAFB)](https://reactjs.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.104+-009688)](https://fastapi.tiangolo.com)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## 📌 Project Overview

The **AI Physics Simulation Generator** is an intelligent, web-based platform that leverages artificial intelligence to create realistic physics simulations for engineering and scientific applications. This project combines the power of **deep learning**, **neural operators**, **Physics-Informed Neural Networks (PINNs)**, and **Graph Neural Networks** to generate accurate simulations of complex physical phenomena.

### 🎯 Key Features

- 🌊 **Fluid Dynamics Simulation** - Navier-Stokes equations, turbulence modeling
- 💥 **Collision Physics Engine** - Rigid body dynamics, particle systems
- 🌤️ **Weather Pattern Modeling** - Atmospheric modeling, precipitation
- ⚙️ **Mechanical Systems Analysis** - Stress, strain, vibration analysis
- 🤖 **AI-Powered Code Generation** - Gemini API integration
- 📊 **Real-time Visualization** - Interactive 2D/3D plots
- 🔐 **User Authentication** - JWT-based secure login
- 📁 **Export/Import** - JSON, CSV, and image exports

## 🛠️ Tech Stack

### Backend
- **Framework**: FastAPI 0.104+
- **Language**: Python 3.9+
- **Database**: SQLite
- **AI Integration**: Google Gemini API
- **Authentication**: JWT with Python-JOSE
- **ML Libraries**: NumPy, SciPy, Pandas

### Frontend
- **Framework**: React 18.2+
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **State Management**: React Context API
- **HTTP Client**: Axios
- **Charts**: Recharts
- **Animations**: Framer Motion

### AI/ML Technologies
- Neural Operators
- Physics-Informed Neural Networks (PINNs)
- Graph Neural Networks (GNNs)
- Google Gemini API

## 📁 Project Structure


## 🚀 Quick Start

### Prerequisites

- Python 3.9 or higher
- Node.js 18 or higher
- npm or yarn
- Git

### Installation

#### 1. Clone the Repository

```bash
git clone https://github.com/vishakha2121/AI-Physics-Simulator-Pro.git
cd AI-Physics-Simulator-Pro

# Navigate to backend
cd backend

# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Create .env file
cp .env.example .env
# Edit .env with your Gemini API key

# Run database migrations
python scripts/init_db.py

# Start backend server
uvicorn app.main:app --reload

# Open new terminal
cd frontend

# Install dependencies
npm install

# Create .env file
cp .env.example .env

# Start development server
npm run dev