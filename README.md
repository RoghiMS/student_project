# Student Project

## Description

This repository contains a simple Python project created as part of a Data Engineering course to practice Git and GitHub.

The main purpose of this project is to learn and demonstrate the basic Git and GitHub workflow, including creating a repository, making commits, working with branches, pushing and pulling changes, cloning a repository, merging branches, and resolving merge conflicts.

The project was developed and modified through several stages to demonstrate how Git can be used to track changes and manage different versions of a project.

## How to Run

### Requirements

* Python 3.x
* Git
* A terminal such as Git Bash
* Visual Studio Code or another code editor (optional)

### Running the Project

1. Clone the repository:

```bash
git clone git@github.com:RoghiMS/student_project.git
```

2. Move into the project directory:

```bash
cd student_project
```

3. Run the main Python file:

```bash
python main.py
```

If the `python` command is not available on the system, the following command can be used on some Windows systems:

```bash
py main.py
```

## Git Concepts Used

The following Git and GitHub concepts were practiced in this project:

### 1. Repository

A Git repository was created to manage and track the project files and their changes.

### 2. Commit

Changes were saved as separate commits with meaningful commit messages. This allows the history of the project to be reviewed and previous changes to be tracked.

### 3. Remote Repository

The local repository was connected to a GitHub repository named `student_project` using the remote name `origin`.

### 4. Push

Local commits were pushed to GitHub so that the changes could be stored and shared in the remote repository.

### 5. Pull

Changes made in the GitHub repository were retrieved to the local repository using `git pull`.

### 6. Branching

A separate branch named `feature/student-info` was created to practice working on a feature independently from the `master` branch.

### 7. Upstream Branch

The local `feature/student-info` branch was connected to its corresponding remote branch on GitHub using an upstream configuration.

### 8. Clone

The GitHub repository was cloned into a second local directory named `student_project_copy` to practice working with an existing remote repository.

### 9. Merge

Changes from another branch were merged into the `master` branch.

### 10. Merge Conflict

A merge conflict was intentionally created by modifying the same section of `README.md` differently in two branches.

The conflict was then resolved manually by editing `README.md`, removing the conflict markers, keeping the required final content, staging the resolved file, and creating a merge commit.

### 11. GitHub Authentication

GitHub authentication was practiced using both HTTPS with a Personal Access Token (PAT) and SSH authentication.

An SSH key pair was generated, the public key was added to GitHub, the SSH connection was tested successfully, and the repository remote was changed from HTTPS to SSH.

## Author

RoghiMS

Data Engineering Course
