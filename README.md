## [Assista ao vídeo da demonstração](https://github.com/Vitoria-Barbara/SCADA/blob/main/assets/SCADA%20demonstration.mp4)

![demonstração](assets/SCADA-demonstration.gif)







# SCADA System in TIA Portal: Step-by-Step Guide  

### **Creating a Project**  

1. **Create a new project** in TIA Portal, selecting the specific PLC you plan to use.  
2. **Add a new device** with the specifications of your PLC.  

![Device Configuration](https://github.com/user-attachments/assets/0fd46800-3449-4d05-bd03-cc903dcdaeca)  

Once added, your screen should look like this:  

![Project Overview](https://github.com/user-attachments/assets/a9b77972-c961-4f45-9dff-fc00c47cb9ba)  

---

### **HMI Configuration**  

1. Open the **HMI_RT_1** section from the left-hand menu.  
2. Go to **Screens** and **add a new screen**.  

![HMI Configuration](https://github.com/user-attachments/assets/6f901939-c441-4030-80d7-9e8dbf03f8c5)  

---

### **Editing the Screen**  

1. Create or edit a screen. In this example, we’ll add two simple buttons:  
   - One button for **System ON**.  
   - Another button for **System OFF**.  

![Adding Buttons](https://github.com/user-attachments/assets/640421fa-250d-4962-be2a-5762736caf0b)  

2. **Customize the buttons**:  
   - Double-click the button to open its **Properties** menu.  
   - Go to the **Appearance** section.  
   - Change the **Fill Pattern** to a **Solid Color** and select the desired color.  

![Customize Button Appearance](https://github.com/user-attachments/assets/37ecc64f-eb88-46b5-84e9-f6353bd2b570)  
![Appearance Settings](https://github.com/user-attachments/assets/692534a7-ad04-4b01-a68a-6c13bdb82c12)  
![Choose Color](https://github.com/user-attachments/assets/b10da73b-cb03-4e3d-8cb6-ea16421eaa11)  

---

### **Adding Logic to the Buttons**  

1. Save your work frequently, as TIA Portal does not auto-save.  
2. Navigate to **PLC_1 -> Program Blocks -> MAIN**.  
3. Implement the logic required to handle the ON and OFF actions using ladder logic or your preferred programming method.  

![Main Program Blocks](https://github.com/user-attachments/assets/df3602a0-a843-4098-aba1-b59647e13d9b)  
![Ladder Logic Example](https://github.com/user-attachments/assets/9739a934-bf19-47a9-bcff-2be6307db940)  

---

### **Simulation**  

1. Save your project and **start a simulation test** using the simulator tool.  

![Simulation Start](https://github.com/user-attachments/assets/0cc71613-6f2d-456d-aaf0-64d355d0450a)  

---

### **Downloading to the Device**  

1. Click **Download to Device**.  
2. Configure the following settings:  
   - Uncheck any unnecessary options.  
   - Enable **PUT/GET communication** under the PLC communication settings.  

![Download to Device](https://github.com/user-attachments/assets/9273cc1a-4206-4a47-ab4e-0592e3e93d09)  
![PUT/GET Configuration](https://github.com/user-attachments/assets/397c031c-5729-49c0-b702-7faaaed7dcb3)  
![Confirmation](https://github.com/user-attachments/assets/f0b68332-d62f-40b2-94b3-5aa3c978e4b9)  

3. Confirm and load the configuration. Start the PLC module after loading.  

![Start Module](https://github.com/user-attachments/assets/66618660-9ba3-49dc-aa7b-7a065be0d298)  

---

### **HMI Simulation**  

1. Click on the **HMI screen** and start the **Runtime simulation**.  

![Runtime Simulation](https://github.com/user-attachments/assets/2bce4cca-cbf8-4777-a733-d49fa7551cd4)  

2. Verify or establish communication in the **HMI Connection** section.  

![Connections Setup](https://github.com/user-attachments/assets/f18edde0-ca4b-41dc-ba3a-f6065590fd77)  
![HMI Connection](https://github.com/user-attachments/assets/6c99c61c-40ad-444e-a690-2f78c24c1188)  

---

### **Advanced Configuration**  

1. If necessary, add a **communication module** (e.g., CP IE) for advanced setups.  
2. Reconfigure variables and readdress memory locations in the PLC if conflicts arise (e.g., Memory Clock issues).  

![Advanced Setup](https://github.com/user-attachments/assets/67e2f806-7469-4442-97a9-973bb7d16bc3)  

---
https://www.youtube.com/watch?v=96QfxMVIXyI
---

Your SCADA system is now successfully configured and ready to use!
