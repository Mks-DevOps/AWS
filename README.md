Industry: Healthcare
Problem Statement:
How to secure patient records online and send it privately to the intended party
Topics:
In this project, you will be working on a hospital project to send reports online and
develop a platform so the patients can access the reports via mobile and push
notifications. You will publish the report to an Amazon SNS keeping it secure and
private. Your message will be hosted on an EC2 instance within your Amazon
VPC. By publishing the messages privately, you can improve the message
delivery and receipt through Amazon SNS.
Highlights:
1. AWS CloudFormation to create a VPC
2. Connect VPC with AWS SNS
3. Publish message privately with SNS

Answer: 
1. create a Couldformation stack using given cloudformation temlate. Cloud formation will create all the required resources using giev code.
2. Once all resources are created create an sns sucscription on user mail and verify
3. create an Endpoint connection to privetly communicate with aws resources (SNS)
4. Conect to Ec2 through your terminal using ssh client "ssh -i "N.verginia.pem" ec2-user@ec2-34-238-167-97.compute-1.amazonaws.com"
5. run cmd to publish msg to user subscribed E-main "aws sns publish --region us-east-1 --topic-arn arn:aws:sns:us-east-1:855076548882:VPCE-Tutorial-Topic --message "Hii, my name is manas, hope you are doing well""
