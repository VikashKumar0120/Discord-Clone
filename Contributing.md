# Contributing guidelines

Thank you for taking the time to contribute to the project. Please take a moment to read the following guidelines before contributing:

## Important point to keep in mind before starting ✅

- If anything is missing or if you find something that needs to be enhanced/fixed/modified in the project, please feel free to [create an issue.](https://github.com/Yeasir0032/Discord-Clone/issues/new/choose)
- Ask to get the issue assigned to you before working on the issue & making a PR.
- Don't create a PR until the issue is not assigned to you.
- Mention the issue number in the PRs and describe all the changes that you have made briefly in the PR(if possible attach a screen recording showing the changes you made).

## How to Contribute? 🤔

### Step 1: Fork the Repository

Click on the "Fork" button.

By forking the repository, you will have your version of the repository under your GitHub username.

Once you have forked your repository, go to your profile inside the repository section, and you will find your forked repository.

### Step 2: Clone the Forked Repository

Once you locate your repository, you must clone it to your local machine.

```sh
git clone https://github.com/YOUR-USERNAME/Discord-Clone.git
```

Congratulations! You have successfully cloned the repository to your local machine. You can now make changes, add new features, or fix issues in the codebase.

### Step 3: Go to the directory
```sh
cd Discord-Clone
```

### Step 4: Install all the dependencies
```sh
npm install
```

### Step 5: Start the application

```sh
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) with your browser to see the result.

### Step 5: Create a New Branch (important)

It's recommended to create a new branch for your changes. This helps keep your modifications separate from the main branch, making it easier to manage and review your contributions.

```sh
git checkout -b <branch-name>
```

### Step 5: Make Your Changes

Make the necessary changes or additions to the codebase.
Once you have added changes in your local, its time to push them, for that run this command to bring the modification to the staging area.

### Step 6: Check your changes

```
git status
```

```
git diff
```

git status: Shows the current status of the repository, including changes, untracked files, and branch information.

git diff: Displays the differences between the working directory and the last commit or between branches.

### Step 10: Stage your changes

```
git add .
```

This command is used to stage all the changes in the current directory and it's subdirectories for the next commit. It adds all modified and new files to the staging area, allowing you to include them in the next commit.

**Note:** The . represents the current directory, so git add . includes all files and directories within the current working directory. This means if you are anywhere outside from the directory then the changes would not be staged.
So make sure you are in correct directory.


### Step 7: Commit Your Changes

Commit your changes with a meaningful commit message using the following command: 


```bash
  git commit -m "Enter Your message related to what work you did"
```
(make sure to add a decent commit message to avoid confusion and get your PR merged)

Once you have committed your changes, it's time to push them to your forked repository on GitHub.

### Step 8: Push Your Changes

Use the following command to push your changes:

```bash
git push -u origin <branch-name>
```

Replace <branch-name> with the name of the branch you created earlier.

### Step 9: Make a Pull Request

After pushing your changes, open your forked repository on GitHub in your web browser.

Click on `compare and pull request`

Provide a clear and informative title and description for your pull request. Explain the changes you have made and why they should be incorporated into the original repository.

Review your pull request to ensure everything is correct, and then click on the "Create pull request" button to submit it.

### Congratulations! 🎉

Your pull request will now be visible to the maintainers of the original repository. They will review your changes, provide feedback if necessary, and decide whether to merge them into the main branch.

### Alternatively contribute using GitHub Desktop

1. **Open GitHub Desktop:**
   Launch GitHub Desktop and log in to your GitHub account if you haven't already.

2. **Clone the Repository:**
   - If you haven't cloned the Discord-Clone repository yet, you can do so by clicking on the "File" menu and selecting "Clone Repository."
   - Choose the Discord-Clone repository from the list of repositories on GitHub and clone it to your local machine.

3. **Switch to the Correct Branch:**
   - Ensure you are on the branch that you want to submit a pull request for.
   - If you need to switch branches, you can do so by clicking on the "Current Branch" dropdown menu and selecting the desired branch.

4. **Make Changes:**
   Make your changes to the code or files in the repository using your preferred code editor.

5. **Commit Changes:**
   - In GitHub Desktop, you'll see a list of the files you've changed. Check the box next to each file you want to include in the commit.
   - Enter a summary and description for your changes in the "Summary" and "Description" fields, respectively. Click the "Commit to <branch-name>" button to commit your changes to the local branch.

6. **Push Changes to GitHub:**
   After committing your changes, click the "Push origin" button in the top right corner of GitHub Desktop to push your changes to your forked repository on GitHub.

7. **Create a Pull Request:**
  - Go to the GitHub website and navigate to your fork of the Discord-Clone repository.
  - You should see a button to "Compare & pull request" between your fork and the original repository. Click on it.

8. **Review and Submit:**
   - On the pull request page, review your changes and add any additional information, such as a title and description, that you want to include with your pull request.
   - Once you're satisfied, click the "Create pull request" button to submit your pull request.

9. **Wait for Review:**
    Your pull request will now be available for review by the project maintainers. They may provide feedback or ask for changes before merging your pull request into the main branch of the Discord-Clone repository.

⭐️ Support the Project
If you find this project helpful, please consider giving it a star on GitHub! Your support helps to grow the project and reach more contributors.

Congratulations! You have successfully created a pull request to contribute your changes to the repository. Remember to monitor the pull request for any updates or feedback from the maintainers.


### Commit Message Guidelines using Commitlint

We follow a standardized commit message format using Commitlint to ensure consistency and clarity in our commit history. Each commit message should adhere to the following guidelines:

1. **Type**: The commit type must be one of the following:

   - `feat`: A new feature or enhancement.
   - `fix`: A bug fix.
   - `docs`: Documentation changes.
   - `style`: Code style changes (e.g., formatting, semicolons).
   - `refactor`: Code refactorings with no feature changes or bug fixes.
   - `test`: Adding or improving tests.
   - `chore`: General maintenance tasks, build changes, etc.

2. **Scope** (Optional): The scope provides context for the commit, indicating the specific part of the project being affected. Use a short description in lowercase (e.g., `auth`, `navbar`, `README`).

3. **Description**: A brief and meaningful description of the changes made. Start with a capital letter and use the imperative mood (e.g., "Add new feature" instead of "Added new feature").

4. **Issue reference** (Optional): Include the issue number associated with the commit (e.g., `#123`).

### Examples:

#### Valid Commit Messages:

- `feat: Add user authentication feature`
- `fix(auth): Resolve login page redirect issue`
- `docs: Update installation instructions`
- `style: Format code according to project guidelines`
- `refactor(navbar): Improve responsiveness`
- `test: Add unit tests for API endpoints`
- `chore: Update dependencies to latest versions`
- `fix: Handle edge case in data processing (#456)`

#### Invalid Commit Messages:

- `Added new stuff`
- `Fixed a bug`
- `Updated code`
- `auth feature update`
- `chore: fixed some stuff`


By following these guidelines, we can maintain a clean commit history that is easy to understand and helps us effectively track changes. If you have any questions or need further assistance, feel free to ask! Happy contributing!

<h3> Don't forget to give a ⭐ to this repo !!<h3>

