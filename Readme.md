# Electric Substation chatbot

Welcome to the Electric Substation Chatbot, created as part of the GTA Sandshore Hackathon organized by MuLearn. This chatbot is designed to answer queries related to electric substations and provide information about various electric components. Whether you are an engineer, student, or someone interested in learning about electric substations, this chatbot can be a valuable resource.

## Contents

The following are the general key components of a README file:

- **Project title:** This is the name of the project. It describes the whole project in a few words and helps people understand the primary goal and aim.
- **Description:** Your description is an essential part of your project. It should provide a brief overview of what the project is about and what it does.
- **Usage:** This section should provide instructions on how to use the chatbot.
- **Implementation:** This section should provide information on how the chatbot was implemented, including the libraries and tools used.
- **Future Work:** This section should provide information on potential areas for future improvement.
- **References:** This section should provide links to relevant resources.

## Usage

The Electric Substation Chatbot is hosted at [gta-sandshore-chatbot.streamlit.app](https://gta-sandshore-chatbot.streamlit.app). Simply navigate to the website and start asking questions related to electric substations. The chatbot will provide responses based on the information it has been trained on.

## Implementation

The Electric Substation Chatbot is implemented in Python using several libraries, including Streamlit, PyPDF2, and HuggingFaceInstructEmbeddings. The chatbot extracts text from a PDF document, splits the text into chunks, creates a vector store from the text chunks, and uses a conversation chain to handle user input and generate responses.

