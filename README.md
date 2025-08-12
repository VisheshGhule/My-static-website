# Static Website Hosting with GitHub Pages

- This project demonstrates how to host a simple static HTML website for free using **GitHub Pages**.

## 📌 Objective
Deploy a simple HTML page and make it accessible online using GitHub Pages.

### Step 1: Create index.html
   - Write your HTML code and save it as `index.html`.

### Step 2: Push the file to a new GitHub repository
- Go to github.com and login to your account.
- Click on New repository.
- Give your repository a name (e.g., my-static-website).
- Set it as Public.
- Click Create repository.

Now, push your index.html file to this repo:

- Open terminal/command prompt on your computer.
- Navigate to the folder where index.html is saved.
- Run these commands:
```bash
git init
git add index.html
git commit -m "Add index.html"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo-name>.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
- Go to your GitHub repo page.
- Click on Settings tab.
- Scroll down and click on Pages in the left sidebar or find it in the main Settings page.
- Under Source, select the branch: main.
- Select the folder: root ( / ).
- Click Save or Save/Deploy.

<br>

  <img width="1000" height="500" alt="ee74788c-453f-434d-9dc3-c68db8573ab5" src="https://github.com/user-attachments/assets/eb30bf80-0fef-4fbf-9fa2-281a17362097" />

  ### Step 4: Access your live website
- After a few seconds or minutes, GitHub will provide a link like:
```bash
https://<your-username>.github.io/<your-repo-name>/
```
- Open that link in a browser to see your static website live.
<img width="600" height="150" alt="Screenshot from 2025-08-12 10-47-54" src="https://github.com/user-attachments/assets/a043060f-6b7a-48b5-a5a5-541bafb3ddd1" />

<br>

### Step 5: Customize with CSS 
- Add ``.css`` file or add inline styles inside your index.html to style your page.

<img width="1000" height="500" alt="c616934e-4b0f-4d95-97a5-a3bfcdae1445" src="https://github.com/user-attachments/assets/2c60141f-dd44-4a31-9aef-1cdbc2416fb3" />
<br><br>
<img width="600" height="180" alt="Screenshot from 2025-08-12 11-01-04" src="https://github.com/user-attachments/assets/885d5e38-b7ec-451d-8a4d-8031665693cd" />

