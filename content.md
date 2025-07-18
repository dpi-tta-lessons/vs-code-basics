# Visual Studio Code - Your Integrated Development Environment

Visual Studio Code is one of the most popular code editors in the world. It's fast, flexible, and packed with features that help you write, run, and debug code more easily no matter what language you're using.

## Goal

By the end of this lesson, you’ll be able to install VS Code, open a project folder, write and save a file, and run it in the terminal.

## 1. Install VS Code

- Go to the official download page: https://code.visualstudio.com
- Download the installer for your OS (Windows, macOS, or Linux).
- Open the installer and follow the default prompts.
- Launch VS Code

<aside class="tip">
  On Windows, choose “Add to PATH” during setup. It makes launching VS Code from the terminal easier.
</aside>

## 2. Open a Folder (Your Project Workspace)

Let’s make a place for your code. Open your terminal and run:

```bash
mkdir hello-project
cd hello-project
```

Now open it in VS Code:

```bash
code .
```

<aside class="tip">
  If <code>code .</code> doesn’t work, press <code>⌘ + Shift + P</code> (Mac) or <code>Ctrl+Shift+P</code> (Win/Linux) in VS Code, type <code>shell command</code>, and select <strong>Install 'code' command in PATH</strong>.
</aside>

VS Code will open your new folder as a project workspace.

## 3. Create and Save a File
In VS Code, click the New File icon in the Explorer sidebar.

Name it: `hello.txt`

Type:

```
Hello, VS Code!
```

Press `⌘ + S` (Mac) or `Ctrl + S` (Win/Linux) to save.

<aside class="why">
  Files you create in VS Code are saved directly into your project folder. No extra setup needed.
</aside>

## 4. Use the Integrated Terminal

Open the terminal inside VS Code:

- Go to the top menu: View > Terminal (or press Ctrl + `)

You’ll now see a terminal at the bottom of the window. Try:

```bash
ls
```

You should see:

`hello.txt`

<aside class="tip">
  <strong>Shortcut:</strong> Press <kbd>Ctrl + `</kbd> (that’s the backtick key) to quickly toggle the terminal.
</aside>

## Shortcuts to Know

| Shortcut	            | What It Does                         |
| --------------------- | ------------------------------------ |
| ⌘/Ctrl + S            | Save the current file                |
| ⌘/Ctrl + P            | Quickly open any file in the project |
| ⌘/Ctrl + /            | Toggle a comment on a line           |
| ⌘/Ctrl + Shift + P    | Open the Command Palette             |
| ⌘/Ctrl + B            | Show/hide sidebar                    |
| ⌘/Ctrl + ` (backtick)	| Toggle terminal                      |

<aside class="tip">
  The Command Palette is your command center. Try typing "theme" or "terminal" into it!
</aside>

## Practice Challenge

Try This:

- Create a new file named notes.md
- Write 3 lines of markdown text.
- Open the integrated terminal and list your files.

## Wrap-Up

You’ve learned how to:

- Install and launch VS Code
- Open a project folder from the terminal
- Create and save files
- Use the integrated terminal
- Use time-saving shortcuts


## Quiz

- What does the `code .` command do?
- Opens the current folder in VS Code
  - Correct! It opens your project folder directly in the editor.
- Runs your code in the terminal
  - Not quite. It launches VS Code.
- Closes VS Code
  - Nope, that’s not what it does.
{: .choose_best #code_dot title="Opening a Folder with VS Code" answer="1"}

- Which are useful VS Code features?
- Integrated terminal
  - Correct! You can run shell commands right inside the editor.
- Built-in web browser
  - Nope! VS Code doesn’t have a browser.
- Extensions marketplace
  - Correct! You can install features for different languages and tools.
- Infinite scrolling
  - Not quite. That’s not specific to code editing.
{: .choose_all #features title="VS Code Features" answer="[1,3]"}

- What shortcut opens the Command Palette?
- ⌘/Ctrl + Shift + P
  - Correct! This lets you run almost any VS Code command.
- ⌘/Ctrl + P
  - Not quite. That opens the file search.
- ⌘/Ctrl + B
  - That toggles the sidebar.
{: .choose_best #command_palette title="VS Code Shortcuts" answer="1"}
