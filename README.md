# Cold Email Generator using Llama 3.1

## Overview

This project is a **Cold Email Generator** designed to automate the process of creating personalized cold emails based on job postings. Leveraging the power of **Llama 3.1** for fast and efficient email generation, this tool extracts relevant skills and requirements from job postings, generates tailored emails, and streamlines the job application process. The project integrates **ChromaDB** for data storage, **Web Loader** for web scraping, and **Streamlit** for a user-friendly interface.

##DIAGRAM
![image](https://github.com/user-attachments/assets/f15e2e38-9250-4f65-bd65-e5be3b9372f4)


## Features

- **Automated Email Generation**: Generate personalized cold emails based on job post skills and requirements.
- **Llama 3.1 Integration**: Utilize Llama 3.1 for fast and accurate email generation.
- **ChromaDB Collections**: Create and manipulate collections in ChromaDB using Python for efficient data storage and retrieval.
- **Web Scraping**: Use **Web Loader** to scrape job postings and extract relevant data.
- **Prompt Extraction**: Extract data and generate emails using **Prompt Extract**.
- **Prompt Templates**: Create customizable prompt templates for email generation using Gen AI.
- **Streamlit UI**: Quick and intuitive UI prototyping with **Streamlit**.
- **API Key Security**: Best practices for securely storing API keys separately from the codebase.
- **Job Application Automation**: Automate the job application process using Gen AI and Llama 3.1.

## Technologies Used

- **Llama 3.1**
- **ChromaDB**
- **Python**
- **Web Loader**
- **Prompt Extract**
- **Streamlit**
- **Gen AI**
  
## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/cold-email-generator.git
   cd cold-email-generator
   ```

2. **Set Up a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up API Keys**:
   - Create a `.env` file in the root directory.
   - Add your API keys and other sensitive information to the `.env` file:
     ```plaintext
     API_KEY=your_api_key_here
     ```

5. **Run the Application**:
   ```bash
   streamlit run app.py
   ```

## Usage

1. **Input Job Posting URL**: Enter the URL of the job posting you want to generate a cold email for.
2. **Extract Data**: The tool will scrape the job posting and extract relevant skills and requirements.
3. **Generate Email**: Using Llama 3.1, the tool will generate a personalized cold email based on the extracted data.
4. **Review and Send**: Review the generated email, make any necessary adjustments, and send it directly from the application.

## Project Structure

```
cold-email-generator/
│
├── tutorial_groq/          # Tutorial files for Groq integration
├── tutorial_chromadb/      # Tutorial files for ChromaDB integration
├── email_generator/        # Module for email generation logic
├── app.py                  # Streamlit application entry point
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
├── .env                    # Environment variables for API keys
├── main.py                 # Main script to run the application
├── chains.py               # Logic for chaining processes (e.g., data extraction, email generation)
├── portfolio.py            # Web scraping and data extraction logic
├── utils.py                # Utility functions
└── resource/               # Resource files
    └── my_portfolio.csv    # Sample portfolio data for email generation
```

## Best Practices

- **API Key Security**: Always store API keys and sensitive information in a `.env` file and never commit them to version control.
- **Prompt Templates**: Customize prompt templates in the `templates/` directory to suit different job roles and industries.
- **Data Privacy**: Ensure that any data scraped or processed complies with privacy laws and regulations.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeatureName`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeatureName`).
5. Open a pull request.


---

**Happy Coding!** 🚀
