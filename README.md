EXP-6:


 SCHEMATIC ENTRY AND SIMULATION OF CMOS INVERTER, CMOS NAND and CMOS NOR USING
 CADENCE TOOL AIM: 
 To design and simulate the CMOS inverter and observe the DC and transient
 responses using cadence tool.
 APPARATUS REQUIRED:
 1.Laptop with MobaXterm
 2.Cadence tool
 PROCEDURE SCHEMATIC ENTRY: 
 Creating a new library:
 1.In the library manager, execute File 
New library. The new library form appears.
2.In the new library form, type ‘my design lib’ in the
 name section. 
 3.In the field of directory section, verify that the path to the library is set to
 ~/Database / Cadence- analog – lab –bl3 and click ok.
 4.In the next ‘technology file for new library
 form select option attach to an existing tech file and click ok. VLSI-LAB-EXP-6
 5.In the ‘attach
 design library to technology file’ form, select gpdk045 form the cyclic field and click ok.
 6.After creating a new library you can verify it from the library manager. 7.If you right click on the ‘my
 design lib’ and select properties, you will find that gpdk045 library is attached as techlib to ‘my
 design lib’. Creating a schematic cell view:
 1.In the CIW or library manager, execute file – new – cell
 viw. 
 2.Setup the new file form as follows, Do not edit the library path file and the above might be
 different from the path shown in your form.
 3.Click ok when done the above setting. A black
 schematic window for the inverter design appears.
 Adding components to schematic: 
 1.In the
 inverter schematic window, click the instance fixed menu icon to display the add instance form.
 2.Click on the browse button. This opens up a library browser from which you can select
 components and the symbol view.
 3.After you complete the add instance form move your cursor to
 the schematic window and click left to place a component. LIBRARY NAME CELL NAME gpdk045
 PMOS gpdk045 NMOS
 4.This is a table of components for building the inverter schematic.
 5.After entering components, click cancel in the add instance form or press ESC with your cursor in the
 schematic window.

 ![Screenshot (61)](https://github.com/hemakaruna/VLSI-LAB-EXP-6/assets/160728787/8db56d8a-49d2-4350-8be7-c7e83a79df26)


  Adding pins to schematic: 
  1.Click the pin fixed menu icon in the schematic window. You can execute
 create pin or press ‘p’.
 2.Add pin form appears. Type the following in the ADD pin form in the next
 order leaving space between the pin. PIN NAMES DIRECTION Vin,Vdd,Vss Input Vout Output
 3.Select cancel and then the schematic window enter window file or press the f bind key.
 Adding wires to schematic: 
 1.Click the wire (narrow) icon in the schematic window. 
 2.In the schematic window click on a pin of one of your components as the first point for your wiring. A diamond
 shape appears over the starting point of this wire.
 3.Follow the prompts at the bottom of design  window and click left on the destination point for your wire. A wire is routed between the source
 and destination points. 
 4.Complete the wiring as shown in the figure and when done wiring press
 ECS key in the schematic window to cancel wiring.
 Saving the design: Click the check and save icon
 in the schematic editor window observe CIW output for any errors.
 BUILDING THE INVERTER TEST DESIGN:
 Creating the inverter test cell view: 
 1.In the CIW or library
 manager, execute file – new – cell view. 
 2.Setup the newfile as shown below.
 4.To set for DC analysis a.In the analysis section select DC. b.Turn on
 save DC operating point. c.Turn on the component parameters. d.Double click the select Vpulse
 source or Type V0 (capital V zero). e.Select the DC voltage in the select window parameter and click
 in the form start and stop voltages are 0 to 1.8. f.Select the enable button and click apply and then
 click ok. 
 Selecting output for plotting:
 1.Execute the o/p’s to be plotted -select on sschematic in the
 simulation window. 
 2.Follow the prompt at the bottom. Click on the o/p net vout input vin of the
 inverter. Press esc with the cursor after selecting.
 Running the simulation:
 1.Execute the simulation
 Netlist and run in the simulation window to start the simulation on the icon. This will create the
 netlist as well as run the simulation.
 2.When the simulation finishes the transient and DC plots
 automatically will be popped up along with netlist

 ![image](https://github.com/hemakaruna/VLSI-LAB-EXP-6/assets/160728787/8d3b9565-fd38-4233-8d88-c3027d9a2ccc)

ANALOG SIMULATION WITH SPECTRA: 
Starting the simulation environment: 
 
In the Inverter-test schematic window execute launch – ADEL. The variable virtuoso 
analog design environment (ADE) simulation window appears. Choosing a simulator:  
the simulation window (ADE) execute setup – simulator / directory / host.  
 
In the choosing simulator form, set the simulator field to specra and click ok.  
In the simulation window 
(ADE) execute the setup model libraries. To complete, move the cursor and click ok. 
Choosing Analysis: 
Click the choose- Analysis icon in the simulation window (ADE).  
The choosing analysis 
form appears.  
To Setup the transient analysis.  
the stop time as 100ns   
In the analysis section select tron.  
Set Click at the moderate or enabled button and the bottom and then click apply.  
To set for DC analysis  
operating point.  
In the analysis section select DC.  
Turn on save DC 
Turn on the component parameters.  
Double click the select Vpulse 
source or Type V0 (capital V zero). 
Select the DC voltage in the select window parameter 
and click in the form start and stop voltages are 0 to 1.8.  
Select the enable button and 
click apply and then click ok. 
Selecting output for plotting: 
Execute the o/p’s to be plotted -select on sschematic in the simulation window. 
Follow the prompt at the bottom. Click on the o/p net vout input vin of the inverter. Press esc with 
the cursor after selecting. 
Running the simulation: 
Execute the simulation Netlist and run in the simulation window to start the simulation 
on the icon. This will create the netlist as well as run the simulation.  
When the simulation 
finishes the transient and DC plots automatically will be popped up along with netlist. 

![image](https://github.com/hemakaruna/VLSI-LAB-EXP-6/assets/160728787/4e9753e8-3f90-490f-a8c3-28f75d5da5bb)

![image](https://github.com/hemakaruna/VLSI-LAB-EXP-6/assets/160728787/641e686a-dd22-4f2d-9895-c0af592b55a7)

CMOS NAND GATE NAND SCHEMATIC

![image](https://github.com/hemakaruna/VLSI-LAB-EXP-6/assets/160728787/e9c5d1ae-706c-411e-ba3a-a2f33e5d54e7)

NAND TEST CELL VIEW

![image](https://github.com/hemakaruna/VLSI-LAB-EXP-6/assets/160728787/94e57c9d-3154-4381-a3ff-ac254f1a4a38)

NAND SIMULATION WITH SPECTRA CMOS NOR GATE NOR SCHEMATIC 

![image](https://github.com/hemakaruna/VLSI-LAB-EXP-6/assets/160728787/2957d722-aeb5-4504-8eec-f1aee38b5107)

NOR TEST CELL VIEW 

![image](https://github.com/hemakaruna/VLSI-LAB-EXP-6/assets/160728787/1b9effa9-6b12-4e19-9264-bdf440677e7f)

NOR SIMULATION WITH SPECTRA

![image](https://github.com/hemakaruna/VLSI-LAB-EXP-6/assets/160728787/361a475f-8af9-4b9a-9489-055557ebf126)

RESULT

Thus the design and simulation the CMOS inverter and observe the DC and transient 
responses using cadence tool is verified successfully.
