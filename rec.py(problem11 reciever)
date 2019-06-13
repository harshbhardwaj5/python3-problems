#!/bin/python2

import socket
recv_ip="127.0.0.1"
recv_port=4444
s=socket.socket(socket.AF_INET,socket.SOCK_DGRAM)
s.bind((recv_ip,recv_port))

while 4>2 : 
	data=s.recvfrom(100)
	print("msg from sender",data[0])
	print("sender ip+socket",data[1])
	s.sendto("ok gotca",data[1])
	break
s.close()
