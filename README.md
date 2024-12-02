This repository uses Git Large File Storage (Git LFS) to manage large files (e.g., model files). Follow these steps to clone the repository properly:

### 1. Open a Terminal/Command Prompt

### 2. Install Git LFS:
#### **For Linux (Ubuntu/Debian):**
```bash
   sudo apt-get install git-lfs
```

#### **For macOS:**
```bash
  brew install git-lfs
```

#### **For Windows:**
```bash
  winget install -e --id GitHub.GitLFS
```

### 3.
```bash
  git lfs install
```
### 4. Create Local Clone of Repository
```bash
  git clone https://github.com/JordanCarden/MusicGenreClassifier.git
```

### 5. Open the Project Folder with VSCode
#### **For Linux (Ubuntu/Debian):**
```bash
   cd ~/MusicGenreClassifier
```
#### **For Windows:**
```bash
  cd %USERPROFILE%\MusicGenreClassifier
```
Launch VSCode
```bash
  code .
```

### 6. Create Virtual Environment and Install Dependencies
```bash
   python -m venv venv
```
or
```bash
   python3 -m venv venv
```

#### Activate Virtual Environment
#### **For Linux (Ubuntu/Debian):**
```bash
   source venv/bin/activate
```
#### **For Windows:**
```bash
  venv\Scripts\activate
```
#### Upgrade pip
```bash
   pip install --upgrade pip
```

#### Install Libraries
```bash
   pip install -r requirements.txt
```
