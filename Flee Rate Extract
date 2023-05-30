import binascii
for i in range(0,508):
    with open(str(i)+".bin","rb") as f:
        hexdata = binascii.hexlify(f.read())
    x = 0
    array = []
    while x < len(hexdata):
        array.append((int(str(hexdata[x:x+2])[2:-1], 16)))
        x+=2
    if array[24] != 0:
        print((i, array[8], array[24]))
        
