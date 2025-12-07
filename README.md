<p align="center">
    
<img src="https://github.com/faroukbmiled/faroukbmiled/raw/main/img/ryuk.gif" height="300" style="width: 1200px; display: inline-block;" data-target="animated-image.originalImage">
</p>


<p align="center">
    <video src="https://github.com/faroukbmiled/faroukbmiled/raw/main/img/ryuk.gif" autoplay loop muted></video>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00BFFF&center=true&vCenter=true&width=800&lines=Full+Stack+Developer;Passionate+about+Web+%26+Mobile+Apps;Loves+Fancy+UI+%26+Colorful+Designs" />
</p>

---
###   sudo windsurf --no-sandbox --user-data-dir=/root/.windsurf
### 🚀 cmd of the day : du -xh / | sort -rh | head -n 20

- **Nom et prénom** : Touil Farouk  
- **Adresse** : Alger   
- **Mob** : 0799 16 27 46  
- **Adresse mail** : farouktouil@gmail.com  
 **Portofolio** :   touilfarouk.github.io
- **Poste occupé** : Technicien d'études
- **Formation** : CMP Opérateur Micro  
- **Principales qualifications** : Développeur full stack  
- **Stages et séminaires** : JavaScript, ReactJS  
- **Expérience Professionnelle** : 13 ans  
- **Maitrise des langues** :   English

- 💻 Full-stack developer mastering PHP, HTML, CSS, Bootstrap, JavaScript, jQuery, SQL Kotlin.
- 🎨 Loves fancy UI designs and animated elements.
- 🏗️ Currently working on Barrage Vert (Plate-form de suivie des traveaux).
- 📡 Exploring the Binance API for real-time crypto data.

---
```sh
git fetch --all
for branch in $(git branch -r | grep -v '\->' | sed 's/origin\///'); do
    git branch --track "$branch" "origin/$branch"
done
git pull --all
```

```sh
…or create a new repository on the command line

echo "# JavaGdxGames" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:touilfarouk/JavaGdxGames.git
git push -u origin main

…or push an existing repository from the command line

git remote add origin git@github.com:touilfarouk/JavaGdxGames.git
git branch -M main
git push -u origin main
```
```
1. Change the existing remote to point to the new repo
If you want this project to push to BnApp2 instead of BnApp, just rename the URL:
git remote set-url origin git@github.com:touilfarouk/BnApp2.git
Check:
git remote -vv
✅ 2. Add a second remote with a different name
If you want to keep the old repo and also push to a new one:
git remote add origin2 git@github.com:touilfarouk/BnApp2.git
Then push to the new repo:
git push origin2 main
```


```sh
1️⃣ Fetch all branches from remote
git fetch origin
2️⃣ List all remote branches
git branch -r
3️⃣ Check out a remote branch locally
git checkout -b signup-backend-flow origin/signup-backend-flow
4️⃣ Verify that you're on the correct branch
git branch
````
## Generate new SSH key 
```sh
ssh-keygen -t ed25519 -C "your_email@example.com"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519
cat ~/.ssh/id_ed25519.pub
Go to GitHub → Settings → SSH and GPG keys → New SSH key
Paste it there and save.
ssh -T git@github.com
````
## Another ssh key with other name
````
ssh-keygen -t ed25519 -C "another@hotmail.com" -f ~/.ssh/id_ed25519_another
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519_another
cat ~/.ssh/id_ed25519_another.pub
Go to GitHub → Settings → SSH and GPG keys → New SSH key
Paste it there and save.
ssh -T git@github.com
````
## 📜 Si Votre Xampp bloque

## xampp
````
cp -r /c/xampp/mysql/data /c/xampp/mysql/data_old && rm -r /c/xampp/mysql/data/mysql/ /c/xampp/mysql/data/performance_schema/ /c/xampp/mysql/data/phpmyadmin/ /c/xampp/mysql/data/test/ && find /c/xampp/mysql/backup/ -mindepth 1 -maxdepth 1 ! -name "ibdata1" -exec cp -r {} /c/xampp/mysql/data/ \;
````
# allow phpmyadmin remote access
````
C:\xampp\apache\conf\extra\httpd-xampp.conf
✅ Here is the full code block you must update inside that file:
🔍 FIND this section:
<Directory "C:/xampp/phpMyAdmin">
    AllowOverride AuthConfig
    Require local
</Directory>

✅ REPLACE IT WITH THIS (allow all remote access)
<Directory "C:/xampp/phpMyAdmin">
    AllowOverride AuthConfig
    Require all granted
</Directory>

````
# clean cache on ubuntu servers 
````
cd /var
cd cache/apt/
rm * -f
cd ../ #cash
rm -f *.gz && rm -f *.1

cd /var/log/
rm -f *.gz && rm -f *.1

cd /var/log/letsencrypt/
rm -f *.gz && rm -f *.1

cd /var/log/apache2
rm -f *.gz && rm -f *.1


````
### Get the latest Android 
````# Download the latest stable version for Linux
cd /tmp

# Download the build (you already have the link)
cd /tmp

# Download the build (you already have the link)
wget https://redirector.gvt1.com/edgedl/android/studio/ide-zips/2025.2.1.7/android-studio-2025.2.1.7-linux.tar.gz

# Backup existing installation
sudo mv /opt/android-studio /opt/android-studio-backup-$(date +%Y%m%d)

# Extract the new version
sudo tar -xzf android-studio-2025.2.1.7-linux.tar.gz -C /opt/

