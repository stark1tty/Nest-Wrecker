# Nest-Wrecker
Nest-Wrecker is a simple Python script in a Jupyter Notebook designed to untangle nested tags in markdown files, handy for those with extensive Obsidian Vaults or similar setups. It was created to address the challenge of managing large, interconnected note systems where tags can become cumbersome and overly complex.

## What It Does
This script efficiently processes markdown files in a given directory, transforming nested tags into individual, more manageable tags. For example, a tag like `#tag1/tag2/tag3` will be replaced with `#tag1 #tag2 #tag3`.

## Why It's Useful
Managing a vast array of interconnected tags can become a daunting task for users of Obsidian or similar note-taking applications. Nest-Wrecker simplifies this by breaking down complex, nested tags into more straightforward, standalone tags, making them easier to organize and search.

## How to Use
1. Set the `notes_directory` variable to the path of your markdown notes.
2. Run the script. It will recursively go through the specified directory, find nested tags, and separate them into individual tags.

## Before You Run
- **Back Up Your Files:** The script modifies your markdown files. Make sure to back up your files before running it.
- **Python Environment:** Ensure you have Python & Jupyter installed on your system.

## Disclaimer
This tool was created out of personal necessity due to the intricacies of managing an extensive Obsidian Vault. It's shared in the hope that it may be helpful to others facing similar tag management challenges.
