STEPS TO PULL AND PUSH THE PROJECT:
mkdir name_folder           //Give a name to pull the project
cd name_folder      
pwd                         //To check the path of the pulled project
mkdir name_newFoldername    //Give a name to the folder to pull the project
cd name_newFolder
pwd                         //To check the path of the pulled project
git init                    //Initialize the empty .git repository
git pull https://github.com/shobanaPattan/Main.git                         //Path to pull the project
Make changes to code
git status                  //To check the status of the modified files
git add .                   //To add files into repository
git commit -m "message"     //To commit the changed files locally
git status                  //To check the status of the modified and committed files
git remote add origin https://github.com/shobanaPattan/Main.git            //Give the path of the repository where the committed files to be added
git remote -v               //TO print the repository url
git push -u main            //To push the committed files
