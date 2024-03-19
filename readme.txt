Installation

Install Dependencies

Install the necessary Python packages using pip:

bash

pip install requests

pip install pandas matplotlib

Configuration

Before running the application, you need to configure your GitHub Personal Access Token and the target repository:

    Open the Python script (main.py, or whatever your main script is named).
    Locate the section where the GITHUB_TOKEN and GITHUB_REPO variables are set.
    Replace 'your_github_token_here' with your GitHub Personal Access Token.
    Replace 'owner/repo' with the GitHub repository you want to analyze, formatted as 'owner/repository_name'.

Running the Application

To run the application, ensure you are in the project's root directory, then execute:

bash

python main.py

