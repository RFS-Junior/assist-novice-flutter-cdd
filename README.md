# Research Project: Assisting Novice Developers Learning in Flutter Through Cognitive-Driven Development

This repository contains the artifacts used in the paper "Assisting Novice Developers Learning in Flutter Through Cognitive-Driven Development" and is organized as described below. The aim is to ensure that other researchers can access, understand, and reuse the data and materials contained here.

## Paper Link
The full paper "Assisting Novice Developers Learning in Flutter Through Cognitive-Driven Development" can be accessed here: [https://arxiv.org/abs/2408.11209](https://arxiv.org/abs/2408.11209).

## Study Context
This study investigates the use of Cognitive-Driven Development (CDD) as an educational tool in a 5-week workshop for novice developers learning Flutter. CDD employs Intrinsic Complexity Points (ICPs), a metric of the approach, to manage cognitive load and aims to improve code maintainability. In the workshop, participants, who were unfamiliar with both Flutter and CDD, were trained to apply these principles in developing a software management application, demonstrating CDD's effectiveness in an educational setting.

## Data Provenance
The data in this repository was gathered during a 5-week workshop with novice developers using Flutter. It comprises control spreadsheets, project management data (from Trello), meeting notes, interview transcripts, and summaries. All data has been anonymized and was collected with the informed consent of participants.

## Ethical and Legal Statements
All participants in this study provided informed consent before the interviews and meetings were recorded. Participants' data has been anonymized to safeguard their identities, and the recordings have been carefully edited to include only the topics pertinent to the research.

## Folder Structure

### /data

#### /ICPs tables
This folder contains versions of the team's Intrinsic Complexity Points (ICP) collection during the workshop.

- **Flutter CDD - Version 1.pdf:** First version of the ICP collection.
- **Flutter CDD - Version 2.pdf:** Second version of the ICP collection.
- **Flutter CDD - Version 3.pdf:** Third version of the ICP collection.

#### /Interview
Folder containing artifacts related to the semi-structured interviews conducted during the study.

- **/Recordings:** Audio files (mp3) in Portuguese of the interviews.
- **/Summaries:** Summaries of the interviews in Portuguese (docx files), used for result analysis.
- **/Transcripts:** Complete transcripts of the interviews in Portuguese (docx files).
- **CDD Interview Script.docx:** Interview script in Portuguese, divided by topic categories.
- **Interview Schedule.xlsx:** Interview schedule.

#### /Meetings
Documentation of meetings held throughout the workshop.

- **Refactoring - Planning (09-30-24):** Audio and transcription of the refactoring phase planning.
- **Sprint 2 - Retrospective (09-16-24):** Audio and transcript of the Sprint 2 retrospective.
- **Sprint 3 - Planning (09-18-24):** Audio and transcript of Sprint 3 planning.
- **Sprint 3 and 4 - Retrospective and Planning (2509):** Audio and transcript of the retrospective and planning of Sprints 3 and 4.

### /figure
Images used in the paper or relevant to the project.

- **scrum.png:** Diagram of Scrum integration with CDD.
- **LOC.png:** Figure 3 of the paper, showing the distribution of LOC among the project's classes over different periods.
- **kanban.png:** Screenshot of Trello showing the Kanban board of the team's development tasks.
- **workshop overview.png:** Overview of the project's stages and phases.

### Data Files

- **Cognitive Load of Classes.xlsx:** Spreadsheet with the ICP count of each project class across different workshop phases.
- **Project Commits.xlsx:** Spreadsheet integrating the team's development tasks in Trello with the commits made by members.
- **Tables.xlsx:** Spreadsheet with all the tables that were added to the article, separated by tabs.
- **trello-produto-mobile.json:** Trello export file with the team's development tasks.
- **trello-retrospectiva.json:** Trello export file with notes made by team members during the retrospectives of each sprint, focusing on CDD.

## Reproducibility Instructions

To reproduce the Line of Code (LOC) charts used in the study:

1. **View Existing Chart**:
   - Open the `/figure/LOC.png` file to view the pre-generated LOC chart used in the paper.

2. **Regenerate the Chart**:
   - To regenerate the LOC chart, use the `Project Commits.xlsx` file to analyze the commit history and lines of code.

3. **Google Colab Notebook**:
   - A complete implementation for generating the LOC charts is provided in the Google Colab notebook. Access the notebook [https://colab.research.google.com/drive/13ummg-lgIX6eD2R-s-hv1-vdQsg0Y3P-](https://colab.research.google.com/drive/13ummg-lgIX6eD2R-s-hv1-vdQsg0Y3P-).
   - Open the notebook and run the cells sequentially to produce the LOC charts for both the last sprint and the refactoring phase.

## Storage Requirements
The total size of the data in this repository is approximately 455.27 MB. To download and interact with all files, ensure you have at least 500 MB of free disk space. Some files, such as large audio recordings, may require specific media players compatible with MP3 format.

## Archival Repository
This artifact is archived in `figshare` and can be cited using the following DOI: [https://figshare.com/articles/software/assist-novice-flutter-cdd/27042199](https://figshare.com/articles/software/assist-novice-flutter-cdd/27042199). Additionally, the project is available on GitHub at: [https://github.com/RFS-Junior/assist-novice-flutter-cdd](https://github.com/RFS-Junior/assist-novice-flutter-cdd).

## Language Note
All ICP tables and interview transcripts are available in Portuguese.

## License
The files in this repository are distributed under the [Creative Commons Zero v1.0 Universal License (CC0)](https://creativecommons.org/publicdomain/zero/1.0/). This license dedicates the work to the worldwide public domain, allowing it to be freely used, modified, and shared without any copyright restrictions. Please refer to the LICENSE file for full details. Note that this license disclaims warranties, similar to the Unlicense.

For more information or questions, please contact the study's authors.
