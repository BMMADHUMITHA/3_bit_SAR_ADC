# 3_bit_SAR_ADC
The successive approximation converter performs basically a binary search through all possible quantization levels before converging on the final digital answer. An N-bit register controls the timing of the conversion where N is the resolution of the ADC. VIN is sampled and compared to the output of the DAC. The comparator output controls the direction of the binary search, and the output of the successive approximation register (SAR) is the actual digital conversion.

<img width="419" alt="image" src="https://github.com/BMMADHUMITHA/3_bit_SAR_ADC/assets/134037700/7ab3dcf8-7ddd-4afa-91d7-43d42a2b9e8a">

# Successive Approximation Algorithm:
<img width="386" alt="image" src="https://github.com/BMMADHUMITHA/3_bit_SAR_ADC/assets/134037700/6c1178c7-d72f-4aaa-962c-9e0078bb0308">

# Circuits to build 3 bit SAR ADC
# comparator
![image](https://github.com/user-attachments/assets/4099347e-e550-4695-8cf4-498c7b2541ac)
<img width="434" alt="image" src="https://github.com/BMMADHUMITHA/3_bit_SAR_ADC/assets/134037700/d390fdd1-6382-4f5e-b130-96c8e130aad2">

# shift register
![image](https://github.com/user-attachments/assets/e98e5eba-fbf8-489d-ab60-447ef05b5d04)
<img width="437" alt="image" src="https://github.com/BMMADHUMITHA/3_bit_SAR_ADC/assets/134037700/5bff5ec9-2992-459f-beaf-5379deaa3de6">

# D flip flop
![image](https://github.com/user-attachments/assets/2c5f252b-04cd-4128-98d7-c415e9852722)
<img width="479" alt="image" src="https://github.com/BMMADHUMITHA/3_bit_SAR_ADC/assets/134037700/37c25e5f-1f84-4561-a6c4-31572072babb">

# JK flip flop
![image](https://github.com/user-attachments/assets/3c9abd57-c53e-4276-9bca-c9695e3add97)
<img width="465" alt="image" src="https://github.com/BMMADHUMITHA/3_bit_SAR_ADC/assets/134037700/fba60c19-2d81-45a3-bfae-9959729118de">

# Sample and Hold
<img width="453" alt="image" src="https://github.com/BMMADHUMITHA/3_bit_SAR_ADC/assets/134037700/695f4e37-e511-4790-8fa5-12a114143750">

# DAC (Digital to Analog Converter)
![image](https://github.com/user-attachments/assets/de483147-c64d-4535-8af7-6d4b0aca9824)
<img width="479" alt="image" src="https://github.com/BMMADHUMITHA/3_bit_SAR_ADC/assets/134037700/2ce09448-bb9a-4c83-b327-cf96f2ccb0ee">

# SAR logic when Din= 111
![image](https://github.com/user-attachments/assets/b41cbc97-da75-4cb1-835e-f9396b8d1cc8)
<img width="478" alt="image" src="https://github.com/BMMADHUMITHA/3_bit_SAR_ADC/assets/134037700/a9133c1d-4aa5-4fec-8b52-25e1ecb31d77">

# SAR logic when Din= 000
<img width="478" alt="image" src="https://github.com/BMMADHUMITHA/3_bit_SAR_ADC/assets/134037700/9b3f1b5e-5631-4fb8-a313-d26e71affd27">

# 3 bit SAR ADC:
<img width="557" alt="image" src="https://github.com/BMMADHUMITHA/3_bit_SAR_ADC/assets/134037700/cb757d6d-e826-4480-8cb3-7c37b377a9dc">

# Internal clock generator:
![image](https://github.com/user-attachments/assets/fc348a1d-eb6b-4c1c-8614-89032037018b)

# Delay cell:
![image](https://github.com/user-attachments/assets/617b99af-c51e-4c1e-b2e1-eecb1545cfa6)

# 2 input NAND Gate:
![image](https://github.com/user-attachments/assets/bd6ce0bd-a54f-4581-a19e-63d38d877aff)
![image](https://github.com/user-attachments/assets/9929953b-3e92-4fb4-b835-514687652896)

# 3 input NAND Gate:
![image](https://github.com/user-attachments/assets/c840b0e3-90e4-4720-9441-c01f6f5153f9)
![image](https://github.com/user-attachments/assets/f55a9a42-9860-474b-94a6-ceb7a919c591)

# OR gate:
![image](https://github.com/user-attachments/assets/ecdfe485-3d88-4679-a9dc-71e455997eca)
![image](https://github.com/user-attachments/assets/c022c8f6-a8a4-4ab2-8e54-416d9cc2ad91)

# XOR Gate:
![image](https://github.com/user-attachments/assets/9c3291df-6cb0-412e-9c9b-eb605d267947)
![image](https://github.com/user-attachments/assets/56523f0c-5989-4be3-8012-60cf4338e991)

# Inverter:
![image](https://github.com/user-attachments/assets/ef9e7565-0a32-40b7-9526-91e6f93a6583)
![image](https://github.com/user-attachments/assets/57537eb5-9e02-44e2-bbdf-af071ad14118)

# Prepared By:
B M Madhumitha

# References:
1. CMOS circuit design, layout and simulation - R Jacob Baker
2. CMOS Analog Integrated circuits Data Converters, Phase locked loops, and their applications – Tertulien Ndjountche










