# scbi-frontend
a React frontend for my SimCity BuildIt helper app

# technologies used
* HTML
* Bootstrap v5.3
* GitHub 
* GitHub Actions (for CI/CD)
* SSH (for version control & deployment)
* Hostinger (for hosting)

# cicd pipeline
1. a GitHub Action is triggered when commits are pushed to `main`. 
2. an FTP connection is established with a Hostinger server
3. the code is uploaded to the directory (i.e. `public_html/scbi`)
