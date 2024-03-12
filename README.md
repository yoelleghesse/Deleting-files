The CSV File Cleanup is a Python script that cleans up CSV files in a specified directory by removing their contents. It utilizes the pathlib module for working with file paths.

Clone the repo:

``git clone https://github.com/your-username/csv-file-cleanup.git``

Run the script:

``python csv_file_cleanup.py``

Features:

- Recursively iterates through a directory and its subdirectories to find CSV files.
- Empties the contents of each CSV file by overwriting it with an empty byte string.
- Deletes the empty CSV files after cleaning them up.

Config:

- Modify the root_dir variable to specify the directory containing the CSV files to be cleaned up.
