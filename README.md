# statsbomb-scripts
Random scripts using the statsbomb data. try it 

# Find Ur Lineups

This repository contains a script to extract and analyze lineup data from the [StatsBomb Open Data](https://github.com/statsbomb/open-data) dataset. The script identifies team lineups across matches and is built using Python in a Jupyter Notebook format.

## 📁 Requirements

- Python 3.7+
- Jupyter Notebook
- pandas, json, os, glob (all installable via pip)

## ⚙️ Setup Instructions

1. **Clone the StatsBomb dataset**
   
   This script requires access to the StatsBomb open data. Clone their GitHub repository:

   ```bash
   git clone https://github.com/statsbomb/open-data.git

	2.	Update File Path
In the notebook (find_ur_lineups.ipynb), set the file_path variable to the path of your local copy of the open-data/data/ directory. For example:

file_path = '/your/local/path/to/open-data/data/'


	3.	Run the Notebook
Launch Jupyter Notebook and run the cells to extract and process lineup data.

📦 Output
	•	Team lineups extracted per match
	•	Optionally, cleaned/aggregated data for further analysis

📄 License

This project is licensed under the [MIT License]('./LICENSE'). See the LICENSE file for more details.

⸻

Data used in this project belongs to StatsBomb and is available under their open data license.
