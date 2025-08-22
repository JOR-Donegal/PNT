# Parallel Links

Another strategy for data communications is to pass a byte (8 bits) or a word (16 or 32 bits) at a time. Imagine two computers have a connection with eight data lines, D0-D7. Now I can transmit a byte at a time. If the link speed is the same as serial, I now have eight-times the data transfer rate. This would seem to be a far better solution than serial.

Unfortunately, once our links are very fast, we start running into problems. Every one of the eight links must have the same signal transfer characteristics, or we end up with bits arriving out of alignment.

Most modern systems use multiple serial links instead of _parallel links_.

<figure><img src="https://johnoraw.gitbook.io/pnt/~gitbook/image?url=https%3A%2F%2F365966430-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FjPKaxBv8yVv6wzBRST0X%252Fuploads%252FSthhObtsXQWIelQ2L3uL%252Fimage.png%3Falt%3Dmedia%26token%3D4d247ba2-71bc-4519-ba5c-92139e92dc3e&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=2639961a&#x26;sv=2" alt=""><figcaption></figcaption></figure>
