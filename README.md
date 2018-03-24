# Simple-Modbus-Master
## A simple Modbus Master Arduino Library  
(Original by Juan Bester  --> https://goo.gl/9au7R1)  
  
you can use it with the Simple Modbus Slave Library --> https://github.com/BlackBrix/Simple-Modbus-Slave
  
15/09/2014 - SMMv2rev2  
I have decided to rewrite some of the library to create easier abstraction and to add functions 5 and 6. I have also created a manual of sorts with lots of information to help getting started. I have also shared a link on my drive to all my communication information. The ones in question are modbus and RS485. It makes for a very good (and long) read. The library for the DUE differs only in the removal of the byteFornat parameter in modbus_configure().  
  
16/06/2014 - SMMv12  
Minor changes in the keywords.txt file.  
  
16/02/2014 - SMMv11  
Cleaned up comments and changed the BUFFER size to 64 which matches the new buffer value in the hardwareSerial core library in version 1.05 onwards.  


