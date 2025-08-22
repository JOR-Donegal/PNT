# Analog and Digital

We tend to have two distinct types of signal which we deal with. The word _analogue_ means that we are representing a value which continuously varies. For example, the fuel gauge in a car can indicate from full to empty and can indicate any value in between. An analogue signal has a theoretically infinite resolution.

_Digital_ systems have distinct values like “1” or “0”. If I have a digital fuel gauge, it typically shows 10 steps from full to empty. In circuits, we tend to deal with _logic levels_ where for example +5V is a one and 0V is a zero.

A computer is primarily made up of digital components and circuits which tend to have very defined signal levels to represent ones and zeros.

A guitar amplifier is (probably!) entirely made of analogue circuits; typically, a pre-amplifier and a power amplifier. And the really fun ones still use thermionic valves (look it up).

A telephone exchange will have both types of circuit, analogue electronics to process incoming and outgoing voice signals to the user and digital circuits to transmit voice between exchanges.

A signal with a one or zero level is binary, the signal will be above a threshold value for 1 and below a threshold value for 0.

<figure><img src="https://johnoraw.gitbook.io/pnt/~gitbook/image?url=https%3A%2F%2F365966430-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FjPKaxBv8yVv6wzBRST0X%252Fuploads%252FZITvS4EG9QDqW8VLMq9j%252Fimage.png%3Falt%3Dmedia%26token%3D2d0e7b15-d7e6-4037-a52f-5b20e64b070e&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=bd664c57&#x26;sv=2" alt=""><figcaption></figcaption></figure>

There is another alternative where we can send multiple voltage levels and where one symbol can be transmitted per voltage level. For example, suppose we make 0V equal to 00, 1V equal to 01, 2V equal 10 and 3V equal to 11. When we have transmitted two bits of information for each symbol we transmit; this is very efficient. We refer to a multi-level system like this as an _m-ary_ system, where _m_ is the number of levels.

<figure><img src="https://johnoraw.gitbook.io/pnt/~gitbook/image?url=https%3A%2F%2F365966430-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FjPKaxBv8yVv6wzBRST0X%252Fuploads%252FB5eaXsBUmC1VPUFhcZSQ%252Fimage.png%3Falt%3Dmedia%26token%3Dda8188c0-9ab3-44f3-a082-16d75b218ada&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=5c4335da&#x26;sv=2" alt=""><figcaption></figcaption></figure>
