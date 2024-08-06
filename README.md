# CoERead

CoERead를 위해선 FB_EcCoESdoRead 기능을 사용해야함 (링크)[https://infosys.beckhoff.com/english.php?content=../content/1033/tcplclib_tc2_ethercat/56996235.html&id=]


sNetID 값  
![image](https://github.com/user-attachments/assets/e57f6c91-b552-4861-b3e1-f79b7851bf21)
  
nSlaveAddr 값  
![image](https://github.com/user-attachments/assets/01b2add6-1ac0-4650-bf2f-5f5be41c338f)
  
nIndex, nSubIndex 값  
nIndex는 32C0, nSubIndex는 17  
![image](https://github.com/user-attachments/assets/15e77fff-4c0d-4191-bfd2-85b82f372f47)
  
pDstBuf은 읽은 값을 저장하려는 PLC변수의 주소  
Ex) ADR(torque)  

cbBufLen은 읽은 값을 저장하려는 PLC변수의 크기  
Ex) Sizeof(torque)
