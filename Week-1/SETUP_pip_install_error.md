### SETUP: Pip Install Error

### Problem Description
I'm trying to set up a Python project, but I'm getting errors when running `pip install -r requirements.txt`. It's preventing the project from installing the necessary dependencies to run properly
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

- [Python Official Documentation](https://docs.python.org/3/)
- [Virtual Environments in Python](https://docs.python.org/3/library/venv.html)