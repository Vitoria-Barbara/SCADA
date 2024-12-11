# SCADA
TIA PORTAL - SISTEMA SCADA 
### SCADA System in TIA Portal: Step-by-Step Guide  

#### Creating a Project  

1. **Create a new project** in TIA Portal, selecting the specific PLC you plan to use.
2. 
![image](https://github.com/user-attachments/assets/0fd46800-3449-4d05-bd03-cc903dcdaeca)

![image](https://github.com/user-attachments/assets/a9b77972-c961-4f45-9dff-fc00c47cb9ba)

3. **Add a new device** with the specifications of your PLC.

![image](https://github.com/user-attachments/assets/535dcef2-dadd-4b96-8128-52224e432adc) 
![image](https://github.com/user-attachments/assets/535dcef2-dadd-4b96-8128-52224e432adc)

---

#### HMI Configuration  

1. Open the **HMI_RT_1** section from the left-hand menu.  
2. Go to **Screens** and **add a new screen**.  

---

#### Editing the Screen  

1. Create or edit a screen. In this example, we’ll add two simple buttons:  
   - One button for **System ON**.  
   - Another button for **System OFF**.  

2. **Customize the buttons**:  
   - Double-click the button to open its **Properties** menu.  
   - Go to the **Appearance** section.  
   - Change the **Fill Pattern** to a **Solid Color** and select the desired color.  
![image](https://github.com/user-attachments/assets/640421fa-250d-4962-be2a-5762736caf0b)
---

#### Adding Logic to the Buttons  

1. Ensure you save your work frequently, as TIA Portal does not auto-save.  
2. Navigate to **PLC_1 -> Program Blocks -> MAIN**.  
3. Implement the logic required to handle the ON and OFF actions using ladder logic, or your preferred programming method.  


![image](https://github.com/user-attachments/assets/df3602a0-a843-4098-aba1-b59647e13d9b)

![image](https://github.com/user-attachments/assets/9739a934-bf19-47a9-bcff-2be6307db940)

![image](https://github.com/user-attachments/assets/1dc6e87a-2228-4db7-b717-27c5a55e4816)

![image](https://github.com/user-attachments/assets/b0fa496b-4a39-4321-80b2-6a9bedee2f75)

![image](https://github.com/user-attachments/assets/98425c5f-af02-47a3-854f-9e21e8c47bd2)

---

#### Simulation  

1. Save your project and **start a simulation test**:  
   - Use the **simulator tool** to test your configurations.  

---

#### Downloading to the Device  

1. Click **Download to Device**.  
2. Ensure the following settings:  
   - Uncheck any options that may cause conflicts.  
   - Enable **PUT/GET communication** under the PLC communication settings.  
3. Confirm your configurations and click **Load**.  
4. **Start the module** on the PLC after loading.  

---

#### HMI Simulation  

1. Click on the **HMI screen** and start the **Runtime simulation**.  
2. Ensure the HMI is properly connected to the PLC.  
3. Use the **HMI Connection** section to verify or establish communication.
4. 
![image](https://github.com/user-attachments/assets/37ecc64f-eb88-46b5-84e9-f6353bd2b570)

![image](https://github.com/user-attachments/assets/692534a7-ad04-4b01-a68a-6c13bdb82c12)

![image](https://github.com/user-attachments/assets/b10da73b-cb03-4e3d-8cb6-ea16421eaa11)

![image](https://github.com/user-attachments/assets/b10da73b-cb03-4e3d-8cb6-ea16421eaa11)

---

#### Advanced Configuration  

1. If necessary, add a **communication module** (e.g., CP IE) for advanced setups.  
2. Reconfigure variables and readdress memory locations in the PLC as needed, especially if there are conflicts with the **Memory Clock**.  

---

#### Final Testing  

1. Test the system thoroughly by interacting with the HMI and PLC to ensure the logic and communications are functioning as expected.  
2. Make any necessary adjustments to the buttons, logic, or communication settings.  

--- 

Your SCADA system is now configured and ready to use!



![image](https://github.com/user-attachments/assets/6f901939-c441-4030-80d7-9e8dbf03f8c5)

![image](https://github.com/user-attachments/assets/6f901939-c441-4030-80d7-9e8dbf03f8c5)


![image](https://github.com/user-attachments/assets/b2706388-de3c-4ac9-ad17-307f2fd40f34)

![image](https://github.com/user-attachments/assets/54b928bd-1e81-40d8-bce0-5a6962c4a3de)



![image](https://github.com/user-attachments/assets/c58a85f1-54ac-4de7-8c99-3a271d31cb1d)
![image](https://github.com/user-attachments/assets/ccfd3f6b-1374-4441-887f-f4f234f8dfee)









SAVE AND DIVEDED SCREM :

![image](https://github.com/user-attachments/assets/93f6fa72-938e-4f93-802c-1d853dd7cb9c)

START SIMULATION FOR TEST :

![image](https://github.com/user-attachments/assets/0cc71613-6f2d-456d-aaf0-64d355d0450a)


DOWLOAD TO DEVICE :
![image](https://github.com/user-attachments/assets/9273cc1a-4206-4a47-ab4e-0592e3e93d09)

![image](https://github.com/user-attachments/assets/9b59429e-38ca-47e4-b647-f60cc309a553)

IS IMPORTANT DESSELECTED THIS:

![image](https://github.com/user-attachments/assets/67e2f806-7469-4442-97a9-973bb7d16bc3)

![image](https://github.com/user-attachments/assets/a1851af8-0cc7-41a7-8bf3-6992c149677f)

NECESERY TOO SELECTED PUT/GET:

![image](https://github.com/user-attachments/assets/397c031c-5729-49c0-b702-7faaaed7dcb3)

OK:
![image](https://github.com/user-attachments/assets/44799be4-db1b-4375-98aa-4c058cac0fb2)

OK AGAIN:

![image](https://github.com/user-attachments/assets/f0b68332-d62f-40b2-94b3-5aa3c978e4b9)


PUT ON PLC:
![image](https://github.com/user-attachments/assets/f3e718b1-4502-4850-8e00-f7c9909ace1b)

LOAD
![image](https://github.com/user-attachments/assets/b6477cc5-1af9-49ff-9edf-e1b6c4df0618)

START MODULE:
![image](https://github.com/user-attachments/assets/66618660-9ba3-49dc-aa7b-7a065be0d298)

AND FINISH

NOW CLICK ON DE SCREEN HMI:

START SIMULATION RT:

![image](https://github.com/user-attachments/assets/2bce4cca-cbf8-4777-a733-d49fa7551cd4)

GO ON CONNECTIONS AND INTERCONECTION BUF

![image](https://github.com/user-attachments/assets/f18edde0-ca4b-41dc-ba3a-f6065590fd77)

CLICK ON HMI_CONNECTION
![image](https://github.com/user-attachments/assets/6c99c61c-40ad-444e-a690-2f78c24c1188)







https://www.youtube.com/watch?v=96QfxMVIXyI



























 
