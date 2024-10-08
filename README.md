# Subcode: Find Live Subdomains by HTTP Status Code
Subcode is a Python-based tool designed to help you discover live subdomains of a target domain by analyzing their HTTP status codes. It provides a reliable and effective means of identifying active subdomains and their respective status codes, making it a valuable tool for security testing, bug bounty hunting, or general domain reconnaissance.

# Installation

To get started with Subcode, follow these steps for installation:

1. Clone the GitHub Repository:

    git clone https://github.com/Vign3sh-user/subcode.git

2. Navigate to the Subcode Directory:

    cd subcode

3. Install Dependencies:

    pip install -r requirements.txt


# Usage

After successfully installing Subcode, you can use it to discover live subdomains based on their HTTP status codes. Here's how to use it:

1. Prepare Your Target List:

    Create a text file, e.g., targets.txt, containing the list of target domains you want to scan for live subdomains. Each domain should be on a separate line.

2. Run Subcode:

   python3 subcode.py targets.txt


![Screenshot](https://github.com/user-attachments/assets/ca9d0748-909c-417d-9ec8-606818ec4b65)

