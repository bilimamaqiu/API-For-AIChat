# API-For-AIChat
A web about how to use api to talk about with some AI models

### Introduction
This is a project about how to call the API to use your AI model
Currently only local deployment is supported, and deployment using docker will be updated later.
In the early stage of the project, HTML and node.js will be used for operation. In the later stage, the front-end operation file format and new back-end may be changed.
This project supports deployment on the server. The minimum running memory is 500mb, which may be increased later.

### Local deployment method
1. Download the provided files
2. Download node.js from the node official website (choose your version)
3. Open your code software and use this project
4. Node runs the back-end code. The code will be valid on port 3000. If it is invalid, please check whether the security group is opened.

### docker deployment (waiting for updates)

### Deployment prerequisites
1.Have APIs for Claude/ChatGPT/third-party transfer station/other models
2. Probably not

### Features
1. The backend will record the text sent and the number of tokens used.
2. Has key verification function
3. There are IP record restrictions
4. There are token restrictions

### Subsequent update plan
1.Fix some bugs
2. Add other people’s API input interface
3. Add access key
