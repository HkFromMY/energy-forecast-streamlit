# Streamlit Deployment for Energy Forecasting FYP

### Commands to run (Windows)
1. Ensure that you're running this on `cmd` instead of PowerShell.
2. Run `py -m venv venv`.
3. Run `venv\Scripts\activate`.
4. Run `pip install -r requirements.txt`.
5. Run `streamlit run 1_Home.py`.

### Commands for Git Large File System (LFS)
1. Run `git lfs install` to initialize the LFS (run only once per user account)
2. Run `git track "*.h5"` to track all the large files in the repository.
3. Run normal git workflow like `git add .` -> `git commit -m "git init"` -> `git push origin main` 