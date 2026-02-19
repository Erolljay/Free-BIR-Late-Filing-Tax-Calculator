🇵🇭 BIR Late Filing Calculator (EOPT Compliant)

A minimalist, web-based calculator designed for Filipino taxpayers to estimate penalties for late tax filings. This tool is updated based on the Ease of Paying Taxes (EOPT) Act (Republic Act No. 11976) which provides significantly lower penalties for Micro and Small Taxpayers.
![alt text](https://img.shields.io/badge/license-MIT-blue)

![alt text](https://img.shields.io/badge/EOPT-Compliant-success)

🚀 Live Demo

[Insert your GitHub Pages link here, e.g., https://yourusername.github.io/bir-late-calculator/]

✨ Features

Automatic Days Counter: Computes the exact number of days late based on the Due Date and Payment Date.
EOPT Toggle: Switch between "Micro/Small" and "Medium/Large" classifications to apply the correct penalty rates.

Surcharge Logic:
10% for Micro/Small taxpayers.
25% for Medium/Large taxpayers.

Interest Logic:
6% per annum for Micro/Small taxpayers.
12% per annum for Medium/Large taxpayers.

Compromise Penalty Table: Automatically maps your tax due amount to the BIR's standard compromise schedule (RMO 7-2015), applying a 50% discount for Micro/Small taxpayers as per latest regulations.
Minimalist UI: Modern "Accent Blue" design that is fully responsive on mobile devices.

⚖️ Penalty Logic Table (2024-Present)
Penalty Type	Micro & Small (< ₱20M Sales)	Medium & Large (≥ ₱20M Sales)
Surcharge	10%	25%
Interest (p.a.)	6%	12%
Compromise	50% of RMO 7-2015	100% of RMO 7-2015

🛠️ Installation & Setup
Clone the repository:
code
Bash
git clone https://github.com/erolljay/bir-late-calculator.git
Open the file:
Simply open index.html in any modern web browser (Chrome, Safari, Edge).
Deploy to GitHub Pages:
Go to your Repo Settings.
Click on Pages in the sidebar.
Under Branch, select main and / (root).
Click Save.
📝 Disclaimer
This calculator is for estimation purposes only. While it follows the formulas provided by the National Internal Revenue Code and the EOPT Act, it is not an official BIR tool. Always verify your final computation with your Revenue District Office (RDO) or a certified public accountant (CPA) before making payments.
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
Created with ❤️ for the Filipino Taxpaying Community.