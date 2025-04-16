
## Create and Copy SSH Key

Open Terminal, Command + Space, type in Terminal 

```bash

ssh-keygen
cat ~/.ssh/id_*.pub | pbcopy


```


## Goto GitHub Settings Page 

[GitHub Settings](https://github.com/settings/keys)

Click New SSH key, Paste in the SSH Key you copied above.

![[Screenshot 2025-03-21 at 5.30.53 PM.png]]
## Clone the Repository

```bash 

cd ~/Documents # Or some other location of your choice

git clone git@github.com:jschappet/magic_map_project.git


```

You may need to accept github's authenticity, just type in **yes**.

## Open Obsidian 

From the File menu | Open Vault... 

![[Screenshot 2025-03-21 at 6.03.02 PM.png]]


## Sync Changes 
![[Screenshot 2025-03-21 at 4.44.06 PM.png]]

![[Screenshot 2025-03-21 at 4.44.14 PM.png]]

