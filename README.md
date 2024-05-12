# VLSI-LAB-EXP-6
# Adding pins to schematic:

1.Click the pin fixed menu icon in the schematic window. You can execute create pin or press ‘p’.
A2.dd pin form appears. Type the following in the ADD pin form in the next order leaving space between the pin. PIN NAMES DIRECTION Vin,Vdd,Vss Input Vout Output
3.Select cancel and then the schematic window enter window file or press the f bind key. Adding wires to schematic:
4.Click the wire (narrow) icon in the schematic window.
5.In the schematic window click on a pin of one of your components as the first point for your wiring. A diamond shape appears over the starting point of this wire.
6.Follow the prompts at the bottom of design window and click left on the destination point for your wire. A wire is routed between the source and destination points.
7.Complete the wiring as shown in the figure and when done wiring press ECS key in the schematic window to cancel wiring.
8.Saving the design: Click the check and save icon in the schematic editor window observe CIW output for any errors.

# BUILDING THE INVERTER TEST DESIGN: Creating the inverter test cell view:

1.In the CIW or library manager, execute file – new – cell view.
2.Setup the newfile as shown below.
3.Click ok when done. A blank schematic window for the inverter test design appears.
4.Using the components list and properties/ comments in this table build the inverter test schematic. LIBRARY NAME CELL VIEW NAME PROPERTIES/COMMENTS My design lib Inverter Symbol Analog lib Vpulse Voltage1 = 0, 5.Voltage2 = 1.8, delay Time = 0, Rise time=Fall time=1ns Period=20ns Analog lib Vdc, gnd Vdc = 1.8v
6.Add the above components using create – instance or by pressing I.
7.Click the wire (narrow) icon and wire your schematic.
8.Click create wire name or press c to name the i/p (vsin) and output wires as in below schematic.
9.Click on the check and save icon to save the design.
![WhatsApp Image 2024-05-12 at 20 00 17_64b28ada](https://github.com/S-Mohankumar/VLSI-LAB-EXP-6/assets/163832108/0eb6d885-39f4-4bc4-a16a-4995626d67cc)
# ANALOG SIMULATION WITH SPECTRA: Starting the simulation environment:

1.In the Inverter-test schematic window execute launch – ADEL. The variable virtuoso analog design environment (ADE) simulation window appears. Choosing a simulator:
2.In the simulation window (ADE) execute setup – simulator / directory / host.
3.In the choosing simulator form, set the simulator field to specra and click ok.
4.In the simulation window (ADE) execute the setup model libraries. To complete, move the cursor and click ok. Choosing Analysis:
5.Click the choose- Analysis icon in the simulation window (ADE).
6.The choosing analysis form appears.
7.To Setup the transient analysis. a. In the analysis section select tron. b. Set the stop time as 100ns c. Click at the moderate or enabled button and the bottom and then click apply.
8.To set for DC analysis a. In the analysis section select DC. b. Turn on save DC operating point. c. Turn on the component parameters. d. Double click the select Vpulse source or Type V0 (capital V zero). e. 9.Select the DC voltage in the select window parameter and click in the form start and stop voltages are 0 to 1.8. f. Select the enable button and click apply and then click ok.
# Selecting output for plotting:

1.Execute the o/p’s to be plotted -select on sschematic in the simulation window.
2.Follow the prompt at the bottom. Click on the o/p net vout input vin of the inverter. Press esc with the cursor after selecting.
# Running the simulation:

1.Execute the simulation Netlist and run in the simulation window to start the simulation on the icon. This will create the netlist as well as run the simulation.
2.When the simulation finishes the transient and DC plots automatically will be popped up along with netlist.
![WhatsApp Image 2024-05-12 at 20 00 46_5a19ba1a](https://github.com/S-Mohankumar/VLSI-LAB-EXP-6/assets/163832108/f298b6a0-7dc8-465a-9037-840a11af503d)
![WhatsApp Image 2024-05-12 at 20 01 09_949437f9](https://github.com/S-Mohankumar/VLSI-LAB-EXP-6/assets/163832108/509bae17-785b-4ba2-8bdf-2c2d6c6d4fa5)
# CMOS NAND GATE

# NAND SCHEMATIC
![WhatsApp Image 2024-05-12 at 20 01 30_73cda01c](https://github.com/S-Mohankumar/VLSI-LAB-EXP-6/assets/163832108/dcf95832-38b7-44ef-8dd5-0039415394a5)
# NAND TEST CELL VIEW
![WhatsApp Image 2024-05-12 at 20 01 48_486d9ff8](https://github.com/S-Mohankumar/VLSI-LAB-EXP-6/assets/163832108/7c3af961-bae8-4cd1-94df-d8d0ae2409fe)
# NAND SIMULATION WITH SPECTRA
![WhatsApp Image 2024-05-12 at 20 02 08_aa76bacc](https://github.com/S-Mohankumar/VLSI-LAB-EXP-6/assets/163832108/da755f90-a604-4454-84a7-7cef1a79e98b)
# CMOS NOR GATE NOR SCHEMATIC
![WhatsApp Image 2024-05-12 at 20 02 36_4cc7514d](https://github.com/S-Mohankumar/VLSI-LAB-EXP-6/assets/163832108/35061de4-00af-4fd3-8690-c27283a6ae15)
# NOR TEST CELL VIEW
![WhatsApp Image 2024-05-12 at 20 02 55_1f40c3fe](https://github.com/S-Mohankumar/VLSI-LAB-EXP-6/assets/163832108/527e7674-f0ee-4fa0-9c67-40af84141ef9)







