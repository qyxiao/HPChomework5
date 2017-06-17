# homework3
Qiyu Xiao(qx344)


Below are performance of 100 iterations for different work group size run in Cuda3 

| work group size | 8 | 12 | 16 | 18 | 20 |
| --- | --- | --- | --- | --- | --- | 
| time used(s) | 0.001660 | 0.001712 | 0.001563 | 0.001631 | 0.001748 | 
| processed pixels/s | 130.157967 | 126.173612  | 138.158878 | 132.431793 | 123.545038 | 
| bandwidth | 1.041264 | 1.009389 | 1.105271 | 1.059454 | 0.988360 | 
| Flop/s | 6.292970 | 6.100331 | 6.679803 | 6.402906 | 5.973243 | 

For 100 iterations in different devices:  
Cuda3 (Tesla T10 Processor)  
0.001563 s 
138.158878 MPixels/s  
1.105271 GBit/s  
6.679803 GFlop/s   
 
Cuda1 (GeForce GTX TITAN Black)  
0.004570 s  
47.264692 MPixels/s  
0.378118 GBit/s  
2.285187 GFlop/s  
  

Original Plot 
![image](https://github.com/qyxiao/HPChomework5/blob/master/Plot/test.jpg)


Plot after 1 operation
![image](https://github.com/qyxiao/HPChomework5/blob/master/Plot/output1.png)


Plot after 50 operation
![image](https://github.com/qyxiao/HPChomework5/blob/master/Plot/output50.png)


Plot after 100 operation
![image](https://github.com/qyxiao/HPChomework5/blob/master/Plot/output100.png)


Plot after 200 operation
![image](https://github.com/qyxiao/HPChomework5/blob/master/Plot/output200.png)


