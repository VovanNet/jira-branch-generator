# 🪄 Jira Branch Name Copier with Type Selector

A Tampermonkey userscript that adds a convenient button to Jira issue pages, allowing you to copy a Git-friendly branch name with a selected prefix like `feature/`, `fix/`, `hotfix/`, `refactoring/`.

## 🚀 Features

- Adds a **"Copy Branch Name"** button directly to Jira issue pages.
- Lets you choose a branch type prefix from a dropdown.
- Automatically formats the branch name using the issue key and title.
- Converts the title to **kebab-case** for Git compatibility.
- Copies the result to your clipboard with one click.

## 📦 Example

For a Jira issue `ABC-123` titled “Fix login bug”, selecting `Bug` will copy:
> ***bugfix/ABC-123-fix-login-bug***

## 📸 Screenshots

### Branch Copier UI on Jira Issue Page
![Screenshot of branch copier dropdown and button](assets/jira-branch-copier-ui.png)


## 🖥️ Supported Platforms

- Works on Jira instances hosted on `atlassian.net`.

## 🧰 Requirements

- A browser extension that supports userscripts:
  - [Tampermonkey](https://www.tampermonkey.net/) (recommended)

## 📥 Installation

1. Install Tampermonkey for your browser.
2. Visit the script page:  
   👉 [GreasyFork Script Page](https://greasyfork.org/en/scripts/556214-jira-branch-name-copier-with-type-selector)
3. Click **“Install this script”**.
4. Open any Jira issue page to see the new button in action.

## ⚙️ Customization

You can edit the script in Tampermonkey to:

- Add or remove branch type prefixes.
- Change the formatting logic.
- Adjust styling or placement of the button.

## 🧪 Development

This script uses vanilla JavaScript and interacts with the Jira DOM. If your Jira layout differs, you may need to tweak the DOM selectors.

## 🧑‍💻 Author

- **VovanNet**  
  [GreasyFork Profile](https://greasyfork.org/en/users/1539203-vovannet)

## 📄 License

[MIT License](LICENSE)

---

✨ Pull requests and suggestions welcome!

