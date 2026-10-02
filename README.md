# BSAI-3rd
A collaborative repository for BSAI 1st batch students.

how to upload files into BSAI-1st-batch repository

🔒 PART 1: HIDE YOUR EMAIL (DO THIS FIRST)
    1. Go to GitHub.com ➔ Click your Profile Picture (top right) ➔ Settings.
    2. Click Emails on the left menu.
    3. Check the box: "Keep my email addresses private".
    4. Right below that checkbox, copy your fake privacy email (it looks like 12345678+username@://github.com).
    5. Open Git Bash on your PC and run these two commands (replace with your actual name and the fake email you           copied):
                          git config --global user.name "Your Username"
                          git config --global user.email "your-fake-email-here"
📂 PART 2: DOWNLOAD THE PROJECT
    Open Git Bash and run these commands one by one to download the project folder to your desktop:
    cd Desktop
    git clone https://github.com
    cd BSAI-1st-batch
🚀 PART 3: UPLOAD YOUR ASSIGNMENT
    The main folder is locked by the admin so we don't overwrite each other's work. You have to use a separate branch      to submit:
    1. Create your own side branch (replace your-name with your actual name):
    git checkout -b your-name-assignment
    2. Open the new BSAI-1st-batch folder on your computer's desktop using File Explorer. Navigate to:
    BSAI 3rd ➔ Computer Organization and Assembly Language ➔ Assignment ➔ Number system conversion.
    3. Drag and drop your files right inside that Number system conversion folder.
    4. Go back to Git Bash and run these three commands to save and upload your files:
    git add .
    git commit -m "Added my assignment files"
    git push origin your-name-assignment
    (If a Windows popup shows up asking you to log in, click "Sign in with your browser" and authorize it).
    5. Go to our repository link: github.com
    Click the green "Compare & pull request" button on the yellow bar at the top, then click "Create pull request".
    The admin will review your files and merge them into the main project folder. Let me know if anyone gets stuck! 👍
