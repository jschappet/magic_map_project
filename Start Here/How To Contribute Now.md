
Contributing to a project can be a rewarding experience, allowing you to improve your skills and collaborate with others. This guide will help you install Obsidian, set up useful plugins, clone the repository, create a pull request, and request write access to the repository.

## Install Obsidian

To install Obsidian, follow these steps:

1. **Download Obsidian**:
   - Go to the [Obsidian website](https://obsidian.md/download).
   - Choose the appropriate version for your operating system (Windows, macOS, or Linux).
   
2. **Install Obsidian**:
   - **For Windows**: Run the downloaded installer and follow the prompts.
   - **For macOS**: Open the downloaded `.dmg` file and drag Obsidian to your Applications folder.
   - **For Linux**: Extract the downloaded archive and run the Obsidian executable.

3. **Open Obsidian**:
   - Launch the application from your applications menu or desktop shortcut.

## Recommended Plugins to Install in Obsidian

To enhance your Obsidian experience, consider installing the following plugins:

[[How to Install Plugins]]

1. **Templater**:
   - Go to `Settings` > `Community Plugins`.
   - Toggle `Safe mode` off.
   - Click on `Browse` and search for "Templater".
   - Click `Install`, then `Enable`.
   
1. **Dataview**:
   - In the same `Community Plugins` section, search for "Dataview".
   - Click `Install`, then `Enable`.

1. **Git**:
   - In the same `Community Plugins` section, search for "Markdown Formatting Assistant".
   - Click `Install`, then `Enable`.

1. **File Hider**:
   - Search for "Calendar" in the `Community Plugins` section.
   - Click `Install`, then `Enable`.

1. **Meta Bind**:
   - Search for "Meta Bind".
   - Click `Install`, then `Enable`.

After installing the plugins, configure them according to your preferences in the `Settings` menu.

![[Screenshot 2025-03-20 at 12.38.09 PM.png]]
## GitHub Repository Management

[[Connecting with GitHub]] -- More detailed instructions here.

### Clone the Repository

To contribute to a project hosted on GitHub, you will first need to clone the repository:

1. **Open your terminal/command prompt**.
2. Navigate to the directory where you want to clone the repository.
3. Use the following command to clone the repository:

   ```
   git clone https://github.com/jschappet/magic_map_project.git
   ```     

### Fork the Repository

If you want to make changes and submit them back to the original repository, it’s best to fork it:

1. Go to the repository [page](https://github.com/jschappet/magic_map_project.git) on GitHub.
2. Click the `Fork` button in the upper right corner.
3. This will create a copy of the repository in your own GitHub account.

### Create a Pull Request

After making your changes, you can submit a pull request:

1. **Push your changes** to your forked repository:
   
```bash
   git add .
   git commit -m "Description of changes"
   git push origin main
   ```

   Make sure to replace `main` with the appropriate branch name if necessary.

2. Go to your forked repository on GitHub.
3. Click on the `Pull requests` tab.
4. Click `New pull request`.
5. Compare your branch with the original repository's branch and click `Create pull request`.
6. Add a description of your changes and submit the pull request.

### Request Write Access to the Repository

If you would like to have write access to the repository for more direct contributions:

1. Navigate to the repository on GitHub.
2. Click on the `Issues` tab.
3. Open a new issue requesting write access, providing a brief explanation of why you would like access and how you plan to contribute.
4. Wait for a response from the repository maintainers.

## Conclusion

Contributing to a project like Obsidian can greatly enhance your skills and help the community. By following these steps, you can install Obsidian, set up useful plugins, manage your contributions through GitHub, and request write access to the repository. Happy contributing!

#tags 
#Obsidian #Contribute #GitHub #Plugins #OpenSource #Markdown #Community
