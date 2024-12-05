# Notes

## Tasks
- [ ] Create a GitHub repository
- [ ] Write a `README.md` file
- [ ] Push the project to GitHub
- [ ] Learn basic Markdown

---

## Git Commands to Remember
- `git init` - Initialize a new Git repository.
- `git add .` - Stage all changes.
- `git commit -m "message"` - Commit changes with a message.
- `git push` - Push changes to the remote repository.
- `git pull` - Fetch and integrate changes from the remote repository.
- `git status` - Check the status of the repository.

---

## Shortcuts
- `Ctrl + K V` - Open Markdown preview in VS Code.
- `Ctrl + S` - Save the file.
- `Alt + Shift + Down` - Duplicate the selected line.

---

## Links
- [Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/)
- [GitHub](https://github.com)

---

## Using Personal Access Token (PAT)
1. **Generate a Token**:
   - Go to **GitHub Profile → Settings → Developer settings → Personal Access Tokens → Tokens (classic)**.
   - Click **Generate new token**.
   - Select required scopes (e.g., `repo` for repository access).
   - Copy the generated token.

2. **Use the Token for Authentication**:
   - During `git push`, when prompted for a password, paste your **token** instead of your GitHub password.

3. **Cache the Token** (Optional):
   ```bash
   git config --global credential.helper store
