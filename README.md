Install Github CLI : brew install gh
Authenticate Github CLI : gh auth login
Create a New Repository : gh repo create <repository-name> --public
                        : gh repo clone <username>/<repository-name>
                        : cd <repository-name>
Install Jest : npm init -y
             : npm install jest --save-dev
Add Test : mkdir __tests__
         : touch __tests__/example.test.js
Create a github action workflow: .github/workflows/ci.yml 
Commit and Push the Changes : git add .
                              git commit -m "Initial project setup with Jest tests and GitHub Actions"
                              git push -u origin main
Workflow logs
Console Output for test pass and fail




