# 🚀 AI Data Analysis Tool
> Transform your data into actionable insights with the power of artificial intelligence

## Overview
This intelligent data analysis platform combines cutting-edge AI technology with powerful visualization tools to help you extract meaningful insights from your datasets. Simply upload your data, ask questions, and watch as the AI generates comprehensive reports and visualizations.

## Key Features

| Capability | Description |
|------------|-------------|
| 🧠 Smart Analysis | Advanced AI algorithms understand your data context |
| 📈 Dynamic Charts | Beautiful visualizations using modern plotting libraries |
| 🌐 Data Import | Direct data fetching from web sources |
| 📁 Format Support | Works with CSV, Excel, JSON, Parquet, and text files |
| ⚡ Batch Processing | Handle multiple queries simultaneously |
| 🎯 User-Friendly | Intuitive interface for all skill levels |
| 🔥 High Performance | Optimized for speed and efficiency |

## Quick Setup

### Prerequisites
- Python 3.8 or higher
- Internet connection for AI services

### Installation Steps

1. **Download the project**
```bash
git clone https://github.com/your-username/ai-data-analysis-tool.git
cd ai-data-analysis-tool
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Configure environment**
Create a `.env` file in the project root:
```
GEMINI_API_KEY=your_google_gemini_api_key
LLM_TIMEOUT_SECONDS=240
```

4. **Launch the application**
```bash
python -m uvicorn app:app --reload
```

Visit `http://localhost:8000` in your web browser to start analyzing data.

## How to Use

### Step 1: Prepare Your Questions
Create a text file with your analysis questions:
```
What are the top performing products by revenue?
Identify any seasonal trends in the data
Show the distribution of customer ages
Find correlations between variables
```

### Step 2: Upload Your Data
- Choose your dataset file (CSV, Excel, JSON, Parquet, or TXT)
- Upload your questions file
- Click analyze

### Step 3: Get Results
The AI will process your data and provide:
- Detailed insights and summaries
- Professional visualizations
- Statistical analysis
- Actionable recommendations

## Technical Architecture

### Backend Components
- **FastAPI**: Modern web framework for high-performance APIs
- **LangChain**: Advanced language model orchestration
- **Google Gemini AI**: State-of-the-art generative AI engine
- **Pandas & NumPy**: Efficient data manipulation
- **Matplotlib & Seaborn**: Professional-grade plotting

### Frontend
- Clean, responsive web interface
- Modern CSS styling
- Interactive user experience

## API Documentation

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/` | Main application interface |
| POST | `/api` | Submit data and questions for analysis |
| GET | `/summary` | Application status and diagnostics |

## Supported File Types

| File Type | Extensions |
|-----------|------------|
| Comma Separated Values | .csv |
| Microsoft Excel | .xlsx, .xls |
| JavaScript Object Notation | .json |
| Apache Parquet | .parquet |
| Plain Text | .txt |

## Use Cases

- **Business Intelligence**: Sales analysis, KPI tracking, market research
- **Academic Research**: Data exploration, statistical analysis, hypothesis testing
- **Data Science**: Exploratory data analysis, pattern recognition, anomaly detection
- **Reporting**: Automated report generation, dashboard creation

## Security & Privacy

- **Local Processing**: All data remains on your machine
- **Secure Configuration**: API keys stored in environment variables
- **No Data Storage**: Files are processed in memory only
- **CORS Protection**: Configurable cross-origin policies

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for bugs and feature requests.

## Support

For questions or support, please open an issue in the GitHub repository.