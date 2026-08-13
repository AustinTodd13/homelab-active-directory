# 🖱️ **Active Directory VM Setup**

### **1) Setup Virtual Machine**
- Open **Virtual Box**
- Click **New**
<img src="../../images/01.png" alt="AD setup" width="450" />

- Type VM name in **VM Name**
- Choose iso image in **ISO Image**
- Deselect **Proceed with Unattended Installation**
- Make sure **OS** and **OS Version** are correct

<img src="../../images/02.png" alt="AD setup" width="450" />

- Right click on created VM and Select **Settings**
- Scroll down to **Network**
- Select **Nat Network** and Select the created Nat Network
- Have **Promiscuous Mode** switched to **allow all**
- Select **OK**

<img src="../../images/03.png" alt="AD setup" width="450" />



### **2) Installing Windows Server**

- Select **Active Directory VM**
- Click **Next** and **Install Now**
- Select **Standard Desktop Experience**
<img src="../../images/04.png" alt="AD setup" width="450" />

- Click **Custom Install**
- Click **Next**
- Wait for Restart
<img src="../../images/05.png" alt="AD setup" width="450" />

- Create Password for Admin Account
- Click **Finish**
- Login to make sure the created password works
<img src="../../images/06.png" alt="AD setup" width="450" />
