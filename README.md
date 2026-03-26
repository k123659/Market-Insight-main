Market Insight
An AI-powered stock market analysis platform that provides comprehensive financial data and intelligent insights through a conversational interface.

Overview
Market Insight leverages advanced AI agents to deliver real-time stock market information, financial analysis, and investment insights. The platform combines the power of LangChain and OpenAI's language models with Yahoo Finance data to create an intelligent assistant for stock market research.

Technology Stack
Backend:

FastAPI for high-performance API endpoints
LangChain & LangGraph for AI agent orchestration
OpenAI GPT models for intelligent responses
YFinance for financial data retrieval
Langfuse for observability and tracing
Frontend:

Modern React-based interface
Real-time streaming responses
Responsive design for all devices
Getting Started
Prerequisites
Python 3.x
Node.js (for frontend)
OpenAI API key
Installation
Clone the repository
Install Python dependencies:
pip install -r requirements.txt
Set up environment variables in .env file
Install frontend dependencies:
cd frontend
npm install
Run the backend server:
python main.py
Run the frontend development server:
cd frontend
npm run dev
Access the API at http://localhost:8000 and frontend at http://localhost:5173
Project Structure
MarketInsight/
├── components/     # AI agent configuration
├── utils/          # Tools and utilities
├── config/         # Configuration files
├── frontend/       # React frontend application
└── main.py         # FastAPI server entry point
API Capabilities
The platform provides 16 specialized tools for comprehensive stock analysis:

Stock price tracking
Historical data analysis
Financial statements (Balance Sheet, Income Statement, Cash Flow)
Company information and ratios
Dividend and split history
Ownership and holder data
Insider transactions
Analyst recommendations
Company ticker lookup
About
This repository contains a comprehensive stock market analysis project that integrates historical data with real-time global news. This project leverages data analysis techniques to provide insights into market movements and forecasts based on both historical trends and current events.

market-insight-theta.vercel.app
Topics
stock-market equity stock-indexes nse bse nse-stock-data bse-stock-data stock-analysis sebi stocks-data
Resources
 Readme
License
 GPL-3.0 license
 Activity
Stars
 33 stars
Watchers
 2 watching
Forks
 20 forks
Report repository
Releases
No releases published
Deployments
16
 Production 3 months ago
+ 15 deployments
Packages
No packages published
Contributors
1
@KalyanM45
KalyanM45 Hema Kalyan Murapaka
Languages
Python
62.3%
 
TypeScript
24.0%
 
CSS
10.3%
 
HTML
1.8%
 
JavaScript
1.6%
Footer
© 2026 GitHub, Inc.
Footer navigation
Terms
Privacy
