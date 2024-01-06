<h1>Creating Password Policy in Local Group Policy</h1>


<h2>Description</h2>
In this lab, I configured a password policy. Password policies ensure that security requirements are enforced on the user's computer. These policies are configured per computer and they cannot be configured for a specific user. The Group Policy Editor is a Windows Admin tool that allows you to configure settings on the computer and network. This can range from password policy to startup programs, and define which application or settings users can change. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Group Policy Editor
- Windows 


<h2>Lab walk-through:</h2>

<p align="center">
Open Local Group Policy Editor: <br/>
<img src="https://i.imgur.com/N5Mq6yX.png" height="80%" width="80%" alt="hello this is reed"/>
<br />
<br />
Navigate to Computer Configuration, expand Windows Settings > Security Settings > Account Policies and click Password Policy:  <br/>
<img src="https://i.imgur.com/2nOvZvq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Open Maximum Password Age and open the properties: <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set the password Age to whatever you desire (mine is at 60):  <br/>
<img src="https://i.imgur.com/umMPuGW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
In the left pane click password Policy and select Export List:
  - This is where you can Export the Policy that was created<br/>
<img src="https://i.imgur.com/obokDQg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now the policies have been applied to the local machine and do not change per user on the machine.  <br/>
</p>
