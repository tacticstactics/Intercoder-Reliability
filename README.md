# Intercoder-Reliability
Intercoder-Reliability(ICR) Test Emulation.<br>

[Hello-World-Reliability](https://github.com/tacticstactics/Intercoder-Reliability/blob/e1bb349a76f2fd55ace4a4aa438a85ad9ca695d4/Hello-World-Reliability.ipynb)<br>
Convert the string to binary data and consider whether the filtering process conveys the string accurately.<br>

Convert string (e.g. 'Hello World') to binary, and create analog data as ndarray.<br>
The ndarray is processed by gaussian / buterworth filter.<br>
<br>
When using Scipy's signal.windows.gaussinan, convolve was used.<br>
When using signal.butter, lfilter was used.<br>
<br>
Filtered ndarray is again converted to binary.<br>
The binary is again converted to string.<br>
Compare the two strings, and judge if transmission was successful or not.<br>




Butterworth Filter<br>
![1](https://github.com/user-attachments/assets/8dd5d73d-691c-4684-b533-7da67fa73082)
![2](https://github.com/user-attachments/assets/02ea8659-7b66-4945-8255-e39d0d664f03)
