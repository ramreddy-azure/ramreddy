Steps to set the infrastructure
Login to VSCode or any other IDE of your choice

Run the below commands to download the application code

mkdir day4_youtube_clone; cd day4_youtube_clone
git init
git clone https://github.com/piyushsachdeva/Youtube_Clone
Create a project in Azure DevOps for Day4 and push the code by running the below commands on VSCode:

git remote add origin $YOURAZUREREPO
git push -u origin all
Note: Make sure to update your Azure repo in the above command

Go to the Azure Portal and Create the Azure App Service by following the instructions in the video

Implement the build pipeline using the classic editor

Understand the use of service connection and service principal
