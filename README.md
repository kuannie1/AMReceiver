We aimed to access the 850 kHz AM station remotely. We achieved this through taking in the frequency signal, filtering and amplifying it, modulating it, and then playing the result through our speakers.

# Our Design
## Block Diagram


## Our Circuit


# What We Learned
We tried various gain levels for our RF Amplifier. At first, we wanted a pretty high gain, but we noticed [clips](https://en.wikipedia.org/wiki/Clipping_(audio)) in the audio signal. Since our gain was so huge that any small noise gets amplified, our op amp amplifiers tries to deliver beyond their bandwidth product.

We also tried to replace the multiplier by an [envelope detector](https://en.wikipedia.org/wiki/Envelope_detector) and noticed a large improvement in sound quality. Much of the external noise became clearer, and instead of just hearing the sound of a human voice, we were actually able to hear what they were saying. 

# Videos
Results with the Multiplier: [https://youtu.be/cI6Wa01qcrw](https://youtu.be/cI6Wa01qcrw)

Results with the Envelope Detector: [https://youtu.be/xL3OHJfi4Rw](https://youtu.be/xL3OHJfi4Rw)
