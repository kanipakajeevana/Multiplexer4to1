# Multiplexer4to1
# AIM
To simulate and synthesis multiplexer using vivado
# APPARATUS REQUIRE
vivado
# PROCEDURE
STEP:1 Start the vivado software, Select and Name the New project.
STEP:2 Select the device family, device, package and speed.
STEP:3 Select new source in the New Project and select Verilog Module as the Source type.
STEP:4 Type the Fille Name and module name and Click Next and then finish button. Type the code and save it.
STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.
STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.
STEP:7 compare the output with truth table.
# Truth Table
![image](https://github.com/RESMIRNAIR/Multiplexer4to1/assets/154305926/f1dac9e1-e938-4072-bfa9-c17a0a54b7c7)
# Circuit Diagram
![image](https://github.com/kanipakajeevana/Multiplexer4to1/assets/170450203/fe22aaf1-0f30-48eb-9534-539a82443756)
# VERILOG CODE
module mux(a, b, c, d, se, sl,y);
input a,b,c,d, so, s1;
output y;
assign y-s1 ?(s0?d:c): (s0?b:a);
endmodule
# OUTPUT
![image](https://github.com/kanipakajeevana/Multiplexer4to1/assets/170450203/f0d33055-cad2-4ae8-9e9c-640bfaccb23c)
# RESULT
Thus, the verilog program for Multiplexer4to1 has been simulated and verified successfully.



