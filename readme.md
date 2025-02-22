# How to use Git and GitHub

Follow these simple steps to set up Git and push your project to GitHub.

## 1. Initialize Git in Your Project (Install Git First)
```bash
git init
```
This creates a `.git` folder, turning your project into a Git repository.

## 2. Add Files to Git
```bash
git add filename.filextension

for multiple files 
git add .
```
This stages `filename.filextension` for the next commit.

## 3. Git Status
``` bash
git status
```
This checks the current state of your working directory and staging area

## 4. Commit the Changes
```bash
git commit -m "Your commit message"
```
This saves your changes with a message.

## 5. Connect to GitHub
1. Go to [GitHub](https://github.com/) and create a new repository.
2. Copy the repository URL.

Now, link your local repo to GitHub:
```bash
git remote add origin https://github.com/your-username/sample-repository.git
```

## 6. Push Your Code to GitHub
```bash
git checkout -b branchname
git push -u origin branchname
```

## 7. Add and Commit Changes
```bash
git add filename.filextension

for multiple files 
git add .

then do
git commit -m "Your Message"

finally push it to your branch
git push origin main
```

### Done! 🎉 Your project is now on GitHub.
Happy coding! 🚀
