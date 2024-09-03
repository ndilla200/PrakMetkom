202408282040
Status:: #idea #publish
Tags:: [[P01 Dasar Dasar GIT]] [[MFG 1103 Praktikum Metode Komputasi]]

# Pengenalan Git & GitHub

## GIT Vs GITHUB

Sure! Let's break it down in simple terms.

### **Git**

Git is like a super-powered file organizer. Imagine you are writing a long essay, and you want to keep track of every change you make, like when you added a paragraph or fixed some mistakes. Git helps you do that. It keeps track of all the changes you make to your files over time, so you can always go back to an earlier version if you mess something up or just want to see what you changed.

### **GitHub**

GitHub is like a big online storage space for projects that use Git. It's where you can put your files after using Git to track your changes. But GitHub is more than just storage—it’s a place where people can share their projects with others, work together on the same files, and even contribute to projects made by people all over the world.

### **Difference**

- **Git** is a tool that you use on your computer to keep track of changes in your files.
- **GitHub** is a website where you can store and share the files you've tracked with Git, and collaborate with others.

In short, Git helps you manage and keep track of your work, while GitHub helps you share that work with others and collaborate on it.

## Similar to GitHub

Yes, there are several other websites similar to GitHub where you can store, share, and collaborate on projects using Git. Here are a few popular ones:

### **1. GitLab**

- **What it is:** GitLab is very similar to GitHub, offering tools for version control, project management, and collaboration. It’s popular for its built-in CI/CD (Continuous Integration/Continuous Deployment) features.
- **Why it's cool:** You can host your own GitLab server if you want, giving you full control over your projects.

### **2. Bitbucket**

- **What it is:** Bitbucket is another Git-based platform that allows teams to collaborate on code. It's closely integrated with other Atlassian products like Jira and Trello, which are popular in project management.
- **Why it's cool:** Bitbucket offers unlimited private repositories for small teams, which is great if you’re working on something that you don’t want to be public.

### **3. SourceForge**

- **What it is:** SourceForge is one of the oldest platforms for hosting open-source projects. It supports version control with Git and other systems like Subversion.
- **Why it's cool:** SourceForge has a large community of open-source projects, and it’s great for finding and collaborating on software.

### **4. AWS CodeCommit**

- **What it is:** AWS CodeCommit is a fully managed source control service hosted by Amazon Web Services. It works like GitHub but is integrated into the AWS ecosystem.
- **Why it's cool:** If you’re already using AWS for your projects, CodeCommit integrates seamlessly with other AWS tools.

### **5. GitKraken (GitKraken Boards)**

- **What it is:** GitKraken offers both Git tools and a Git hosting platform. It’s known for its user-friendly interface and integration with GitHub, GitLab, and Bitbucket.
- **Why it's cool:** GitKraken is particularly popular for its visual Git interface, which makes it easier to manage branches and commits.

Each of these platforms has its own strengths, so the best choice depends on your specific needs and how you want to manage and collaborate on your projects.

## Comparison Table

Here’s a comparison table between GitHub and five other similar services: GitLab, Bitbucket, SourceForge, AWS CodeCommit, and GitKraken.

