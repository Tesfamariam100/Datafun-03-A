# Datafun-03-A Project

## Project Setup

1. **Create Virtual Environment:**
   - On Windows, create a project virtual environment in the `.venv` folder.
     ```shell
     py -m venv .venv
     .venv\Scripts\Activate
     py -m pip install -r requirements.txt
     ```

## Git Workflow

2. **Add and Commit Changes:**
   - Open a terminal and navigate to your project directory.
   - Add all files in the folder to source control ("stage" them).
     ```shell
     git add .
     ```
   - Commit the changes to the local Git repository with a meaningful message.
     ```shell
     git commit -m "Add .gitignore, update README with commands"
     ```

3. **Push Changes to Remote Repository:**
   - If you want to update the remote repository (e.g., GitHub) with your local changes.
     ```shell
     git push origin main
     ```


