# jenkins-pipelines 4
Code Build should automatically be triggered once commit is made to master branch or develop branch. If commit is made to master branch, test and push to prod; If commit is made to develop branch, just test the product, do not push to prod
The Code should be containerized with the help of a Docker file. The Docker image should be built every time there is a push to Git-Hub. 
