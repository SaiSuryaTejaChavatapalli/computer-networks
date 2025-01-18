# Terminologies

## Protocols:

⇒ Network protocols are a set of rules and regulations setup to communicate and share information over a network.

Ex: HTTP,SMTP,UDP, TCP

## Packets:

⇒ In order to share data, we can’t send big chunk of data over the network.

⇒ so we divide the data into smaller chunks, these small chunks are called as packets.

Ex: Easily manageable, fast, if some chunk is lost, we can easily recover it compare to large file.

## Address:

⇒ Sending messages over the network requires the destination details, This details uniquely identifies the end system (Phone, laptop) is called address.

Ex: IP address

## Ports:

⇒ Any machine could be running many apps, In order to distinguish these apps for receiving messages, we use ports. (Port number)

Ex: In one phone many process are happening, out communication receives to which app decides using ports

IP address + Port = Socket

⇒ Ports help you get the packets to specific process on the host.

⇒ Every process has 16 bit port number

0-2^16= 65535

⇒ 0 to 1023 = well known ports

Ex: Port 80 = http, Port 443= https

⇒ 1024-49152= registered ports

⇒ They are used by specific, potentially proprietarily apps / process that are known but not system defined

Ex: Third party apps like node server , mongo server can use these range of port 3000

→ SQL server Port number : 1433

→ Mongo server : 27017

⇒ 49152 to 65535 → Dynamic ports → For Future purposes.

⇒ users can use these ports

⇒ when the above range is filled, future purpose can use it

⇒ We can change those ports, if we want, if we don’t want to follow protocols
