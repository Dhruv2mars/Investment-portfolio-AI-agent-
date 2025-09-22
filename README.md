# Investment Portfolio AI Agent

An AI-powered investment analysis tool that provides comprehensive portfolio insights, risk assessments, and personalized recommendations using the ReAct framework.

## Features

- **Stock Risk Analysis**: Detailed risk assessment for individual stocks
- **Portfolio Diversification**: Sector allocation and risk level analysis
- **Expected Return Calculation**: Historical performance-based projections
- **Smart Recommendations**: AI-driven portfolio optimization suggestions
- **Interactive Web Interface**: User-friendly Streamlit application

## Tech Stack

- **Backend**: Python, Groq API (Llama 3.1)
- **Frontend**: Streamlit
- **AI Framework**: ReAct (Reasoning and Acting)

## Quick Start

1. **Clone and setup**:
   ```bash
   git clone <your-repo-url>
   cd Investment-Portfolio-AI-Agent
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

2. **Configure environment**:
   Create `.env` file:
   ```
   GROQ_API_KEY=your_groq_api_key_here
   ```

3. **Run the application**:
   ```bash
   streamlit run src/streamlit_app.py
   ```

4. **Access the app**: Open http://localhost:8501

## Usage Examples

- "Get risk profile for NVDA stock"
- "Analyze a portfolio with 40% AAPL, 30% GOOGL, 30% SPY"
- "Calculate expected return for my portfolio"
- "Recommend adjustments for low risk tolerance"

## Requirements

- Python 3.8+
- Groq API Key (sign up at https://console.groq.com/)

## License

MIT License - see LICENSE file for details.

---

*Investment involves risks. This tool provides insights and should not be considered definitive financial advice.*