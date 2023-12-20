**Step 1: Prerequisites**
- Install Python 3 and pip3 locally.
 
**Step 2: Install MkDocs and MkDocs Material**
```bash
pip3 install mkdocs mkdocs-material
```
 
**Step 3: Clone the Repository**

 
**Step 4: Make Changes**
- Edit the markdown files (`*.md`) in the "docs" directory.
- Update the `mkdocs.yml` file if needed.
 
**Step 5: Build and Test Locally**
```bash
mkdocs build
mkdocs serve
```
Access the documentation locally at http://127.0.0.1:8000/ to verify changes.
 
**Step 6: Commit and Push Changes**
```bash
git add .
git commit -m 'Updated documentation'
git push origin master
```
 
**Step 7: Deploy to GitHub Pages**
```bash
mkdocs gh-deploy
```
 
**Step 8: Access Live Documentation**
Visit the live documentation on GitHub Pages.
