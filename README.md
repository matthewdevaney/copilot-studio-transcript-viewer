# Copilot Studio Transcript Viewer

__Copilot Studio Transcript Viewer__ is a Power Apps code app  that enables you to explore the *full* conversation transcripts for any agent and see *hidden* their details to assist with troubleshooting.

Transcripts can be accessed in two ways:
- Search for a transcript in the *current environment* where the app is installed.
- Paste a transcript JSON from *another environment* directly into the app.

<img width="1236" height="755" alt="image" src="https://github.com/user-attachments/assets/42b66ced-147b-47cb-a751-225d248887c6" />


## Quickstart

### Search transcript from the current environment

1. Search for the transcript using the Agent Name or Conversation ID from the Activity tab in Copilot Studio

2. Select the transcript

3. Expand activities found in the transcript to see their full details

<img width="1424" height="894" alt="cstranscriptviewer-1" src="https://github.com/user-attachments/assets/684b13ab-a070-469d-8139-ecd194f65d0d" />


### Copy and paste transcript JSON from another environment

1. Open the three dots menu found in the sidebar footer

2. Select Import JSON

3. Copy the JSON value found in the  *content* column of the conversationtranscripts table

4. Paste the *content* JSON into the the multi-line text input and press OK

5. Expand activities found in the transcript to see their full details

<img width="1424" height="894" alt="cstranscriptviewer-2" src="https://github.com/user-attachments/assets/7d48f2ce-49d1-44b1-be2d-1e191232052a" />


## Pre-Requisites

The following items are required to use the Transcript Viewer app:
- Power Apps Premium license 
- Security role with organization-level read-access to these tables:
    - Agent (bot) 
    - Conversation Transcript (conversationtranscript) 


## Installation

1. Download the managed solution from the Releases section of this repostory.

2. Open the Power Platform environment you wish to install the solution into in Power Apps.

3. Go to the Solutions menu and select Import.

4. Select the managed solution and import it into the environment.

5. Wait for the solution to be installed.

6. Share the Power Apps code app named Copilot Studio Transcript viewer with users and ensure they have a Power Apps Premium license.

7. Open the application.
