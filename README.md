This repo is used to learn how CircleCI works and also how to trigger builds from CircleCI to Netlify. 

What I have done:
1. Clone the Gatsby starter project
2. Add .circleci/config.yml file with the different workflows 
3. the workflows will install dependencies, build the site and then deploy it to Netlify using the Netlify CLI


I have created a personal access token on Netlify that will allow CircleCI to trigger a build on it. This is stored as an environment variable on CircleCI. 
 

Reference:https://www.dasithsblog.com/blog/CI_CD_with_circleCI/
