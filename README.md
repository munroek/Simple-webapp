# Simple-webapp
This is a simple web app using the AWS services Amplify, Lambda, IAM, API Gateway and DynamoDB. This follows a tutorial provided by [Tiny Technical Tutorials](https://www.youtube.com/playlist?list=PLwyXYwu8kL0wg9R_VMeXy0JiK5_c70IrV). 

## Hosting the Application

We'll be using [Amplify](https://aws.amazon.com/amplify/) to build and host the website.

First, we can create a basic HTML file. I'll be using Visual Studios Code as that's what I'm comfortable with. The HTML doesn't have to be anything fancy. We'll utilize the code below:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>To the Power of Math!</title>
</head>
<body>
    To the Power of Math!
</body>
</html>

```

This is just the HTML boilerplate with the title changed and a sentence in the body.

Create the HTML file into a zip file.

In the AWS Managment Console, in the search box, type Amplify:

![Amplify](https://onedrive.live.com/embed?resid=C6BB67E526E3A1E4%217030&authkey=%21AKip2YctQa4AUzU&width=1302&height=322)
If you haven't started a project yet, you can press "Get Started". 
We'll want to select "Amplify Hosting" to get started. 
