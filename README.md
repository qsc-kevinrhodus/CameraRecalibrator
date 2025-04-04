# Camera Recalibrator

Instructions:

 1. Install User Component in Q-SYS Designer
 2. Drag in a copy of the "Camera Recalibrator" component to design
 3. When prompted to Create a Named Component, select Yes
 4. Enable Script Access for all cameras in the design you wish to have re-calibrated
 5. Emulate / Go Online with the Core and open Q-SYS Administrator
 6. Create a Command Schedule Event with the following settings:
	 **Name:** Recalibrate Cameras
    
	 **Command:** Ad-Hoc Command
    
	 **Command Type:** Control Command
    
	 **Controls:** CameraRecalibrate
    
	 **Enabled:** Yes
    
	 **Occurs:** Daily at specified time
    
	 **Loop:** No
	 
		  
