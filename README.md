# **Macropad — Volume + Macro Controller**



##### This is my custom macropad built for Hack Club Blueprint.

##### It’s a small desk controller that lets me:



* ###### Control volume with a rotary encoder

###### 

* ###### Play / pause with encoder press

###### 

* ###### Use shortcut keys (Chrome, Copy, Paste, LED mode, minimize app)

###### 

* ###### Show animations + volume on an OLED

###### 

* ###### Control RGB effects with presets using one of the keys



###### I designed the PCB in KiCad, modeled the case in Fusion, and programmed it using KMK.



### **🖼️ Screenshots**

###### 

* #### Overall Hackpad
![Screenshot of the fully assembled hackpad to be updated after assembly](overall_macropad.png)
#### 

* #### Schematic
![Screenshot of the schematic](macropad_schematic.png)
#### 

* #### PCB Layout
![Screenshot of the pcb board](macropad_pcb_layout.png)
#### 

* #### Case + How It Fits Together
![Screenshot of the assembly](macropad_3d_model.png)
###### 

###### 

## ***🧩 Features***

###### 

* #### 5 mechanical keys

#### 

* #### EC11 rotary encoder with push

#### 

* #### SSD1306 0.91" OLED (128×32)

#### 

* #### 10x SK6812 mini RGB LEDs (underglow)

#### 

* #### USB HID (macros + media control)

#### 

* #### Animation when idle, volume overlay when adjusting

#### 

* #### LED presets controlled by a key

###### 

## ***🧾 Parts List***

#### **Part 				                  Quantity		   Notes**

#### Seeed XIAO RP2040  		             1			     Main controller

#### MX mechanical switches	  	         5			     With keycaps

#### EC11 rotary encoder		             1			     With push button

#### SSD1306 OLED, 0.91", 4-pin	         1			     I2C (GND-VCC-SCL-SDA)

#### SK6812 MINI-E LEDs		              10			     Addressable RGB

#### 1N4148 diodes			                 5			     One per switch

#### M3 heat-set inserts		             2		       For mounting

#### M3×16mm screws	                     2           For PCB mounting

#### 3D printed case + plate	           1	         Custom Fusion design





## **⚙️ Firmware**

###### 

##### **Framework: KMK**

###### 

### **Functions:**

###### 

##### Volume up/down (encoder)

##### 

##### Play / pause (encoder press)

##### 

##### Chrome launch

##### 

##### Copy / Paste

##### 

##### LED mode toggle

##### 

##### Minimize apps

#####

##### Idle animation resumes after volume change
