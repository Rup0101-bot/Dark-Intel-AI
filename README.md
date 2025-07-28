# Dark-Intel-AI
Dark-Intel-AI: Advanced dark web intelligence system for law enforcement. Features automated Tor-based data collection, real-time AI analysis via Groq LLM, parallel crawling, OCR processing, and interactive chat interface. Includes bundled Tor, SQLite storage, visual correlation diagrams. Restricted to authorized agencies only.

# DarkBert: Advanced Dark Web Intelligence Collection & Analysis System

## Project Overview

**DarkBert** is a sophisticated dark web intelligence collection and analysis system designed exclusively for law enforcement agencies and authorized personnel. This comprehensive Python-based tool combines automated dark web data collection, real-time LLM-powered analysis, and advanced correlation capabilities to provide actionable intelligence from the dark web.

## Core Capabilities

### 1. **Dark Web Data Collection Engine**
- **Multi-Engine Search**: Automatically discovers and utilizes multiple onion search engines through Ahmia.fi integration
- **Tor Integration**: Includes bundled Tor Expert Bundle (Windows x86_64-14.5.4) for seamless dark web access
- **Parallel Crawling**: High-performance parallel crawling of search engines and subpages using ThreadPoolExecutor
- **Deep Site Crawling**: Recursive crawling of onion sites up to configurable depth levels
- **OCR Text Extraction**: Extracts text from images using Tesseract OCR for comprehensive data collection
- **Smart Query Processing**: Supports both user-defined queries and AI-generated random topics

### 2. **Real-Time LLM Intelligence Analysis**
- **Groq LLM Integration**: Powered by Llama3-70b-8192 and Llama3-8b-8192 models for advanced analysis
- **Live Data Processing**: Continuous crawling with real-time LLM summarization and correlation
- **Conversational AI Interface**: Interactive chatbot that combines live dark web data with LLM intelligence
- **Query Expansion**: AI-powered query expansion for comprehensive data discovery
- **Relevance Scoring**: Intelligent ranking of results based on query relevance

### 3. **Advanced Data Management & Visualization**
- **SQLite Database**: Robust data storage with search results, related links, and metadata
- **Visual Correlation Diagrams**: Rich terminal-based visualization of data relationships
- **Domain Grouping**: Intelligent organization of results by onion domains
- **Keyword Extraction**: Advanced keyword extraction using spaCy NLP library
- **Data Export**: Full raw data export capabilities for external analysis

### 4. **Interactive User Interface**
- **Rich Terminal UI**: Beautiful, colorful terminal interface using Rich library
- **Modern Menu System**: Arrow key navigation with live updates
- **Hotkey Support**: Keyboard shortcuts for pause/resume/switch operations
- **Progress Indicators**: Real-time progress tracking for all operations
- **Panel-Based Display**: Organized information display with color-coded panels

## Technical Architecture

### **Core Components**

1. **[`main.py`](DarkBert/darkweb_ai/main.py:1)** - Entry point that launches the main menu system
2. **[`darkweb_collector.py`](DarkBert/darkweb_ai/darkweb_collector.py:1)** - Primary data collection engine with parallel crawling
3. **[`llm_chat.py`](DarkBert/darkweb_ai/llm_chat.py:1)** - Real-time LLM chat interface with live data integration
4. **[`conversational_llm_chat.py`](DarkBert/darkweb_ai/conversational_llm_chat.py:1)** - Advanced conversational AI chatbot
5. **[`onion_utils.py`](DarkBert/darkweb_ai/onion_utils.py:1)** - Tor proxy utilities and onion site handling
6. **[`db_utils.py`](DarkBert/darkweb_ai/db_utils.py:1)** - Database initialization and management
7. **[`ahmia_utils.py`](DarkBert/darkweb_ai/ahmia_utils.py:1)** - Ahmia.fi integration for search engine discovery
8. **[`gorq_llm_utils.py`](DarkBert/darkweb_ai/gorq_llm_utils.py:1)** - Groq LLM API integration utilities

### **Key Features**

- **Automated Tor Management**: Automatic Tor process startup and management
- **Multi-threaded Architecture**: Concurrent processing for maximum efficiency
- **Error Handling**: Robust error handling with retry mechanisms
- **Content Filtering**: Advanced filtering to exclude error pages and irrelevant content
- **Image Processing**: OCR extraction from dark web images
- **Data Correlation**: AI-powered correlation analysis between collected data points

## System Requirements

- **Python 3.8+**
- **Windows x86_64** (includes bundled Tor Expert Bundle)
- **Groq API Key** for LLM functionality
- **Required Dependencies**: [`stem`](DarkBert/darkweb_ai/requirements.txt:1), [`requests[socks]`](DarkBert/darkweb_ai/requirements.txt:2), [`beautifulsoup4`](DarkBert/darkweb_ai/requirements.txt:3), [`openai`](DarkBert/darkweb_ai/requirements.txt:4), [`rich`](DarkBert/darkweb_ai/requirements.txt:5)

## Usage Modes

### **1. Data Collection Mode**
- Specific query-based collection
- Random topic exploration
- Multi-engine parallel searching
- Deep crawling with configurable depth

### **2. Live LLM Chat Mode**
- Real-time dark web data crawling
- Continuous LLM analysis and summarization
- Hotkey controls for pause/resume/switch
- Live correlation and pattern detection

### **3. Conversational AI Mode**
- Interactive chatbot interface
- Combined database and live data analysis
- Query expansion and smart searching
- Incremental result display

### **4. Data Analysis & Visualization**
- Visual correlation diagrams
- Domain-based data grouping
- Keyword-based data filtering
- Export capabilities for external analysis

## Security & Legal Compliance

**DarkBert operates under strict legal restrictions:**

- **Exclusive Law Enforcement Use**: Licensed only for authorized law enforcement agencies
- **Verification Required**: Users must provide valid law enforcement credentials
- **No Commercial Use**: Prohibited for commercial or unauthorized purposes
- **Legal Compliance**: All usage must comply with applicable laws and regulations

## Developer Information

**Developed by**: Mr. Rup Sarkar  
**License**: MIT License with Usage Restrictions  
**Published**: July 28, 2025  
**Copyright**: © 2025 Rup Sarkar  (rupsarkar0101@gmail.com / rupsakar50@gmail.com)

## Technical Highlights

- **High-Performance Crawling**: Multi-threaded architecture with up to 8 concurrent workers
- **AI-Powered Analysis**: Advanced LLM integration for intelligent data processing
- **Real-Time Processing**: Live data collection with immediate analysis and correlation
- **Comprehensive Coverage**: Multiple search engines with deep site exploration
- **Rich Visualization**: Advanced terminal UI with color-coded information display
- **Robust Error Handling**: Comprehensive error management and retry mechanisms

DarkBert represents a cutting-edge solution for law enforcement agencies requiring sophisticated dark web intelligence capabilities, combining automated data collection with advanced AI analysis for actionable insights.
