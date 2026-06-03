# Pre-Employment Project: Environment Setup

I am a performance marketer who is self-learning AI-native workflows.
This README documents how I set up the tools required for Step 1 of the 100Hires hiring process.

## Tools Installed

- Cursor IDE
- Claude Code (Cursor extension)
- Codex (Cursor extension)
- Git (CLI, installed separately for the GitHub workflow)

## Steps I Completed

1. Downloaded and installed Cursor IDE from cursor.com.
2. Inside Cursor, opened the Extensions panel and installed Claude Code, then signed in with my existing
  Claude Pro account.
3. Installed the Codex extension the same way. Codex and Claude Code did not show an obvious sign in button
  in the sidebar, so I opened the Command Palette (Ctrl+Shift+P), searched "Codex", 
   chose "Codex: Open Codex Sidebar", and the login bar appeared.
   I signed in with my free OpenAI account, then I did the same for Claude Code.
4. Created a public GitHub repository named "100hires-pre-employment-project" with the default README.md.
5. Installed Git on my local computer and cloned the repository through the terminal.
6. Opened the project folder in Cursor and edited this README directly inside the Cursor IDE.
7. Committed the changes and pushed to GitHub from the terminal.

## Issues I Ran Into And How I Solved Them

### 1. Choosing between Git CLI and GitHub Desktop

This was a decision rather than a bug, but it shaped the rest of my workflow.
I chose Git CLI instead of GitHub Desktop for two reasons.
First, I am currently self-studying programming (C and Python through CS50x),
and I wanted real practice with the command line because that is how developers actually work.
Second, I was curious to understand what each Git command does instead of clicking buttons without 
knowing the underlying action.

### 2. The "destination path already exists and is not an empty directory" error

I ran "git clone" twice by mistake. The second time, the terminal returned this error.
Instead of guessing, I copied the message into Claude and asked three questions in order:
   Why is this happening?
   What exactly is this error? (so I can understand the concept)
   How do I fix it?
I learned that Git refuses to clone into a folder that already has content, so it had not created a duplicate.
The fix was simple: I use "cd" to enter the existing folder and continue from there. No deletion needed.

### 3. Codex sign in flow was not obvious

After installing the Codex extension, I expected a clear "Sign In" button somewhere in the UI.
There was none. I checked the sidebar, the status bar, and the extension page. Nothing worked.
I then opened the Command Palette and searched "Codex", which surfaced a list of Codex commands.
The "Open Codex Sidebar" triggered the login prompt I was looking for.
Key takeaway: When a tool's UI is not intuitive, the Command Palette is often the fastest path.

### 4. Editor choice for the README itself

My first thought was to edit README.md with Notepad through the terminal. But when I typed "cursor ." 
in PowerShell, Cursor opened the folder directly, and editing inside Cursor was cleaner and easier to read.
I also wanted to explore Cursor more while I had it open, since the IDE is part of what 100Hires is asking me to learn. 
Two goals in one action.

## How I Use AI In My Workflow

I treat Claude as a debugging partner, not a code generator. When I hit an error, my loop is:

1. Why is this happening? I want to know the root cause.
2. What is this concept? Understanding it means I am not just copying and pasting a fix.
3. How do I fix it? Then I try the fix by myself.

This is how I learn the system instead of patching symptoms. 
I think this is what AI-native should mean in practice: AI accelerates research and understanding, 
but judgment and execution stay with me.

## A Short Note On Context

My background is in performance marketing, not engineering. I have worked across Meta Ads,
Google Ads, and Shopee Ads (a platform similar to Amazon in Southeast Asia) in agency, freelance, and in-house roles.
The technical side (tracking infrastructure, automation tools, internal dashboards) is where I have been 
pushing recently, both at work and through self-study. This Step 1 task fits exactly into that direction, 
which is part of why I applied for this role.