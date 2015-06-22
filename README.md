# CS-Test
messing with Git
Getting Started with Intrusion Prevention System (IPS)
_____________________________________________________________________________________________
Overview
The Platform CenturyLink IPS utilizes an Agent installed on your VM that will monitor that VM for suspicious activity.  If found, will log it, may block or stop it, and will report it based on the IPS policy.  There is a default policy associated to each VM that is automatically tuned based on the host operating system and installed applications.
The blueprint is for the actual installation and activation of the IPS service on the VM, other blueprints will be available for modifications to the install.
Prerequisites
•	A CenturyLink Cloud Account
•	Managed Operating System Services on the Virtual Machine
Supported Managed Operating Systems
•	Red Hat Enterprise Linux 5 (64 bit only)
•	Red Hat Enterprise Linux 6 (64 bit only)
•	Microsoft Windows Server 2008 (64 bit only)
•	Microsoft Windows Server 2012 (64 bit only)
Important Information
•	Can be applied to either a managed or unmanaged VM
Installation Process
1. Search for DSA (IPS) in the Blueprint library. Then, click on DSA (IPS) 95 Install for RHEL 64bit Part 1.

 
 
2. Click on the deploy blueprint button
 

3. Select the appropriate virtual machine to execute on.  Create and confirm User Password.  Click next: step 2 button.         

 

4. Review the blueprint parameters and select deploy blueprint.

 

5. Blueprint will show each step taken and its status during provisioning.
 


6. An email notification will be sent to the initiator of the blueprint for both queuing and completion.

Frequently Asked Questions
Q: Can I make modifications to my existing policy to further customize or tune it?
Not at this time, if you'd like to see this feature, please contact features@ctl.io.


