# Sine-Wave-Generator-using-Verilog
- This is a simple project that deals with the generation of Sine Waves. The maximum clock frequency obtained was 200MHz. 
- Power Analysis of this particular module gives a clear discription of the power suage and types of power usage which are attatched below. 
<img width="323" alt="image" src="https://user-images.githubusercontent.com/99958597/226159560-5b7d7b4a-cda8-46a9-a4a6-b670ac371acb.png">

- The samples of the sine wave were generated using Matlab. I have taken 100 samples in this project because the more samples you take the more finer will be the sime wave. 
# Commands for generating Sine Wave Samples:
 - t = 0 : pi/50 : 2*pi % for 100 samples, for 20 samples take pi/20.insteat of pi/50.
 - int32(sin(t)*10000/128) % 128 for 8-bit output, for 6-bit output take 512 instead of 128.  

# Tools Used: 
- Cadence NC Launch 
- Xilinx Vivado
- Matlab
