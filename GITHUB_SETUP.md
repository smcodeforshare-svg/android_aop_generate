# How to Push MyBasicApp to GitHub

## Prerequisites
1. Install Git from https://git-scm.com/download/win
2. Create a new repository on GitHub (e.g., named "MyBasicApp")

## Steps to Push Code

### 1. Open Command Prompt or PowerShell
Navigate to the MyBasicApp folder:
```bash
cd d:\Soumen\git_ap_test\MyBasicApp
```

### 2. Initialize Git Repository
```bash
git init
```

### 3. Add All Files
```bash
git add .
```

### 4. Commit Files
```bash
git commit -m "Initial commit - Basic Android app with WebView"
```

### 5. Add Remote Repository
Replace `YOUR_USERNAME` with your GitHub username and `YOUR_REPO` with your repository name:
```bash
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
```

### 6. Push to GitHub
```bash
git branch -M main
git push -u origin main
```

## Alternative: Using GitHub Desktop
1. Download GitHub Desktop from https://desktop.github.com/
2. Open GitHub Desktop
3. File > Add Local Repository
4. Select the MyBasicApp folder
5. Click "Publish repository" to push to GitHub

## After Pushing to GitHub
You can set up GitHub Actions to automatically build the APK by adding a workflow file in `.github/workflows/build.yml`

## Notes
- Make sure you have a GitHub account
- Create the repository on GitHub first before pushing
- You may need to authenticate with GitHub (username/password or token)