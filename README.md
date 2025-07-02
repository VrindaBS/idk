# idk

1. git init
2. git remote add origin https://github.com/YourUsername/your-repo-name.git
3. git add .
4. git commit -m "first commit"
5. git branch -m main
6. git push -u origin main
      OR
1. git init
2. git remote add origin https://github.com/YourUsername/your-repo-name.git
3. git add .
4. git commit -m "first commit"
5. git push -u origin master:main

git config --global user.name "Your Full Name"
git config --global user.email "your.email@example.com"

git config --list

🔧 How to Set It Up (One Time)
✅ Step 1: Generate a PAT
Go to: https://github.com/settings/tokens

Click "Generate new token (classic)" or "Fine-grained token" (either works)

Select scopes:

repo (for access to your repos)

Set an expiration (e.g., 30 days or custom)

Click Generate token

Copy the token immediately and keep it safe!

Step 2: Push Your Code (First Time Only)
When you run:

bash
Copy
Edit
git push origin main
Git will prompt:

Username: → enter your GitHub username

Password: → paste the token you just generated

✅ If you used git config --global credential.helper store, it will remember the token so you don’t have to enter it again.



1. git credential-manager clear
2. git config --global user.name "Your Name"
3. git config --global user.email "your.email@example.com"