| **Feature**                   | **GitHub**                                      | **GitLab**                                    | **Bitbucket**                                 | **SourceForge**                              | **AWS CodeCommit**                           | **GitKraken**                                  |
|-------------------------------|------------------------------------------------|-----------------------------------------------|-----------------------------------------------|----------------------------------------------|----------------------------------------------|------------------------------------------------|
| **Primary Use**               | Code hosting, collaboration, CI/CD             | Code hosting, CI/CD, DevOps                   | Code hosting, project management              | Open-source project hosting                  | Code hosting, integrated with AWS services    | Code hosting, Git GUI tool                     |
| **Hosting Options**           | Cloud-based                                    | Cloud-based or self-hosted                    | Cloud-based                                   | Cloud-based                                  | Cloud-based                                   | Cloud-based, integrates with other platforms   |
| **Version Control Systems**   | Git                                            | Git                                           | Git, Mercurial (limited support)              | Git, Subversion                              | Git                                           | Git                                             |
| **Free Private Repos**        | Yes, unlimited                                 | Yes, unlimited                                | Yes, unlimited (for small teams)              | Yes                                          | Yes                                           | Yes (limited with free tier)                    |
| **Integrated CI/CD**          | GitHub Actions                                 | Built-in CI/CD pipelines                      | Bitbucket Pipelines                           | No, requires third-party integration         | Integrated with AWS CodePipeline              | No, requires third-party integration            |
| **Project Management Tools**  | Basic (Issues, Projects, Wikis)                | Advanced (Issues, Boards, Milestones, Wikis)  | Integrated with Jira, Trello                  | Basic (Tickets, Discussion Forums, Wikis)    | Basic (Integrated with AWS tools)             | Basic (Integrates with GitHub, GitLab, etc.)    |
| **Self-Hosting**              | No                                             | Yes                                           | No                                            | No                                           | No                                            | No                                              |
| **Large Community**           | Yes, very large                                | Growing rapidly                               | Large                                         | Large, mostly open-source projects           | Smaller, primarily for AWS users              | Medium, popular for Git users                   |
| **Third-Party Integrations**  | Extensive (CI tools, IDEs, etc.)               | Extensive (CI tools, IDEs, monitoring, etc.)  | Extensive (Jira, Trello, Slack, CI tools)     | Limited                                       | Extensive (AWS ecosystem)                     | Extensive (IDE plugins, Git tools, CI tools)    |
| **Ease of Use**               | User-friendly, beginner-friendly               | Slightly steeper learning curve               | User-friendly, integrates well with Atlassian | More complex, suitable for open-source       | Easy if familiar with AWS, otherwise complex  | User-friendly GUI, good for visual learners     |
| **Security Features**         | 2FA, Dependabot, Code scanning                 | Advanced (2FA, code scanning, SAST/DAST)      | 2FA, IP whitelisting, branch permissions      | Basic security, limited to open-source tools | Strong integration with AWS security services | Basic (depends on platform integrations)        |

### **Key Takeaways:**

- **GitHub** is the most popular platform with a vast community and easy-to-use features, making it great for open-source and collaborative projects.
- **GitLab** offers robust CI/CD and DevOps features, along with self-hosting options for more control.
- **Bitbucket** is well-integrated with Atlassian tools like Jira, making it a good choice for teams already using those products.
- **SourceForge** is focused on open-source projects with support for older version control systems like Subversion.
- **AWS CodeCommit** is best suited for projects deeply integrated with AWS, offering strong security and scalability.
- **GitKraken** provides a unique Git GUI experience, simplifying Git workflows and integrating with other platforms like GitHub and GitLab.

## Common GIT Commands in Small Project

Here’s a table of common Git commands that are essential for collaborating on a simple project with a small team:

| **Command**                    | **Description**                                                                                  | **Example Usage**                          |
|--------------------------------|--------------------------------------------------------------------------------------------------|--------------------------------------------|
| `git init`                     | Initializes a new Git repository in your project directory.                                       | `git init`                                 |
| `git clone <repository-url>`   | Clones an existing repository from a remote server to your local machine.                        | `git clone https://github.com/user/repo.git` |
| `git status`                   | Displays the state of the working directory and staging area, showing changes that are staged, untracked, or need committing. | `git status`                               |
| `git add <file>`               | Stages a specific file or files for the next commit.                                              | `git add filename.txt`                     |
| `git add.`                    | Stages all changes (new, modified, or deleted files) in the current directory for the next commit. | `git add.`                                |
| `git commit -m "<message>"`    | Commits the staged changes to the repository with a descriptive message.                          | `git commit -m "Add new feature"`          |
| `git push`                     | Uploads the local commits to the remote repository (e.g., GitHub, GitLab).                        | `git push`                                 |
| `git pull`                     | Fetches and merges changes from the remote repository into the current branch.                   | `git pull`                                 |
| `git branch`                   | Lists all local branches in the repository.                                                      | `git branch`                               |
| `git branch <branch-name>`     | Creates a new branch with the specified name.                                                    | `git branch feature-branch`                |
| `git checkout <branch-name>`   | Switches to the specified branch.                                                                | `git checkout feature-branch`              |
| `git merge <branch-name>`      | Merges the specified branch into the current branch.                                             | `git merge feature-branch`                 |
| `git remote add <name> <url>`  | Adds a new remote repository with a specified name (e.g., origin) and URL.                       | `git remote add origin https://github.com/user/repo.git` |
| `git fetch`                    | Downloads objects and refs from another repository, but doesn’t merge them into your current branch. | `git fetch`                               |
| `git log`                      | Shows the commit history for the current branch.                                                  | `git log`                                  |
| `git diff`                     | Displays the differences between the working directory and the staging area or between commits.  | `git diff`                                 |
| `git reset <file>`             | Unstages a file that has been added to the staging area.                                          | `git reset filename.txt`                   |
| `git stash`                    | Temporarily saves changes that you don’t want to commit right away, allowing you to work on other things. | `git stash`                           |
| `git stash pop`                | Applies the most recent stashed changes and removes them from the stash list.                    | `git stash pop`                            |
| `git rebase <branch-name>`     | Reapplies commits on top of another base tip, often used to keep a feature branch up to date with the main branch. | `git rebase main`            |

