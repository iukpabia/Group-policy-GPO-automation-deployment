# Group-policy-GPO-automation-deployment

 

<h2>Description</h2>
Group Policy is a feature in Microsoft Windows operating systems that allows administrators 
to manage user and computer configurations centrally within an Active Directory environment. 
It enables administrators to control various aspects of users' and computers' settings, 
such as security options, application settings, network configurations,software deployment and more.
This project demonstrates how to automate deployment of Mozilla firefox software on domain computers. 

<br />


<h2>Tools</h2>

- <b>Group Policy Objects (GPO)</b> 
- <b>Active directory</b>
- <b>Windows 2019</b>


<h2>Deployment Destination </h2>

- <b>Windows 2019</b> 

<h2>Project walk-through:</h2>

<p align="center">

Install Active directory <br/>

<img width="450" alt="Picture1" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/58b3da51-0da1-4793-8f84-bd43809e36dd">
<br />
<br />
Select destination server <br />
<img width="450" alt="Picture2" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/961f9464-c7d2-4ab4-8ce5-e1ba3db2a5d1">
<br />
<br />

Select server role <br/>

<img width="450" alt="Picture3" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/42496542-94ad-40b9-b509-b4a545db9c4c">
<br />
<br />

Promote to Domain controller<br />

<img width="450" alt="Picture4" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/e947a85c-a8a9-4015-8388-c361b2085ffb">


<br />
<br />

Active Directory installed <br/>

<img width="450" alt="Picture5" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/7f17c6aa-ca4d-4dcf-9ccf-972576bfe2db">

<br />
<br />


Group policy management <br/>

<img width="450" alt="Picture6" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/43c25e99-d9e2-4484-be7d-1bb65af62249">

<br />
<br />

 Creating New GPO called mozilla installation<br/>

<img width="450" alt="Picture7" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/563c5938-5712-4490-a9c8-3ab4553ff24e">


<br />
<br />

<br />

<img width="450" alt="Picture8" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/77dc566c-26f8-4cf7-bfce-4beeac4fc779">


<br />
<br />


 Create a new package for mozilla firefox installation.<br/>

<img width="450" alt="Picture9" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/18eec915-dabc-4e0b-ae78-3652899e8f02">
<br />
<br />

 Select the downloaded Mozilla Firefox .msi file<br/>

<img width="450" alt="Picture10" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/edc82973-d196-430d-8475-312b936f55c8">


<br />
<br />

 Assign a deployment method.<br/>

<img width="450" alt="Picture11" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/7921d321-4eab-45b4-b805-371cc49cb927">

<br />
<br />


 Mozilla software assigned.<br/>

<img width="450" alt="Picture12" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/a8e7b47c-95ee-4f29-a952-958541bcdfa4">


<br />
<br />



Viola!!! the end product (mozilla firefox deployed) <br/>

<img width="450" alt="Picture13" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/0f8455e3-8be7-4b0c-b72d-23c0b5935c7b">


<br />
<br />
