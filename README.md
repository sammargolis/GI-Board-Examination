# GI-Board-Examination
This script is designed to automate the uploading, extraction, and analysis of data related to GI Board Examinations.

### Guide for the GI Board Examination Script

This guide will assist you in setting up and running the `GI board examination vShare` Python script. The script is designed to automate the uploading, extraction, and analysis of data related to GI Board Examinations. Here's how to get everything set up and running smoothly.

#### Requirements
Before running the script, ensure that you have the following:
- **Python Environment**: A Python environment that supports package installation, such as Anaconda or a virtual environment in a development setup like Jupyter Notebook or Google Colab.
- **Internet Connection**: Required for installing packages and potentially for API calls.

#### Installation of Dependencies
All dependencies are listed within the code blocks.  Packages can often be updated and may require updates

#### Files Needed
To run the script, you will need the following files:
- **`2022_Test_Blank.csv`**: Contains the blank GI board exam questions with text and references to associated images stored in `2022_ACG_Files.zip`. Place this file in a directory that the script can access.
- **`ACG_self_assessment_examples.csv`**: Includes 5-shot learning examples with textual content and references to images in `Example_Images.zip`. Place this file in a directory that the script can access.
- **`2022_ACG_Files.zip`**: Contains all images referenced in the `2022_Test_Blank.csv`, necessary for the visual components of the exam questions. Ensure this file is in the same directory as the script.
- **`Example_Images.zip`**: Holds all images referenced in the `ACG_self_assessment_examples.csv`, providing visual support for the assessment examples. Ensure this file is in the same directory as the script.
- **API Key**: You need an API key for OpenAI & Gemini services. Store this securely and update the script to retrieve this key as needed.

All files can be found in the Google Drive Link here: https://drive.google.com/drive/folders/116W2snTaJ6l4Y55oDu9mpjF1pdW6gdul?usp=sharing

#### Example Image Files
If the script processes or generates images, ensure that these image files are correctly formatted and named according to the script's requirements. Include them in the directory or upload feature as needed.
