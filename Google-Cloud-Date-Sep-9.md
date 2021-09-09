# Google Cloud Platforms 

#### What is IAM 
```
Identity and Access Management 
```
## Create Our First VPC in Google Cloud
### Introduction
You have been tasked with creating a test VPC network with a public subnet in the IOWA region. Your company would like to provision and test resources as they wish in this environment. In the end, you will provision a VPC network that meets their exact need.

## To complete the objectives, we need to

- Create a VPC
- Create a custom subnet in the IOWA region

#### Solution
How to Log in to Google Lab Accounts
On the lab page, right-click Open Google Console and select the option to open it in a new private browser window (this option will read differently depending on your browser — e.g., in Chrome, it says "Open Link in Incognito Window"). Then, sign in to Google Cloud Platform using the credentials provided on the lab page.

On the Welcome to your new account screen, review the text, and click Accept. In the "Welcome Cloud Student!" pop-up once you're signed in, check to agree to the terms of service, choose your country of residence, and click Agree and Continue.

#### Create the VPC
- From Google Cloud console's main navigation, choose VPC Network.
- Click Create VPC Network. (In a production environment, you would choose the applicable project before creating the VPN Network. We only have one project available for the lab environment).
- Give your VPC a name.
- On Subnets, click Custom. Give a unique name to your subnet.
- Set Region to US-Central-1
- Set you IP Address range to 10.0.1.0/24.
- Click Done.
- Click Create.

##### Conclusion
```
Congratulations — you've completed this hands-on lab!
```


### Creating and Configuring a Compute Engine Instance
#### Introduction
General purpose instances are widely used in the GCP environment! Understanding how to create and configure an instance is a pretty important task. In this hands-on lab, we will create and configure a general-purpose instance.

### Scenario
You have been tasked with creating an instance for your team's workload. They would like for this instance to be in the Iowa region, available to be connected over HTTP and HTTPS protocols, and use a general-purpose instance. They want to go the cheapest route and save the most money possible.

###### Note: Instead of using a Compute machine instance in the lab, please use a General-purpose E2 series, e2-medium (2 vCPU, 4 GB memory) machine configuration.

### Connect to the Lab
- Log in to the GCP console using the credentials provided on the lab instructions page.
- If a pop-up window appears about welcoming you to your new account, click Accept.
- Agree to the terms on the welcome screen.
- Select your Country of residence from the combo box.
- Click AGREE AND CONTINUE.
### Create the General Purpose Instance
- In the left-hand pane, click Compute Engine.
- Click Create instance.
- Enter a Name of test-instance in the box provided.
- Make sure the Region is set to us-central1 (Iowa). If it is not, use the combo box to select that value.
- Under Machine family, select General-purpose.
- Ensure the Series is set to E2. If it is not, use the combo box to select that value.
- Use the Machine type combo box to select e2-medium (2vCPU, 4 GB memory).
- Under Firewall, select both the checkboxes for Allow HTTP traffic and Allow HTTPS traffic.
- Click Create.
- Once the instance has been created, verify the details for the instance.
##### Conclusion
```
Congratulations, you've completed this hands-on lab!
```
