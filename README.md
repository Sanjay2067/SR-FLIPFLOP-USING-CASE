# SR-FLIPFLOP-USING-CASE

**AIM:**

To implement  SR flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

SR Flip-Flop SR flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, SR latch operates with enable signal. The circuit diagram of SR flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/0f710028-ad52-4d3e-9276-8714cf023a25)

 
This circuit has two inputs S & R and two outputs Qtt & Qtt’. The operation of SR flipflop is similar to SR Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of SR flip-flop.

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/dabfc4f4-87e3-4cbc-9472-f89ee1b5ed30)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, SR flip-flop can be used for one of these three functions such as Hold, Reset & Set based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of SR flip-flop. Present Inputs Present State Next State

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/dd90d16c-aec5-4290-a586-e2346b1e9eb5)

 
By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. The three variable K-Map for next state, Qt+1t+1 is shown in the following figure.

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/473efad6-d70b-4ca7-aeb7-898bbfca319f)

 
The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=S+R′Q(t)Q(t+1)=S+R′Q(t)

**Procedure**

/*1.Type the program in Quartus software. 2.compile and run the program. 3.generate the RTL schematic and save the logic diagram. 4.create nodes for inputs and outputs to generate the timing diagram. 5.for different input combinations generate the timing diagram.*/

**PROGRAM**

/* Program for flipflops and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/




![WhatsApp Image 2024-12-11 at 11 02 01](https://github.com/user-attachments/assets/9d433e88-147a-403e-958f-54a6908b06f7)










**RTL LOGIC FOR FLIPFLOPS**





![WhatsApp Image 2024-12-11 at 11 02 01](https://github.com/user-attachments/assets/b66b7f87-c553-4ad8-b927-4f4b48e90d73)








**TIMING DIGRAMS FOR FLIP FLOPS**









![WhatsApp Image 2024-12-11 at 11 02 40](https://github.com/user-attachments/assets/078e9091-608f-4e63-8eea-ac346ee8ba0c)







**RESULTS**
Thus to implement  SR flipflop using verilog and validating their functionality using their functional tables is verified