# Optionally rename for consistency
sudo mv /opt/android-studio-2025.2.1.7 /opt/android-studio

# Launch and verify version
/opt/android-studio/bin/studio.sh --version



````

### Install Jupiter book - flask server
````
python -m venv book
.\book\Scripts\activate # Windows 
python -m pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name=book
pip install --upgrade notebook
jupyter notebook


pip install flask
python -m http.server 8000

Then create a file server.py:

from flask import Flask

app = Flask(__name__)

@app.route('/')
def home():
    return "Hello, Flask Server!"

if __name__ == '__main__':
    app.run(debug=True, port=8000)

Run it with:

python server.py

````
### 🛠️ Tech Stack
````
   19  sudo truncate -s 0 /var/log/syslog /var/log/auth.log /var/log/kern.log /var/log/daemon.log /var/log/messages
   20  sudo find /var/log/apache2 -type f -exec truncate -s 0 {} \;
   21  sudo find /var/log/mysql -type f -exec truncate -s 0 {} \;
   22  sudo truncate -s 0 /var/log/apt/*log
   23  sudo find /var/log -type f -name "*.gz" -delete
   24  sudo find /var/log -type f -regex ".*\.[0-9]+" -delete
   25  sudo find /var/log -type f -exec truncate -s 0 {} \;
   26  sudo find /var/log -type f \( -name "*.gz" -o -regex ".*\.[0-9]+" \) -delete
   27  sudo find /var/log -type f -name "*.gz" -delete
   28  sudo find /var/log -type f -regex ".*\.[0-9]+" -delete
   29  sudo find /var/log -type f -exec truncate -s 0 {} \;
   30  sudo mysql -e "RESET QUERY CACHE;"
   31  sudo mysql -e "SET GLOBAL innodb_buffer_pool_size=innodb_buffer_pool_size;"
   32  sudo find /var/log -type f \( -name "*.gz" -o -regex ".*\.[0-9]+" \) -delete
   33  sudo truncate -s 0 /var/log/syslog /var/log/auth.log /var/log/kern.log /var/log/daemon.log /var/log/messages
   34  sudo find /var/log/apache2 -type f -exec truncate -s 0 {} \;
   35  sudo find /var/log/mysql -type f -exec truncate -s 0 {} \;
   36  sudo truncate -s 0 /var/log/apt/*log
   37  sudo find /var/log/apache2 -type f -exec truncate -s 0 {} \;
   38  sudo find /var/log/mysql -type f -exec truncate -s 0 {} \;
   39  sudo truncate -s 0 /var/log/apt/*log
````

<p align="center">
  <img src="https://skillicons.dev/icons?i=php,javascript,html,css,bootstrap,jquery,react,nodejs,mysql,sqlite" />
</p>

---
### if node js npm start does not work, put this in powershell 
````
 Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
````
### 📊 GitHub Stats & Streaks

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=touilfarouk&show_icons=true&theme=tokyonight&hide_border=true"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=touilfarouk&theme=tokyonight&hide_border=true"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=touilfarouk&layout=compact&theme=tokyonight&hide_border=true" />
</p>

---

### 📈 Contribution Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=touilfarouk&theme=github" />
</p>

---

### 💬 Let's Connect

<p align="center">
  <a href="https://www.linkedin.com/in/touilfarouk" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:touilfarouk@example.com"><img src="https://img.shields.io/badge/Email-red?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  
</p>
<p align="center">
    
<img src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" height="600" style="width: 1200px; display: inline-block;" data-target="animated-image.originalImage">
</p>
<p align="center">
Here’s a concrete plan to introduce cancel/resume controls for the resumable upload system:

Evaluate & prepare upload state
Extend 
DecisionFinanc.js
 state to track upload session metadata (e.g., uploadSessionId, isUploadPaused, isUploadCancelable).
Update 
uploadFileWithProgress
 to register the active XMLHttpRequest instance so it can be aborted on demand, and capture partial progress info (e.g., bytes uploaded) for resuming.
UI/UX updates in the dialog
In the inline progress zone (next to “Choisir un fichier”), add two buttons:
– “Annuler le téléversement” (severity danger, outlined) → aborts the current upload and resets progress.
– “Reprendre” (severity success) → currently shown only when a resume is possible (e.g., after interruption or manual cancel that supports resume).
Mirror the same controls in 
UploadProgressOverlay
 to keep parity when the global overlay is displayed.
Provide user feedback via toasts when canceling or resuming.
Resume/cancel handling logic
Implement handleCancelUpload to abort the stored XMLHttpRequest, clear progress, and set resumeInfo with the needed payload (file reference, uploaded bytes, resume URL/token).
Enhance 
handleResumeUpload
 to restart the upload from the saved offset; coordinate with backend support (e.g., include Content-Range headers or chunk index).
Ensure the backend (upload endpoint) accepts resumable/chunked requests: add parameters to indicate resume state and persist partial uploads, or fall back to re-upload if the server cannot resume.
Edge cases & validation
Disable the “Reprendre” button when no resume payload exists.
If the user cancels entirely (not resumable), clear pdf1 and prompt to reselect.
Handle dialog closure by cleaning up outstanding uploads to avoid orphaned requests.
QA checklist
Test cancel/resume for both add and edit dialogs.
Simulate network loss (XHR error) and verify resume button appears and succeeds.
Ensure deletion + reupload flows still respect the “PDF required” validation.
</p>