### **Key Commands for Collaboration:**

- **`git clone`**: To start working on the project by copying it to your local machine.
- **`git pull`**: To get the latest changes from the remote repository.
- **`git add`** + **`git commit`** + **`git push`**: The workflow to save changes and share them with your team.
- **`git branch`** + **`git checkout`**: To work on different features or fixes in parallel.
- **`git merge`**: To combine changes from different branches.
- **`git stash`**: To temporarily save changes when you need to switch contexts without committing.

These commands cover most of the basics you’ll need to effectively collaborate on a Git project with a small team.

## Using `tag`

To create a Git commit with a tag, you’ll follow these steps:

1. **Make Changes**: First, make some changes to your files and stage them.
2. **Commit the Changes**: Commit those changes with a descriptive message.
3. **Create a Tag**: Add a tag to that commit.

Here’s how you can do it:

### **Step-by-Step Example**

1. **Stage your changes:**

   ```bash
   git add .
   ```

2. **Commit the changes:**

   ```bash
   git commit -m "Add feature X to improve performance"
   ```

3. **Create a tag:**

   ```bash
   git tag -a v1.0.0 -m "Release version 1.0.0"
   ```

   - `-a v1.0.0`: This creates an annotated tag named `v1.0.0`.
   - `-m "Release version 1.0.0"`: This adds a message to the tag, describing what it represents.

4. **Push the commit and tag to the remote repository:**

   ```bash
   git push origin main
   git push origin v1.0.0
   ```

   - `git push origin main`: Pushes your commits to the `main` branch.
   - `git push origin v1.0.0`: Pushes the `v1.0.0` tag to the remote repository.

### **Explanation:**

- **Commit Message**: `"Add feature X to improve performance"` is your commit message, describing what the commit does.
- **Tag**: `v1.0.0` is a version tag, typically used to mark a release or a significant point in the project’s history.

### **Checking Your Tag**

To see the tags in your repository, you can use:

```bash
git tag
```

If you want to see details about a specific tag:

```bash
git show v1.0.0
```

This workflow is commonly used when you want to mark specific commits as releases or milestones in your project.

## Setup and Configuration

To start using Git and GitHub, here’s a guide on the minimal requirements and setup steps:

### **1. Install Git**

First, you need to install Git on your computer.

#### **For Windows:**

