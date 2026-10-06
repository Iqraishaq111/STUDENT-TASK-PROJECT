
# Student Task Management Application

## Project Description

The **Student Task Manager** is a simple yet functional web application designed to help users manage their daily tasks efficiently. The application allows users to add tasks with titles and descriptions, view all tasks, mark tasks as completed, delete unwanted tasks, and search through their task list. 

This project was developed as a collaborative pair-based assignment to demonstrate real-world Git and GitHub workflows, including branching, pull requests, code reviews, and conflict resolution.

---

## Team Members

| Role | Name | Roll No. | GitHub Profile |
|------|------|----------|---|
| Student 1 | Sumaiya Naumaan | MSDSF26M021 | [GitHub Profile](https://github.com/sumaiyanaumaan9536) |
| Student 2 | Iqra Ishaq | MSDSF26M022 | [GitHub Profile](https://github.com/Iqraishaq111) |

---

## Features

✅ **Add Tasks** - Create new tasks with title and description  
✅ **Display Tasks** - View all tasks in an organized list format  
✅ **Mark as Completed** - Toggle task completion status  
✅ **Delete Tasks** - Remove tasks from the list  
✅ **Search Tasks** - Find specific tasks quickly  
✅ **Responsive Design** - Mobile-friendly interface  
✅ **Task Status Tracking** - Visual indication of completed tasks  

---

## Technologies Used

- **Frontend**
  - HTML5 - Semantic markup structure
  - CSS3 - Styling and responsive layout
  - JavaScript (ES6+) - Task management logic

- **Version Control**
  - Git - Local repository management
  - GitHub - Remote repository and collaboration

- **Development Tools**
  - Git CLI commands
  - GitHub Issues for task tracking
  - GitHub Pull Requests for code review

---

## Git Workflow Demonstrated

### Initial Setup
1. **Git Installation & Configuration** - Verify Git installation and configure user identity
2. **Repository Initialization** - Create local Git repository with `git init`
3. **Initial Commit** - Staged project files and created first meaningful commit

### Branching & Feature Development
4. **Feature Branches** - Created separate branches for different features:
   - `feature/task-form` - Task input form implementation
   - `feature/task-style` - Styling and responsive design
   - `feature/task-search` - Task search functionality

5. **Branch Management**
   - Create and switch branches using `git switch -c`
   - Push branches to remote using `git push -u origin <branch-name>`
   - Maintain clean branch history

### Collaboration & Code Review
6. **Pull Requests** - Created multiple PRs for peer review
7. **Code Review** - Partners reviewed each other's code with constructive comments
8. **Merging** - Merged reviewed and approved pull requests into main branch

### Conflict Resolution
9. **Merge Conflicts** - Intentionally created and resolved merge conflicts
   - Edited conflicting sections collaboratively
   - Removed conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`)
   - Completed merge after discussion

### Git Recovery & History Management
10. **Git Stash** - Temporarily stored uncommitted work
11. **Git Restore** - Discarded unwanted uncommitted changes
12. **Git Reset** - Moved HEAD and reset staging area (soft reset)
13. **Git Revert** - Created new commit to reverse previous changes

### Versioning
14. **Git Tags** - Created version tag `v1.0.0`
15. **GitHub Release** - Published release with version notes

---

## Branches Used

| Branch | Purpose | Developer |
|--------|---------|-----------|
| `main` | Production-ready code | Both |
| `feature/task-form` | Task input form implementation | Student 1 |
| `feature/task-style` | CSS styling and responsive design | Student 2 |
| `feature/task-search` | Search functionality implementation | Feature branch |

---

## Git Commands Demonstrated

### Core Commands
| Command | Purpose |
|---------|---------|
| `git init` | Initialize local repository |
| `git status` | Check working tree status |
| `git add .` | Stage all changes |
| `git commit -m "message"` | Create snapshot in history |
| `git log --oneline --graph` | View commit history |

### Branching Commands
| Command | Purpose |
|---------|---------|
| `git branch` | List branches |
| `git switch -c <branch>` | Create and switch to branch |
| `git switch <branch>` | Switch to existing branch |
| `git merge <branch>` | Merge branch into current branch |

### Remote Commands
| Command | Purpose |
|---------|---------|
| `git remote add origin <URL>` | Add remote repository |
| `git remote -v` | View remote URLs |
| `git push -u origin <branch>` | Push branch to remote |
| `git pull origin <branch>` | Fetch and integrate changes |
| `git clone <URL>` | Clone remote repository |

### Recovery Commands
| Command | Purpose |
|---------|---------|
| `git stash` | Temporarily save work |
| `git stash pop` | Restore stashed work |
| `git restore <file>` | Discard changes in file |
| `git reset --soft HEAD~1` | Undo commit, keep changes staged |
| `git revert <commit-hash>` | Create new commit reversing changes |

### Tag & Release
| Command | Purpose |
|---------|---------|
| `git tag v1.0.0` | Create version tag |
| `git push --tags` | Push tags to remote |

---

## GitHub Features Demonstrated

✅ **GitHub Repository** - Created public repository for collaboration  
✅ **Pull Requests** - Created and merged multiple PRs  
✅ **Code Review** - Peer review with comments and approvals  
✅ **Issues** - Created GitHub Issues for feature tracking  
✅ **Issue Linking** - Linked PRs to issues with "Closes #<number>"  
✅ **Auto-close** - Issues automatically closed when PR merged  
✅ **Branch Protection** - Controlled merges through PR review  
✅ **Releases** - Created GitHub Release with v1.0.0  
✅ **Contributor Stats** - Track contributions from both team members  

---

## How to Run

### Prerequisites
- Git installed on your system
- Modern web browser (Chrome, Firefox, Safari, Edge)

### Installation Steps

```bash
# 1. Clone the repository
git clone https://github.com/Iqraishaq111/STUDENT-TASK-PROJECT.git

# 2. Navigate to project directory
cd STUDENT-TASK-PROJECT

# 3. Open in browser
# Simply open index.html in your web browser:
# Double-click index.html or right-click → Open with Browser
```

### Using the Application

1. **Add a Task**
   - Enter task title in the input field
   - Enter task description
   - Click "Add Task" button

2. **View Tasks**
   - All tasks appear in the task list below
   - Each task shows title, description, and status

3. **Mark as Completed**
   - Click the checkbox next to a task to mark it complete
   - Completed tasks appear with a strikethrough style

4. **Delete a Task**
   - Click the delete button (trash icon) next to a task
   - Task will be removed from the list

5. **Search Tasks**
   - Use the search box to filter tasks by title
   - Results update in real-time

---

## Version History

### v1.0.0 (Current Release)
- ✨ Initial stable release
- ✅ All core features implemented
- ✅ Responsive design completed
- ✅ Search functionality added
- 📝 Full documentation

### Development Timeline
- **Initial Setup** - Git initialization and project structure
- **Phase 1** - Task form implementation (Student 1)
- **Phase 2** - Styling and responsive design (Student 2)
- **Phase 3** - Search functionality and bug fixes
- **Phase 4** - Final testing and v1.0.0 release

---

## Project Structure

```
STUDENT-TASK-PROJECT/
├── index.html          # Main HTML structure
├── style.css          # Styling and responsive design
├── script.js          # JavaScript functionality
├── README.md          # Project documentation
└── .git               # Git repository
```

### File Descriptions

- **index.html** - Contains the application structure with task input form and task display area
- **style.css** - Provides styling for layout, buttons, task cards, and responsive mobile design
- **script.js** - Implements task management logic (add, delete, search, mark complete)
- **README.md** - Complete project documentation

---

## Key Learning Outcomes

### Git Concepts Mastered
- Working Directory vs Staging Area vs Local Repository vs Remote Repository
- Commit lifecycle and meaningful commit messages
- Branch creation, switching, and merging
- Pull requests and code review workflow
- Merge conflict creation, detection, and resolution

### GitHub Collaboration Skills
- Repository initialization and remote connection
- Feature branch workflow for parallel development
- Pull request management and code review process
- Issue tracking and linking to PRs
- Release management and version tagging

### Best Practices Implemented
- ✅ Meaningful commit messages (not "update", "final", etc.)
- ✅ Regular commits after each feature
- ✅ Feature branches for isolated development
- ✅ Code review before merging
- ✅ Descriptive pull request descriptions
- ✅ Clear issue descriptions with acceptance criteria

---

## Challenges & Solutions

### Challenge 1: Merge Conflicts
**Problem:** Both students modified README.md simultaneously causing conflicts  
**Solution:** Communicated and discussed desired changes, resolved markers manually, tested before final commit

### Challenge 2: Branch Synchronization
**Problem:** One team member's local main was out of sync with remote  
**Solution:** Used `git pull origin main` to fetch and integrate latest changes

### Challenge 3: Staging Area Confusion
**Problem:** Accidentally staged unwanted files  
**Solution:** Used `git restore --staged <file>` to unstage specific files

---

## Commit Message Guidelines

All commits followed these guidelines:

✅ **Good Examples**
- "Initial project setup"
- "Add task input form"
- "Add task manager styling"
- "Implement task creation"
- "Implement task deletion"
- "Add task completion"
- "Add task search"
- "Prepare version 1.0 release"

❌ **Avoided Examples**
- "changes", "update", "final"
- "abc", "test", "work"
- "new", "fix", "random"

---

## Contributors

This project was developed through collaborative effort:

| Contributor | Contributions | Commits |
|-------------|---|---|
| Sumaiya Naumaan (MSDSF26M021) | Project setup, Task form, Issue management | Multiple |
| Iqra Ishaq (MSDSF26M022) | Styling, Responsive design, Feature implementation | Multiple |

### Contribution Areas
- **Student 1 (Sumaiya):** Project initialization, feature/task-form branch, first PR review
- **Student 2 (Iqra):** Repository connection, feature/task-style branch, styling enhancements
- **Both:** Merge conflict resolution, Git command demonstration, pull request reviews

---

## Testing & Quality Assurance

- ✅ All features tested in multiple browsers
- ✅ Responsive design verified on mobile devices
- ✅ Search functionality tested with various inputs
- ✅ Cross-browser compatibility confirmed
- ✅ Code reviewed by partner before merge

---

## GitHub Repository

**Repository URL:** https://github.com/Iqraishaq111/STUDENT-TASK-PROJECT

**Status:** Public repository (maintained for grading purposes)

---

## References & Resources

### Git Documentation
- [Git Official Documentation](https://git-scm.com/doc)
- [Pro Git Book](https://git-scm.com/book)

### GitHub Guides
- [GitHub Hello World Guide](https://guides.github.com/activities/hello-world/)
- [GitHub Pull Request Guide](https://docs.github.com/en/pull-requests)

### Best Practices
- [Conventional Commits](https://www.conventionalcommits.org/)
- [GitHub Flow](https://guides.github.com/introduction/flow/)

---

## License

This project is created for educational purposes as part of a Git and GitHub assignment.

---

## Assignment Details

- **Duration:** 5 Days
- **Team Size:** 2 Students
- **Submission:** Word document + GitHub repository URL
- **Platform:** Google Classroom
- **Total Marks:** 100

**Submission Date:** As per course timeline

---

## Appendix: Quick Reference Commands

```bash
# Start a new project
git init
git add .
git commit -m "Initial setup"

# Create and work on feature
git switch -c feature/my-feature
git add .
git commit -m "Implement feature"
git push -u origin feature/my-feature

# Merge changes
git switch main
git pull origin main
git merge feature/my-feature

# Handle mistakes
git stash              # Save uncommitted work
git restore file.txt   # Discard changes
git reset --soft HEAD~1  # Undo last commit
git revert HASH        # Undo committed change

# Release version
git tag v1.0.0
git push --tags
```

---

**Last Updated:** 2024  
**Version:** 1.0.0  
**Status:** Stable Release

---

*This README documents a Git and GitHub collaborative assignment demonstrating version control workflows, team collaboration, and modern development practices.*
