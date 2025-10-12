# n8n Workflows Repository 🚀

This repository contains a collection of workflows in `.json` format that can be easily imported into [n8n](https://n8n.io/). These workflows are designed to automate various tasks and processes, making it easier to integrate and manage your data.

## Workflows 📂

### 1. Segment Large Audios and Transcribe 🎙️

**Description:** This sub-workflow processes audio files by taking the file path as input. It evaluates the file size, and if the size exceeds 20MB, it segments the audio into smaller parts. These segments are then transcribed using the Gemini transcription service. The workflow ensures efficient handling of large audio files for transcription purposes.

## How to Use 🛠️

1. Open your n8n instance.
2. Import the desired workflow `.json` file.
3. Configure the workflow parameters as needed.
4. Execute the workflow.

## License 📜

This project is licensed under the MIT License.
