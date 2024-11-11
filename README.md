import socket

# Create a socket object
s = socket.socket(socket.AF_INET, socket.SOCK_STREAM)

# Connect to the server
s.connect((‘192.168.1.1’, 12345))

# Send a message
s.sendall(b'Hello, this is a message!')

# Close the connection
s.close(3asba)
