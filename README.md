**Active Windows-Server-2019**
# Active Windows Server 2019

**When you try to activate Windows server 2019 from evaluation version, do you always get an error message “the product key you entered didn’t work. Check the product key and try again, or enter a different one. (0x80070490)”? Today, I am going to show you how to install license key to activate Windows Server 2019 from Evaluation version. Let’s follow steps to activate your windows server 2019 (it also can be use for activating Windows Server 2016).**

**At First Convert your Windows server 2019 Standard Evaluation to Standard or Datacenter**


**Step 1: Go to Windows PowerShell ( Run as administrator) Mode, Then Copy the command line and paste**
 
    slmgr /skms kms.teevee.asia

**Step 2: Copy the command line and paste ( When your you convert Standard version )**

    DISM /online /Set-Edition:ServerStandard /ProductKey:N69G4-B89J2-4G8F4-WWYCC-J464C /AcceptEula
    
**Or Copy the command line and paste ( When your you convert Datacenter version )**

    DISM /online /Set-Edition:ServerDatacenter /ProductKey:WMDGN-G9PQG-XVVXX-R3X43-63DFG /AcceptEula
