# AI Study Assistant Prompt Template
Created by Gilbert Harijanto

This repository contains a customizable prompt template for creating an AI study assistant using ChatGPT. The assistant is designed to help students summarize notes, learn concepts, and quiz themselves on various subjects.

## How to Use

1. Copy the entire contents of `study_assistant_template.md`.
2. Go to [ChatGPT](https://chat.openai.com/).
3. Click on profile on top right and select "My GPTs"
4. Select "Create a GPT"
5. Paste the copied prompt into the "Instructions" column
6. Replace the placeholders in square brackets with your specific information:
   - [Assistant Name]: Name for your AI assistant
   - [Field of Expertise]: The subject area of expertise
   - [User Name]: Your name or the student's name
   - [Course Name]: The specific course or subject
   - [Max Level]: The highest level attainable in the XP system
   - [XP per Level]: XP points needed to level up
   - [Subject]: The general subject area for the Learning Mode
   - [Quiz XP]: XP points awarded for correct quiz answers
7. Give your GPT a Name and Description
8. (Optional) Add "/help" in the "Conversation Starters" column
9. In the "Capabilities" column, select only the "Code Interpreter & Data Analysis"
10. Click Create

## Features

- Customizable for any subject or course
- Multiple modes for different types of content (Transcript, PowerPoint, Reading)
- Comprehensive note-taking functionality
- Learning mode for exploring specific topics
- Quiz mode for self-assessment
- XP point system for gamified learning

## Modes

- **Transcript Mode**: Summarizes lecture transcripts
- **PowerPoint Mode**: Summarizes PowerPoint presentations
- **Reading Mode**: Summarizes assigned readings
- **Notes Mode**: Combines information from all sources into comprehensive notes
- **Learning Mode**: Provides explanations and follow-up questions on specific topics
- **Quiz Mode**: Generates multiple-choice questions for self-assessment

## Slash Commands

- `/help`: List all available commands
- `/transcript`, `/ppt`, `/reading`: Enter respective modes
- `/learn`: Enter Learning Mode
- `/quiz`: Enter Quiz Mode
- `/notes`: Generate comprehensive notes
- `/rank`: Display current level and XP
- `/motivate`: Receive a motivational message
- `/esc`: Exit all modes

## Customization

Feel free to modify the template to better suit your specific needs. You can add new modes, change the XP system, or adjust the instructions for each mode.

## Author

**Gilbert Harijanto**
- LinkedIn: [linkedin.com/in/gilbertharijanto/](https://www.linkedin.com/in/gilbertharijanto/)

Feel free to reach out for questions or collaborations!

## License

This project is licensed under the MIT License:

MIT License

Copyright (c) 2023 Gilbert Harijanto

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
