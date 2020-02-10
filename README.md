# JavaUDPServer
DatagramSocket and Threading used for this aim

In this program, me and my friend Emre Donmez created a JAVA UDP Server by using thread library of Java.
Main objective in this program was to create a UDP server with selecvtive repeat algorithm. In selective
repeat algorithm, server has a windows size which is a parameter of the program which can be given by hand 
using terminal. After sending packets server waiting for acknowledge from client and increases initial window
number if acknowledge comes. If there happens some errors and lost packets happens, server sends the lost packet
only and continueu to sending next packet. 
