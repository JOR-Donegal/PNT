# Waveforms

Blues, heavy metal, and rock tend to have a distorted guitar sound.

For Rory Gallagher’s kind of blues, one of the stages of the amplifier is overdriven, causing the sine waves to be squared off a little on top. If this is beyond your musical expertise, have a listen on the Internet. This also has the effect of adding some sustain to the sound by compression.

Some of Santana’s music is much more distorted and has massive sustain. Technically this is called distortion, the effect is created by turning the nice pure sine waves which a guitar’s pickups produce, into square waves.

There are other kinds of waves we find in use in technology, including triangular waves and saw-tooth waves. We mostly experience these as electrical signals with waves in voltage, current, power.

We may display these signals with voltage on the vertical axis (Y) and time on the horizontal axis (X). As time is used for one axis, we refer to this as a display in the time domain.

<figure><img src="https://johnoraw.gitbook.io/pnt/~gitbook/image?url=https%3A%2F%2F365966430-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FjPKaxBv8yVv6wzBRST0X%252Fuploads%252FSX5u2sDEy9rf5HQWAm9i%252Fimage.png%3Falt%3Dmedia%26token%3Dde842b49-8e82-4eea-95a3-a62a39bc1e99&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=2e79c26d&#x26;sv=2" alt=""><figcaption></figcaption></figure>

When a signal is viewed using a device called an _oscilloscope_, it appears as a continuous varying waveform. I can use a _signal generator_ (pictured on the right) to create and view test signals on the oscilloscope (pictured on the left).

<figure><img src="https://johnoraw.gitbook.io/pnt/~gitbook/image?url=https%3A%2F%2F365966430-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FjPKaxBv8yVv6wzBRST0X%252Fuploads%252Fgc5vlJoamoCI1Znq6f4Z%252Fimage.png%3Falt%3Dmedia%26token%3Dce80497b-ea4f-4446-b384-433ecce3074f&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=2dbdb8e8&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Complex signals do not appear to have a pattern, one way to model these waveforms is to see them as being made up from many sine waves of different frequencies and different amplitudes. The mathematics behind this is called _Fourier Analysis_ and it is the basis for much of electronic design and modelling.

Do a little background reading on Fourier Analysis now.

There is a second instrument we use to look at signals, called a spectrum analyzer. This looks at signals with the horizontal axis showing frequency. We refer to a diagram like this as being in the frequency domain.

<figure><img src="https://johnoraw.gitbook.io/pnt/~gitbook/image?url=https%3A%2F%2F365966430-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FjPKaxBv8yVv6wzBRST0X%252Fuploads%252FyvjoOABaQSKKKyixLX6O%252Fimage.png%3Falt%3Dmedia%26token%3D6c66759e-0273-4ade-a3bf-83f545d0db49&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=76fea5a0&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Imagine we have an audio signal from a phone, 3.1 KHz bandwidth, modulated onto a carrier of 100 KHz. If we were to view the signal in the time domain, we would see energy in frequencies from 97-103 KHz.

The areas on either side of the carrier are called _sidebands_. The actual carrier itself provides no information and can be suppressed before the signal is amplified and transmitted.
