# Blocker Solutions Documentation

## Overview

The **Blocker Solutions** documentation is designed to help us overcome technical blockers as we progress through the training program. Each week, a folder will contain a series of markdown files that document any technical blockers. By referencing these markdown files, we will be able to quickly overcome obstacles, learn from challenges, and foster a collaborative environment to support rapid skill acquisition.

## Table of Contents

1. [Getting Started](#getting-started)
2. [Folder Structure](#folder-structure)
3. [Contributing to Blocker Solutions](#contributing-to-blocker-solutions)
4. [Blocker Solution Format](#blocker-solution-format)
5. [Training Weeks and Blocker Categories](#training-weeks-and-blocker-categories)

---

## Getting Started

This document serves as a reference for tackling technical blockers encountered throughout the training program. The folders have been created so as we progress, you'll be able to find detailed solutions to various problems. The goal is to resolve issues efficiently and share knowledge to improve everyone's learning experience.

### How to Use This Documentation:
- Browse the week-based folders to identify blockers related to a specific topic.
- Each file will have a clear title indicating the issue, followed by a brief description of the problem, a step-by-step guide for resolution, and links to any relevant external resources.
- If you encounter a new blocker that is not documented yet, you can contribute by creating a new markdown file, following the format described below.

---

## Folder Structure

Each week has its own folder. Inside each folder, you will find markdown files that document specific blockers for the topics referenced in the [category links](#training-weeks-and-blocker-categories) below. The structure will look like this:

```
BlockerSolutions/
├── Week1/
│ ├── blocker-FIRST_BLOCKER.md
│ ├── blocker-SECOND_BLOCKER.md
│ └── ...
├── Week2/
│ ├── blocker-FIRST_BLOCKER.md
│ ├── blocker-SECOND_BLOCKER.md
│ └── ...
├── ...
└── Week12/
│ ├── blocker-FIRST_BLOCKER.md
│ ├── blocker-SECOND_BLOCKER.md
└── ...
```


Each markdown file follows a consistent format to ensure clarity and ease of navigation. If you run into a blocker not yet listed, please follow the contribution guidelines provided in the next section.

---

## Contributing to Blocker Solutions

Anyone can contribute to the **Blocker Solutions** repository. If you encounter a new blocker or solution not yet documented, please create a new markdown file in the appropriate week folder and submit it for review. 

### Steps for Contributing:
1. **Identify the Blocker**: Ensure the problem you're solving is not already documented.
2. **Create a New File**: Format the file name using the following convention: `blocker-<BLOCKER_TITLE>.md` (e.g., `blocker-BLOCKER_TITLE.md`).
3. **Follow the Blocker Solution Format**: Use the structure outlined below.
4. **Submit for Review**: Once completed, submit your file for review by the training leads or fellow trainees for accuracy and clarity.

### Example Submission Format:
- **Title**: Provide a clear and descriptive title for the issue (try to keep it as short as possible).
- **Description**: A 1-2 sentence description explaining the problem.
- **Solution**: A step-by-step guide to resolving the issue, with any necessary screenshots or code snippets.
- **Documentation Links**: Include links to any external resources that can assist in solving the problem.

---

## Blocker Solution Template

Feel free to copy and paste this template directly to ensure consistency. Each markdown file should follow this structure:

### Title
A brief, descriptive title that highlights the problem.

### Problem Description
1-2 sentences that explains the blocker. This description should provide enough context for someone unfamiliar with the issue to understand.

Example:
- "I'm trying to set up a Python project, but I'm getting errors when running `pip install -r requirements.txt`. It's preventing the project from installing the necessary dependencies to run properly."

### Solution
A detailed, step-by-step guide to resolve the issue. Include any necessary commands, code snippets, or screenshots to clarify the solution.

Example:
### Solution

1. **Step 1**: Ensure you're in the root of your Python project directory.

2. **Step 2**: (Optional but recommended) Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

3. **Step 3**: Install project dependencies from requirements.txt:

4. **Step 4**: If you encounter errors, try deleting the virtual environment folder and reinstalling:
    ```bash
    deactivate  # Only if currently in the virtual environment
    rm -rf venv  # On Windows: rmdir /s /q venv
    python3 -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt

### Documentation Links

Include links to any relevant external documentation or resources, such as official docs, StackOverflow threads, or training materials.

**Example:**

- [Python Official Documentation](https://docs.python.org/3/)
- [Virtual Environments in Python](https://docs.python.org/3/library/venv.html)

---

## Training Weeks and Blocker Categories

Each week will be focused on different topics. Blockers are categorized and mapped to the [learning targets](https://github.com/Data-Cohort-2025/class-notes/tree/main/learning%20targets) to make them easier to locate. Below is a general outline of the topics as currently outlined:

- **Week 1**: [Environment Setup & Fundamentals (UNIX, Python, Git)](https://github.com/r-brown1/Week-1)
- **Week 2**: [PART 1 - Python Data Structures | NumPy & Pandas | Data Cleaning | UNIX Shell Scripting](https://github.com/r-brown1/Week-2)
- **Week 3**: [PART 2 - Python Data Structures | NumPy & Pandas | Data Cleaning | UNIX Shell Scripting](https://github.com/r-brown1/Week-3)
- **Week 4**: [Advanced SQL | Data Modeling | ETL Pipelines | Data Formats (CSV, JSON, XML, etc.) | Data Visualization](https://github.com/r-brown1/Week-4)

[//]: # (- **Week 5**: []&#40;https://github.com/r-brown1/Week-5&#41;)

[//]: # (- **Week 6**: []&#40;https://github.com/r-brown1/Week-6&#41;)

[//]: # (- **Week 7**: []&#40;https://github.com/r-brown1/Week-7&#41;)

[//]: # (- **Week 8**: []&#40;https://github.com/r-brown1/Week-8&#41;)

[//]: # (- **Week 9**: []&#40;https://github.com/r-brown1/Week-9&#41;)

[//]: # (- **Week 10**: []&#40;https://github.com/r-brown1/Week-10&#41;)

[//]: # (- **Week 11**: []&#40;https://github.com/r-brown1/Week-11&#41;)

[//]: # (- **Week 12**: []&#40;https://github.com/r-brown1/Week-12&#41;)

For each topic, any blocker files you create should be placed inside their corresponding folder. Blockers may include environment setup errors, syntax issues, bugs, or any other challenges faced when practicing or completing tasks. 

---

## Conclusion

This documentation is a living resource, meant to evolve over time as new blockers are discovered and solutions are provided. By contributing and referencing this guide, we can build a shared knowledge base and support each other. Please feel free to make any changes or additions.

Remember: Every challenge is an opportunity for growth. Let's enjoy this process together!

