#!/bin/python2

import socket
recv_ip="127.0.0.1"
recv_port=4444
s=socket.socket(socket.AF_INET,socket.SOCK_DGRAM)

while 4>3 :
  msg=raw_input("plz enter your message")
  if(len(msg) > 150):
     print("length exceded")

  s.sendto(msg,(recv_ip,recv_port))
  print(s.recvfrom(10))
  s=raw_input("do you wanna quit the chat")
  if(s=="yes"):
	break
	
