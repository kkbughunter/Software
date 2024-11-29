# Software
- [ Burp Suit Pro ](https://github.com/KKBUGHUNTER/Software/blob/main/Burp-Suite.zip)
- [ MS Office 13 ](https://github.com/KKBUGHUNTER/Software/blob/main/MS-Office-13.zip)
- [ Oracle 11g Database - Lab Software](https://github.com/KKBUGHUNTER/Software/blob/main/oracle-DB-11g.zip)
- [Quartus](https://github.com/kkbughunter/Software/blob/main/90_quartus_free.exe)

## Steps to Upload Large Files to `GitHub`

#### Step 1: Install and Initialize Git LFS
Make sure Git LFS is installed and initialized. You’ve already run the following commands, but let’s verify them:
```bash
sudo apt-get update
sudo apt-get install git-lfs
git lfs install
```
#### Step 2: Track the Large File
Navigate to your repository’s directory and track the file with Git LFS:
```bash
git lfs track "file-name"
```
This command creates a `.gitattributes` file in your repository, telling Git LFS to handle the `Burp-Suite.zip` file.
#### Step 3: Add the .gitattributes File and Commit
Add the `.gitattributes` file to your repository:
```bash
git add .gitattributes
git commit -m "Track file-name with Git LFS"
```
#### Step 4: Add and Commit the Large File
Add the large file to the repository:
```bash
git add Burp-Suite.zip
git commit -m "Add file-name using Git LFS"
```
#### Step 5: Push to GitHub
Push the changes to GitHub:
```bash
git push origin main
```
