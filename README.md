# Coursera Dump
Script downloads information about courses from [Coursera](https://www.coursera.org/) ans save it in xlsx file.
Courses are chosed randomly from the list.

## Usage

- **Clone repository:** `git clone https://github.com/Sir-Nightmare/10_coursera.git`  
- **Install necessary modules:** `pip3 install -r requirements.txt` 
- **Launch the script:** `python coursera.py  <options>` 

**Options:**

description | type | key | default value
--- | --- | --- | ---|
**Path to output folder** | str | `-p, --path`| same folder with the script
**Number of courses to show** | int | `-n, --number`| 20


**Examples:**

```
python coursera.py 
python coursera.py -p D:\Courses -n 15
```


# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
