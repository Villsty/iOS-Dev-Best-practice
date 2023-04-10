# iOS-Dev-Best-practice
My chosen workflow and way of working with Xcode, Github and coding in Swift

Create a new Xcode project: 
Open Xcode and create a new project using the appropriate project template. Choose a location on your local machine to save the project.
Initialize a Git repository: In the terminal, navigate to the root directory of your Xcode project and initialize a new Git repository by running the following command:

git init

This will create a new Git repository in the root directory of your Xcode project.

Create a new repository on GitHub: 
In your web browser, navigate to GitHub and create a new repository. Give your repository a name and description, and make sure to select the appropriate options for public or private visibility.
Link your Xcode project to the GitHub repository: Copy the HTTPS URL of your newly created GitHub repository. In Xcode, go to Source Control > your project name > Configure your project name... and select the "Remotes" tab. Click the "+" button to add a new remote repository, and paste the HTTPS URL of your GitHub repository. Give the remote repository a name, such as "origin".
Commit your changes: In Xcode, make some changes to your project (e.g. add a new file or modify an existing one) and save your changes. Go to Source Control > Commit... and add a commit message. Make sure to select all the changes you want to include in your commit. Click "Commit".
Push your changes to GitHub: Once you've committed your changes, go to Source Control > Push to <remote> to push your changes to the remote repository on GitHub. Make sure to select the appropriate branch you want to push to.

From now on, you can use Xcode's built-in Git functionality to commit changes to your local repository and push changes to the remote repository on GitHub.
