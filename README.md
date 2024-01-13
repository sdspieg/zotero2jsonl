# zotero2jsonl
Code to process exports from a Zotero group library to jsonl
## Overview
`zotero2jsonl` is a Python-based tool for efficiently extracting data from a Zotero SQLite database and converting it into a JSONL (JSON Lines) format. This tool is ideal for researchers, librarians, and anyone who utilizes Zotero for bibliographic data management and wishes to analyze or share their data in a versatile and widely-used format.

## Features
- Extracts author names, attachment paths, and other relevant fields from Zotero's SQLite database.
- Transforms data for enhanced readability and analysis.
- Exports data to the JSONL format, perfect for large datasets and further processing.

## Prerequisites
Before using `zotero2jsonl`, ensure you have the following:
- Python 3.x installed.
- Access to Zotero SQLite database file.
- Required Python libraries: `pandas`, `sqlite3`.

## Installation
Clone the repository or download the Jupyter Notebook directly:

```bash
git clone https://github.com/your-username/zotero2jsonl.git
```
You can copy and paste this code block into your README file on GitHub, and it will provide instructions for users on how to clone your repository.

Or simply download the `.ipynb` file if you're not using git.

## Usage
To use `zotero2jsonl`, follow these steps:
1. Update the `zotero_db_path` in the notebook to the path of your Zotero SQLite database.
2. Execute the notebook cells in order. The notebook will:
   - Establish a connection to the Zotero database.
   - Extract relevant data.
   - Transform and merge data into a cohesive dataset.
   - Export the dataset to a JSONL file.
3. The exported JSONL file can be found in the specified output directory.

## Customization
- Modify SQL queries to extract different data as per your requirements.
- Change the output path and filename for the JSONL file as needed.

## Contributing
Contributions to `zotero2jsonl` are welcome. Please fork the repository and submit a pull request with your proposed changes.

## License
This project is open source and available under the [MIT License](LICENSE).

## Contact
For any queries or suggestions, feel free to open an issue in the GitHub repository.

Thank you for using or contributing to `zotero2jsonl`!

