# Tone Reservation (TR) PAPR reduction technique.
In this technique, some OFDM subcarriers are reserved. These reserved subcarriers don’t carry any data information,
they are only used for reducing PAPR. This method is called Tone Reservation.
There are different methods for tone reservation technique, such as Kernel TR method and Scaling Signal To Clipping Noise Ratio (TR-S-SCR) method.
Each method will be explained in detail with the performance analysis.

# Kernel TR
Kernel TR method creates a reference kernel vector 𝑝, which is an impulse function with FFT size,
in the kernel vector the reserved tones positions will be set to one, and all other values are set to zero. 
![image](https://github.com/Metwaly-yahia/Tone_Reservation/assets/81784667/2f89baf5-e3f5-4ba5-b167-e171a707b108)
#…Then we do IFFT for X & P.

# Procedure of Gradient Algorithm

![image](https://github.com/Metwaly-yahia/Tone_Reservation/assets/81784667/9009e7e9-90fc-422d-a73a-8d1455622bbc)

![image](https://github.com/Metwaly-yahia/Tone_Reservation/assets/81784667/fe25df85-9f79-4012-af33-a38d69bc0138)

![image](https://github.com/Metwaly-yahia/Tone_Reservation/assets/81784667/07d3605e-e8a3-4ae4-8de6-7ea5bcd14aad)





