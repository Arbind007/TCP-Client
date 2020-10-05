# TCP-Client


socket.send() expected a bytes type argument but data is an unicode string. This happens only in python3 socket.send() takes a bytes parameter. Thus we have to convert the string data into bytes using str.encode() and then use .decode() to retrive the data. 
