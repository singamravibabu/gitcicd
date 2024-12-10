# **Day 1: Basics of Version Control**

---

#### **1. Definition and Importance of Version Control**  

**What is Version Control?**  
Version Control is a system that helps track changes to files, typically source code, over time. It allows multiple people to collaborate on a project while keeping a history of changes, enabling easy reversions if needed.

**Key Benefits of Version Control:**  
- **Collaboration:** Multiple team members can work on the same project without overwriting each other's work.  
- **Change History:** Keeps a detailed log of all changes, who made them, and why.  
- **Backup and Recovery:** If something goes wrong, you can roll back to a stable version.  
- **Experimentation:** Developers can create branches to test new ideas without affecting the main project.  

---

#### **2. History of Git and Introduction to GitHub**

**The History of Git:**  
- Git was created in 2005 by **Linus Torvalds**, the creator of Linux, to manage the Linux kernel's development.  
- It was designed to be fast, distributed, and capable of handling large projects efficiently.  
- Unlike centralized version control systems (e.g., Subversion), Git enables each developer to have a complete local copy of the repository.  

**Introduction to GitHub:**  
- GitHub is a cloud-based platform that allows developers to host and manage Git repositories.  
- It adds collaboration features like **pull requests**, **issue tracking**, and **project management tools**.  
- GitHub integrates seamlessly with Git, making it a preferred choice for individual developers and teams alike.

---

#### **3. Installing Git and Creating a GitHub Account**

**Step 1: Install Git**  
- Visit the [Git Downloads Page](https://git-scm.com/downloads) and choose the appropriate version for your operating system.  
- Follow the installation instructions for your platform:  
  - **Windows:** Run the installer and choose default settings unless specific changes are required.  
  - **macOS:** Use Homebrew (`brew install git`) or download the installer.  
  - **Linux:** Use your package manager, e.g., `sudo apt-get install git` for Ubuntu.  

**Step 2: Verify Installation**  
- Open your terminal (or Git Bash for Windows).  
- Run the following command to check the installed version:  
  ```bash
  git --version
  ```  

**Step 3: Set Up Git Configuration**  
- Configure your name and email for Git:  
  ```bash
  git config --global user.name "Your Name"
  git config --global user.email "youremail@example.com"
  ```  

**Step 4: Create a GitHub Account**  
1. Go to [GitHub's Signup Page](https://github.com/join).  
2. Enter your details (username, email, and password) and click **Sign up for GitHub**.  
3. Verify your email address to activate your account.  

**Step 5: Install GitHub CLI (Optional)**  
- GitHub CLI simplifies interactions with GitHub from the terminal. Install it from [GitHub CLI Documentation](https://cli.github.com/).  

---

### **Hands-On Exercise: Your First GitHub Repository**

1. **Create a Repository:**  
   - Go to GitHub and click on **New Repository**.  
   - Give it a name (e.g., "version-control-basics") and choose "Public" or "Private."  
   - Click **Create Repository.**  

2. **Clone the Repository Locally:**  
   - Copy the repository's URL and run:  
     ```bash
     git clone <repository_url>
     ```  

3. **Add a File:**  
   - Navigate to the cloned directory and create a file (e.g., `hello.txt`).  
   - Add some text to the file and save it.  

4. **Commit the File:**  
   ```bash
   git add hello.txt
   git commit -m "Initial commit: Added hello.txt"
   ```  

5. **Push Changes to GitHub:**  
   ```bash
   git push origin main
   ```  

Now your changes are live on GitHub! 🎉  

---

### **Homework:**  
1. Research how GitHub differs from other version control platforms like Bitbucket and GitLab.  
2. Write down at least three reasons why version control is critical for collaboration.  
3. Explore the GitHub interface and create your first issue in the repository.