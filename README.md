# BadJoker

A clouformation template that deploys two AWS lambda functions, assigns IAM roles, grants neccessary permissions, sets up an API and SNS topic.


![test3](https://user-images.githubusercontent.com/82989538/124405466-95018300-dcf3-11eb-815b-6c9ac2d89e1f.png)

<br/>

To test this stack, upload the CF_BadJoker template to AWS cloudformation Designer and click create stack. Cloudformation will create all the components of
this stack. Next to test the stack, retrieve the API url from API gateway make a POST request like described in the image below. If successful, you will
receive a confirmation like one at the bottom of the image:

![](images/postman.JPG)

<br/>
Next, the subscribed email will receive a confirmation notification. Once subscribed, the user will receive periodic notification with a joke:

![](images/aws_notification.JPG)
