# REMOVING-RF-VULNERABILITIES-FROM-IOT-DEVICES

ABSTRACT-
RF vulnerabilities is a massive problem nowadays. If you see TV remote, AC remote, camera and car remotes RF have been using everywhere. The problem with RF security is that it always generates a signal with the same key which locked or unlock the system. RF signals are also unencrypted and It transfers signal through an unsecured channel so It suffers from key relay attack where the same key signal used to generate every time from a captured RF signal having the same key to make work to the system. Our problem statement is “Removing RF vulnerabilities to transfer data securely so that RF can avoid any types of relay attack threats”. we proposed a system which transferred data securely, In our system, we advise key rolling algorithm with a 2-way handshake, Key rolling algorithm rolls key which provides a new key every time of data transferring and 2-way handshaking provide synchronization between sender and receiver.


KEY ROLLING ALGORITHM-
The key rolling algorithm uses the symmetric keys in the both sides of sender and receiver for data accessing. It uses every time new key for each transmission. The key is stored in circular queue format so the after some particular interval the keys will repeat

The key rolling algorithm uses keys for the secure data transmission. The key values are made as set and stored in the circular queue. This key set is shared with the sender and receiver. When the data is transferred using this algorithm, then one of the blocks of the circular queue is selected as the key and stored. And to get access to the same data we have to  use the key set in the receiver side when the selected key matches the set then it can be accessed
