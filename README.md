# GroupDNA — Your WhatsApp Group, Decoded

GroupDNA is a Python + NumPy data analysis project that analyzes WhatsApp chat data to uncover group activity patterns, favourite words, response behaviour, silent streaks, and personality archetypes.

## Project Overview

This project takes a WhatsApp chat export in `.txt` format and converts the raw messages into structured data. The analysis then produces a report describing how the group communicates and behaves.

The project analyzes:

* Total messages and participants
* Messages sent by each participant
* Busiest day and busiest hour
* Group activity heatmap using NumPy
* Top 10 favourite words in the group
* Top 5 words used by each participant
* Average response speed
* Longest silent streaks
* Rule-based personality archetypes

## Technologies Used

* Python
* NumPy
* File handling
* Lists, dictionaries, sets and tuples
* Loops and conditionals
* Functions
* String processing
* Datetime operations

## Project Dataset

The project uses the synthetic WhatsApp dataset `hostel_bois.txt`.

The dataset contains approximately 60 days of group conversation with 6 participants and 3,174 parsed messages.

## Project Structure

* `GroupDNA_Prashant_1CD24CD039.ipynb` — Main Google Colab/Jupyter Notebook
* `hostel_bois.txt` — Input WhatsApp chat dataset

## Analysis Sections

1. Chat Parser
2. Group Overview
3. Activity Heatmap
4. Favourite Words
5. Response Speed and Silent Streaks
6. Personality Archetypes
7. Final GroupDNA Report

## Constraints

This project was developed using the specified project constraints.

The following libraries and pre-built tools were not used:

* Pandas
* Matplotlib
* Seaborn
* Plotly
* `collections.Counter`
* `collections.defaultdict`
* Regular expressions
* Pre-built WhatsApp analysis libraries
* AI/ML/NLP libraries

The analysis was implemented using Python fundamentals and NumPy.

## Seven-Day Development

The project was developed progressively across seven days, covering Python fundamentals, chat parsing, group statistics, word analysis, NumPy activity analysis, response patterns, personality archetypes, testing, and final report formatting.

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Upload `hostel_bois.txt` to the notebook environment.
3. Run the notebook from the first cell to the last cell.
4. The final GroupDNA report will be generated from the chat data.

## AI Assistance

AI tools were used as a learning aid to understand Python concepts, debug errors, and clarify project requirements. The implementation was developed, tested, and adapted by me according to the project constraints and dataset.

## Project Output

The final output presents a compact analytical report containing group statistics, activity patterns, favourite words, response behaviour, silent streaks, and personality archetypes.

A screenshot of the final output is included below.

<!-- Add the final GroupDNA output screenshot here -->

## Learning Outcome

This project helped me gain practical experience in processing unstructured text data using Python. I learned how to convert raw chat messages into structured information and perform meaningful analysis using dictionaries, loops, string processing, datetime operations, and NumPy arrays. It also improved my understanding of how simple rule-based logic can be used to identify behavioural patterns from data.
