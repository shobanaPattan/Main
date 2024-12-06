mkdir name_folder       //give a name to pull the project
cd name_folder      
pwd                    //To check the path of the pulled project
mkdir name_newFolder  //to insert all the pulled projects
cd name_newFolder
pwd                    //To check the path of the pulled project
git init              //Initialize the empty git repository
git pull https://github.com/shobanaPattan/Main.git  //path to pull the project
Make changes to code
git status            //To check the status of the modified files
git add .            //To add files into repository
git commit -m "message" //To commit the changed files
git status           //To check the status of the modified and committed files
git remote add origin https://github.com/shobanaPattan/Main.git //Give the path of the repository where the committed files to be added
git remote -v
git push -u main //To push the committed files