- Download Git from the [official Git website](https://git-scm.com/download/win).
- Run the installer and follow the default options. This will install Git Bash, a command-line interface, which you’ll use to run Git commands.

#### **For macOS:**

- Open the Terminal application.
- Install Git by running:

  ```bash
  git --version
  ```

  If Git isn’t installed, it will prompt you to install it via Xcode Command Line Tools. Follow the prompts to complete the installation.

#### **For Linux:**

- Open your terminal and run the following command, depending on your distribution:

  ```bash
  sudo apt-get install git         # For Ubuntu/Debian
  sudo yum install git             # For CentOS/Fedora
  ```

### **2. Configure Git**

After installing Git, you need to configure it with your name and email, which will be associated with your commits.

```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```

### **3. Create a GitHub Account**

If you don’t already have one, sign up for a free account on [GitHub](https://github.com/).

### **4. Set Up SSH Keys (Optional but Recommended)**

SSH keys allow you to connect to GitHub without entering your password every time you push or pull changes.

#### **Generate An SSH Key:**

1. Open your terminal and run:

   ```bash
   ssh-keygen -t ed25519 -C "youremail@example.com"
   ```

   - Use `ed25519` for the key type, which is more secure and faster.
   - When prompted, you can press `Enter` to accept the default file location and skip the passphrase by pressing `Enter` again.

2. Add the SSH key to your SSH agent:

   ```bash
   eval "$(ssh-agent -s)"
   ssh-add ~/.ssh/id_ed25519
   ```

3. Copy the SSH key to your clipboard:

   ```bash
   cat ~/.ssh/id_ed25519.pub
   ```

   Copy the output, which is your public key.

4. Add the SSH key to your GitHub account:
   - Go to your GitHub account, navigate to **Settings** > **SSH and GPG keys** > **New SSH key**.
   - Paste your key into the "Key" field and give it a title, then click **Add SSH key**.

### **5. Create or Clone a Repository**

Now, you can create a new repository on GitHub or clone an existing one.

#### **To Create a New Repository:**

1. Go to [GitHub](https://github.com/) and log in.
2. Click the **+** in the top-right corner and select **New repository**.
3. Fill in the repository name and details, then click **Create repository**.
4. Follow the instructions to either create a new repository locally or push an existing repository to GitHub.

#### **To Clone an Existing Repository:**

1. Find the repository you want to clone on GitHub.
2. Click the **Code** button and copy the SSH or HTTPS URL.
3. In your terminal, navigate to where you want to store the project and run:

   ```bash
   git clone <repository-url>
   ```

### **6. Basic Git Workflow**

With your repository set up, you can now use Git to manage your project:

- **Stage Changes**: `git add.`
- **Commit Changes**: `git commit -m "Your commit message"`
- **Push to GitHub**: `git push`

This minimal setup will allow you to start using Git for version control and GitHub for collaboration and remote storage.

## Scenario: Local to GitHub

The `git remote add origin` command is used to add a remote repository (usually on a platform like GitHub) to your local Git repository. This allows you to push and pull changes between your local machine and the remote server.

Here’s a step-by-step example:

### **Scenario**

Imagine you’ve just created a new project locally and want to link it to a new GitHub repository.

### **1. Create a New Local Git Repository**

First, navigate to your project directory and initialize a Git repository.

```bash
cd /path/to/your/project
git init
```

### **2. Create a Repository on GitHub**

- Go to [GitHub](https://github.com/) and log in.
- Click on the **+** icon in the top-right corner and select **New repository**.
- Name your repository, optionally add a description, and choose whether it will be public or private.
- Do **not** initialize the repository with a README,.gitignore, or license (you’ll add those locally).
- Click **Create repository**.

### **3. Link Your Local Repository to GitHub**

Once your GitHub repository is created, you’ll be provided with a URL. It will look something like this:

```plaintext
https://github.com/yourusername/your-repo.git
```

Now, you need to add this URL as a remote in your local Git repository.

In your terminal, run:

```bash
git remote add origin https://github.com/yourusername/your-repo.git
```

### **4. Verify the Remote**

You can check if the remote was added correctly by running:

```bash
git remote -v
```

This should display something like:

```plaintext
origin  https://github.com/yourusername/your-repo.git (fetch)
origin  https://github.com/yourusername/your-repo.git (push)
```

### **5. Push Your Local Changes to GitHub**

If you haven’t committed anything yet, make a commit first:

```bash
git add .
git commit -m "Initial commit"
```

Then, push your changes to the remote repository on GitHub:

```bash
git push -u origin main
```

- The `-u` flag sets the upstream for the `main` branch, so future `git push` commands will know where to push by default.
- Replace `main` with `master` if your default branch is named `master`.

### **Summary**

- **`git remote add origin <url>`**: Links your local repository to a remote one.
- **`git push -u origin main`**: Pushes your commits to GitHub and sets the `origin` as the default remote for future pushes.

---

# References
