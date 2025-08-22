# Errors and Parity

Communications links can be affected by electrical noise and now and then, a spike of noise can cause a bit error in a circuit.

<figure><img src="https://johnoraw.gitbook.io/pnt/~gitbook/image?url=https%3A%2F%2F365966430-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FjPKaxBv8yVv6wzBRST0X%252Fuploads%252FtV7S21V7mfoBSb0xmh5K%252Fimage.png%3Falt%3Dmedia%26token%3D9fab06a4-c38f-419f-b533-ee0000670f52&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=4ae27386&#x26;sv=2" alt=""><figcaption></figcaption></figure>

The noise voltage will be superimposed on the signal, the receiver will be unable to distinguish between a symbol caused by noise and the original intended signal.

To counteract the effect of noise causing a bit error, we use _parity_. We add up all the bits in the original signal. There were four 1’s and that is an even number, so we could make our parity value 0. If we added them up and they made an odd number, we could make our parity value 1. We can then add a parity bit to the end of our data, before the stop bit.

Parity will allow us to find any single bit error in a character. It will not allow us to detect two or more bits of error (why?).
