# JAVA Accelerator

## FAQ:

### Initial Setup

1. Before you begin, please navigate to your home directory and create a new directory called `java-accelerator`. This
   step only needs to be performed once:
   ```bash
    cd ~
    mkdir java-accelerator
    cd java-accelerator
   ```

### How do I Fork and Clone lessons/labs?

1. From the General Assembly enterprise GitHub account, navigate to the top right corner of the repository page and
   click the "Fork" button
2. Select your Username as the destination for the fork.
3. Verify that the repository is under your username: `https://git.generalassemb.ly/username/repo-name`
4. Click the green Code button and then click the clipboard icon next to the **SSH URL** to copy the .git path.
5. Open the terminal and `cd` into your java-accelerator folder: `cd ~/java-accelerator`.
6. From the terminal window, type: `git clone <paste_git_url_here>`
7. Open this newly created directory in JetBrains IntelliJ IDE by selecting "Open" from the IDE's welcome screen or
   navigating through the menu option `File` > `Open`.

   <br>

### How do I commit and push my work to GA's GitHub Enterprise?

1. In the VM Terminal, `cd` into the folder you want to push up.
2. Add your files to a staging mode: `git add -A`
3. _(Optional)_ - You can run `git status` to observe your files
4. Commit your files to version control: `git commit -m "PUT A DESCRIPTION OF WHAT YOU'RE COMMITTING HERE"`
5. _(Optional)_ - You can run `git status` to observe what you committed
6. _(Optional)_ - You can run `git log` to see a history of all your commits.
7. Push to GitHub: `git push`. You can now goto your repo on GitHub to see your new files.

<!-- NOTE - if you get an error, try `git push origin main`. Your primary branch will be named `master` or `main`. -->
<!-- You can now goto your repo on GitHub to see your new files. NOTE - if you do not see your updates, please select the dropdown menu on the top right (it'll probably say "Main") and select the "Master" branch. -->
<br>

### How do I submit my Work via Pull Request?

1. In your repository, click on Pull Requests which is placed underneath the repo name.
   ![](resources/start-here/assets/pull_requests.png)
2. Click on the New pull request button.
   ![](resources/start-here/assets/new_pr.png)
3. Confirm that the base repository is the ModernEngineering org name and the head repository is your GH username. Once
   that's been verified, click on the Create pull request button.
   ![](resources/start-here/assets/create_pr1.png)
4. In the Title input, type in `java-accelerator - <your_first_name> <your_last_name>` then click on Create pull request
   to officially submit your lab or homework.
    - In the comment section, you must add the following:
      ```text
         * Comfortability [0 to 5]
         * Completeness [0 to 5]
         * What was a win?
         * What was a challenge?
         * Any other comments
      ```