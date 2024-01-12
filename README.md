# Lecture Summarizer

This Python application uses the AssemblyAI API to automatically summarize virtual lectures and answer questions about the lesson material. It's built with Streamlit and AssemblyAI's Python SDK.

## Features

- **Automatic Lecture Summarization**: The application transcribes and summarizes lectures from local files, remote files, or YouTube videos using AssemblyAI's LeMUR API.
- **Question-Answering**: Users can ask questions about the summarized lecture. The answers are generated using AssemblyAI's API.
- **Interactive UI**: The application features an interactive interface created with Streamlit. Users can input their AssemblyAI API key, choose the type of file, and ask questions about the lecture.

## Use Cases

- **Online Learning**: Students can use this application to summarize and ask questions about online lectures.
- **Research**: Researchers can use this to understand lectures or talks related to their field of study.
- **Professional Development**: Professionals can use this to understand webinars, online courses, or other educational content.

## Getting Started

You need to have an AssemblyAI API key. If you don't have one, you can get it from the [AssemblyAI Dashboard](https://www.assemblyai.com/dashboard). You can either paste your API key in the application's text box or set it as an environment variable (`ASSEMBLYAI_API_KEY`).

## How to Use

1. **Enter API Key**: Paste your AssemblyAI API key in the text box or set it as an environment variable.
2. **Choose File Type**: Select the type of file you want to summarize - a local file, a remote file, or a YouTube link.
3. **Upload/Enter File**: Depending on the chosen file type, upload a local file, enter a public link to a remote file, or enter a YouTube link.
4. **Enter Context (Optional)**: Enter contextualizing information about the file, if needed.
5. **Submit**: Click the "Submit" button to start the summarization process. The application will transcribe the file, generate a summary, and display it.
6. **Ask Questions**: After the summary is displayed, ask questions about the lecture. Enter your question in the text box and click the "Submit" button to get the answer.

## Note

Processing a file takes approximately 15-30% of the file's duration. If a YouTube link is used, additional time will be needed to extract the file.

## References

- [How to build an interactive lecture summarization app](https://www.assemblyai.com/blog/how-to-build-an-interactive-lecture-summarization-app)
- [AssemblyAI Dashboard](https://www.assemblyai.com/dashboard)
- [Introducing LeMUR](https://www.assemblyai.com/lemur)
