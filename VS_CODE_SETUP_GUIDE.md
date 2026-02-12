# 💻 VS Code Setup Guide (Step-by-Step)

Follow these steps to connect your assigned GitHub repository to VS Code.

---

## Step 1: Install Required Tools

Make sure you have:

- Git installed → https://git-scm.com/
- Visual Studio Code installed → https://code.visualstudio.com/

---

## Step 2: Accept Repository Invitation

1. Open your email.
2. Accept the GitHub repository invitation.
3. Verify that you can see your assigned repository.

---

## Step 3: Copy Repository URL

1. Go to your assigned repository.
2. Click the green "Code" button.
3. Copy the HTTPS URL.

Example:
https://github.com/organization-name/repository-name.git

---

## Step 4: Clone Repository in VS Code

### Option A: Using VS Code UI

1. Open VS Code.
2. Press `Ctrl + Shift + P`
3. Type: `Git: Clone`
4. Paste the repository URL.
5. Select a local folder.
6. Open the cloned repository.

---

### Option B: Using Terminal

Open terminal and run:

git clone https://github.com/organization-name/repository-name.git

Then:

cd repository-name
code .

---

## Step 5: Start Working

- Create project files.
- Make changes.
- Save files.

---

## Step 6: Commit and Push Changes

Inside VS Code:

1. Go to Source Control tab.
2. Stage changes.
3. Write a clear commit message.
4. Click "Commit".
5. Click "Push".

OR using terminal:

git add .
git commit -m "Initial commit"
git push

---

## Important Reminders

- Push your work regularly.
- Do NOT force push.
- Ensure your final commit is pushed before deadline.
