# Automatic-File-Sorter

This is a basic Python project that sorts files in a given directory into subfolders based on their file types. It currently handles .csv, .jpeg, and .xlsx files and moves them into designated folders for easier organization.

# Features

* Automatically creates subfolders for each file type (csv files, image files, xlsx files).
* Moves .csv, .jpeg, and .xlsx files to their respective folders.
* Prevents overwriting existing files by checking if the file already exists in the destination folder.

# Prerequisites

* Python 3.x
The following Python libraries are required:
 * os
 * shutil

# How to Use

1.Clone or download this repository.
2.Update the path variable in the Python script to the directory containing the files you want to sort.
3.Run the script using Python:
    python file_sorter.py

# Project Structure

file_sorter.py: Main script for sorting files.

# Example

If you have the following files in your folder:
 - example.csv
 - image.jpeg
 - data.xlsx
After running the script, the folder will be structured like this:
  /csv files
    - example.csv
/image files
    - image.jpeg
/xlsx files
    - data.xlsx

# License

This project is free to use and modify.

# Contributing

Feel free to submit a pull request or open an issue if you have any suggestions or improvements!






