# obsidian-notes
obsidian import

How I git commit Obsidian notes:

1. Install Obsidian-Git extension
2. Create a folder [Project-Repository] to store repository [obsidian-notes] via Git Bash
	1. Change directory $[cd] to desired folder, using $[ls] to navigate and check contents
	2. Create folder using $[mkdir] to *make directory*. Use relevant title for folder name.
	3. Initialize directory using [git init], which creates hidden .git folder that tracks changes and version control.
3. Create GitHub repository [obsidian-notes] and fork it. 
4. Create a Personal Access Token in GitHub
	1. Settings -> Dev settings -> Personal Access Token
		- Never Expires
		- Scope set to "repo"
5. Open CMD Palette and type `clone existing repo`
6. Paste `https://<PERSONAL_ACCESS_TOKEN>@github.com/<USERNAME>/<REPO>.git` into Obsidian CMD palette (Ctrl + P)
	*directly copy the HTTPS link and format it according to above*
7. Restart Obsidian
8. To commit notes: CTRL + P for CMD Palette, type `Obsidian Git: Create backup`

Supplemental Steps:
**To connect from GitBash to GitHub**
	1. Identify account ownership through email
	2. type `git config --global user.email "jsmoultrie05@gmail.com"`
	3. **Viewing** `git config --global user.email`

---

## Note Taking Standards

- Notes are labeled by date, then subject matter
Dates will be categorized by months, then years. Within each folder, days appear chronologically.
### Body Format
