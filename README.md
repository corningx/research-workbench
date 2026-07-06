# Research Workbench

A local-first research project management workbench designed for graduate students and researchers.

No installation, account registration, or server is required. Download the files and open the application directly in your browser. All research data is stored locally by default and is not uploaded automatically.

## Main Features

- Multi-project management
- Research questions and hypothesis tracking
- Research roadmap planning
- Experimental results and anomaly records
- Figure planning for papers
- Related literature management
- Task and to-do management
- JSON data import and export
- Local auto-save and recovery snapshots

## How to Use

1. Download `index.html` from the repository.
2. Open it with Chrome or Edge.
3. Create a new research project or import the example JSON data.
4. Regularly export a JSON backup from the **Data Management** page.

### Importing the Example Data

1. Open the application.
2. Go to **Data Management**.
3. Click **Import JSON**.
4. Select the example JSON file included in the repository.

## Data Storage

This project follows a local-first design. Research data is mainly stored in the local storage of your current browser.

Please note:

- Clearing browser data may delete your saved records.
- Data is not automatically synchronized when you switch browsers, computers, or website addresses.
- Export JSON backups regularly and store them in your project folder or cloud storage.
- This project is currently in beta. Do not keep the only copy of important research data in the browser.

## Project Files

```text
research-workbench/
├── index.html      # Main application
├── README.md       # Project documentation
└── demo.json       # Example research data
