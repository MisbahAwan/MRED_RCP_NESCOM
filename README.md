# MRED_RCP_NESCOM
High-ordered transformations framework

MRED Prototype Manual

1.	Download the MRED Prototype RCP from Google Drive by following the link given on the following GitHub repository:

   https://drive.google.com/drive/u/2/folders/1YFCD87fViwphx3jfVAePBYEISvyK4cPV

2.	Save it anywhere in the system and extract it in a folder. You will get the following directory structure inside the “exe” folder:

 ![image](https://github.com/user-attachments/assets/b3f3f01e-cc77-4139-b068-b005846016c9)


3.	Run “MRED” exe inside “eclipse” folder:

 
![image](https://github.com/user-attachments/assets/25f9fea2-eb12-4ee5-81d7-a7fb2a40deed)



4.	MRED editor, showing blended modeling environment, will appear as shown below:

 ![image](https://github.com/user-attachments/assets/1f7c9216-29c6-4d42-bdbf-f19df6974e4f)


5.	The MRED editor supports three concrete syntaxes including Timed Automata (Uppaal), C language and System Verilog along with the tree representation of the abstract model. All four modules are functional and editable.

6.	 Moreover, the MRED editor supports three-way back and forth seamless runtime transformations against the well-defined subset of transformation rules.

7.	For example:

   ![image](https://github.com/user-attachments/assets/91104d66-8727-4158-9b46-46a2f45ed929)


a.	Update the variable “int New_Mode_Flag” in the Verilog Tab and change it to “int New_Mode_Flag_Updated”.

b.	Press the “Save” button from the menu bar.

c.	The transformations will run seamlessly in the backend and update the other three Tabs including Uppaal Tab, C Language Tab and the Tree Editor.

d.	See image below for visual details.
 


8.	You can run the same transformations from other concrete syntaxes e.g. from C to all others etc. etc.

9.	Please note that if you make updations in more than one Tabs then on pressing the “Save” button the transformations will be executed on the basis of last updated Tab.



-	THE END 	-


