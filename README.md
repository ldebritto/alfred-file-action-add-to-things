## Description
File action to create a task with a link to the selected file on the Notes field

## How to install
Download the workflow from the Releases page on this Repo.

## How to use
1. Select a file on Alfred
<img width="605" alt="Captura de Tela 2022-01-17 às 18 56 04" src="https://user-images.githubusercontent.com/73193566/149841008-7465cbd2-9fe6-4abb-97f5-8dcc4472c594.png">

2. Select "Add file to Things new task Quick Entry" and this should be your result:
<img width="648" alt="Captura de Tela 2022-01-17 às 18 54 12" src="https://user-images.githubusercontent.com/73193566/149841100-23b391ae-7a39-4ea5-8e0f-83f7e1e0210b.png">

From there, it's a breeze to tag file the task as you would in any Area/Project/List…

## How it works
Uses an AppleScript to perform the following actions:
1. Fetch a `file://` link to the selected file
2. Open a Quick Entry window with the link in the `Notes` field
