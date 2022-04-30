# gitBash_commands
**This repo contains commonly used git bash commands**

## Setup
<ul>
  <li>Configure user info, which is used across all local repositories</li>
    <ol>
      <li>git config --global user.name "[firstname lastname]"</li>
      <li>git config --global user.email "[valid-email]"</li>
      <li>git config --global color.ui auto</li>
    </ol>
</ul>

## Setup & Init
**Create a repo on github before completing the steps below**
<ul>
  <li>open git bash/terminal and check directory</li>
    <ol>
      <li>use the pwd command</li>
      <li>If needed cd to the correct directory (navigate to a directory where you want the save the project)</li>
    </ol>
  <li>git clone [clone url]</li>
  <li>git pull</li>
    </ol>
</ul>

## Update repo
**Use the commands below to update the repo from terminal**
<ul>
  <li>git status - show modified files</li>
  <li>add/remove files using one of the commands below</li>
    <ol>
      <li>git add -A (stages all files including deleted files</li>
      <li>git add . (add the entire directory recursively)</li>
      <li>git add -u (stages new and modified files only)</li>
    </ol>
  <li>git status</li>
  <li>git commit -m "explain what changes were made"</li>
  <li>git push origin main</li>
    </ol>
</ul>
