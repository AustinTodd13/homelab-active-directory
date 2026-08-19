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



### **3) Network Setup**

- Go to search bar and type **Network** and click **Network Status**
- Click **Change Adapter Options** and right click Ethernet and click **Properties**
<img src="../../images/07.png" alt="AD setup" width="450" />

- Select **Internet Protocol Version 4** and click **Properties**
- Setup a Static IP address and DNS IP to localhost 127.0.0.1
- Click **OK**
<img src="../../images/08.png" alt="AD setup" width="450" />

- Go to **Server Manager** and click **Local Server**
- Click **Computer Name**
- Select **Change** and input your new Server Name
- Restart Server
<img src="../../images/09.png" alt="AD setup" width="450" />



### **4) Active Directory Setup**

- Go to **Server Manager** and go to **Manage** and click **Add Roles and Features**
<img src="../../images/10.png" alt="AD setup" width="450" />

- Click **Next**
<img src="../../images/11.png" alt="AD setup" width="450" />

- Select **Active Directory Domain Services**
- Click **Next**
<img src="../../images/12.png" alt="AD setup" width="450" />

- When you get to Confirmation, click **Install**
<img src="../../images/13.png" alt="AD setup" width="450" />

- After Install, Select **Flag with '!'**
- Click **Promote this Server to Domain Controller**
<img src="../../images/14.png" alt="AD setup" width="450" />

- Select **Add New Forest**
- Create a name for **Root Domain Names**
<img src="../../images/15.png" alt="AD setup" width="450" />

- Click **Next**
- Create and Confirm **Password**
<img src="../../images/16.png" alt="AD setup" width="450" />

- Click **Next** until **Install Button Appears** and click **Install**
- Restart Server after Install is Completed
<img src="../../images/17.png" alt="AD setup" width="450" />
