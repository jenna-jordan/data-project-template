# Project Documentation

Title: Project Title Goes Here
Link: Link to project (e.g. GitHub) goes here
Description: short plain language description of the project

## Abstract

High level description of the project. Include what this project has accomplished, the resources used to accomplish it, and any other relevant background information.

## Contributors

List out the name, contact information, and role for each contributor to the project

## Attribution

How you would like for this project to be cited

## Relevant Links

Include any relevant links here that may be useful both while working on the project and for reference after

## File Structure

Document the file structure and files of the project here

### Code

my-data-project
├── code
│   ├── analysis
│       └── example_analysis.ipynb
│   └── data_wrangling
│       └── example_transformation.ipynb

- example_analysis.ipynb: contains code analyzing some dataset
- example_transformation.ipynb: contains code for cleaning and transforming some dataset

### Data

my-data-project
├── data
│   ├── 0_raw
│       └── example_source.json
│   ├── 1_cleaned
│       └── example_cleaned.csv
|   ├── 2_transformed
│       └── example_transformed.parquet
│   └── 3_final
│       └── example_final.csv

- example_source.json: the raw, unmodified source data from example source
- example_cleaned.csv: data from example source that has been cleaned and is ready for further transformation
- example_transformed.csv: combines data from source 1 and source 2, and has one record per some observation
- example_final.csv: final dataset that represents some concept and is aggregated to some level

### Documentation

my-data-project
├── documentation
│   ├── images
│       └── example.png
│   ├── original_documents
│       └── example.txt
|   ├── project.md
|   ├── resources.md
|   └── sources.md

- example.png: an image file used in the README
- example.txt: documentation provided by organization A about dataset Z
- project.md: documentation about this project
- resources.md: include any useful resources for those contributing to the project
- sources.md: documentation about all source datasets

### Admin

my-data-project
├── .gitignore
├── COLLABORATORS
├── LICENSE
├── README.md
└── requirements.txt

- .gitignore: standard Python gitignore file, lists all files/folders not committed to GitHub
- COLLABORATORS: lists GitHub usernames of everyone who made commits to this repo
- LICENSE: specifies the license for this repository (defaults to CC0, update to your preferred License)
- README.md: The first file anyone will see in your repo
- requirements.txt: list out all packages and versions used in code files 