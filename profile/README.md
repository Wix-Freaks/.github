## Hi there 👋

# Website Code Saving Process

This README contains instructions on how to save website code effectively. By following these steps, you can easily create a local repository and store your website code while also integrating it with Git for version control and collaboration.

## Step 1: Copying the Code
- Open the code editor for your website.
- Use the editor's search function, preferably in the Wix Dev Mode, to locate pages that contain code.
- Copy the code from each page and ensure that you capture all the necessary code snippets.

## Step 2: Creating a Local Repository
- Choose a name for your local repository. Following the naming scheme "Firstname-Secondname-Thirdname," replace "Firstname," "Secondname," and "Thirdname" with relevant names or keywords. Use hyphens ("-") to separate each word.
- Create a new folder on your local machine to serve as the repository for your website code. Name the folder according to the chosen repository name.

## Step 3: Organizing the Files
- Within the local repository folder, create separate subfolders to categorize the code files based on their functionality.
- Place the copied code files into their respective folders. For backend code, move the files to the "backend" folder. For frontend code, move the files to the "frontend" folder. Ensure that the code files are appropriately named in camel case (camelCase) to maintain consistency and clarity.

## Step 4: Setting up Git Repository
- Open a terminal or command prompt in the local repository folder.
- Initialize a new Git repository by executing the command: `git init`. This command initializes an empty Git repository in the current directory.

## Step 5: Committing and Connecting
- Add all the changes made to the repository using the command: `git add .`. This command stages all modified and new files for the commit.
- Create a commit to record the changes using the command: `git commit -m "Initial commit"`. Replace "Initial commit" with a descriptive message summarizing the changes you made.
- If you haven't already, create a new repository on a Git hosting service (e.g., GitHub, GitLab) with the same name as your local repository.
- Connect your local repository to the remote Git repository by executing the command provided by the hosting service. This typically involves adding a remote repository URL using the command: `git remote add origin <remote_repository_url>`. Replace `<remote_repository_url>` with the URL of your remote Git repository.

## Step 6: Pushing to the Online Repository
- Push the code from your local repository to the remote Git repository using the command: `git push origin master`. This command uploads your code and makes it accessible for collaboration.
- Depending on your Git hosting service and repository configuration, you might be prompted to provide authentication credentials (e.g., username and password, SSH key).

By following these steps, you will be able to save your website code, organize it into frontend and backend components, and integrate it with Git for version control and collaboration.
