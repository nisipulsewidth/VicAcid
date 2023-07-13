# VicAcid
Vic is my attempt at replicating the acid bass architecture, first pioneered by the Roland TB-303. A big part of my artistic process is trying to replicate these iconic/genre-defining synthesized sounds and tweaking its architechture, whether that be the parameters or interface. that way i avoid turning into a fucking gearhead ($$$) and i'm able to create something that is uniquely my own. Vic was an adaptation of this other maxpatch i found somewhere on the cycling 74 forums that was also an attempt at making an acid bass, but was still unfinished.

The core oscillator is a sawtooth wave whose frequency is being modulated by another sawtooth of the same frequency. The x-axis of the pictslider controls the frequency of the oscillator (0-500hz) and the y-axis controls the FM depth (0-10). the oscillator is then fed through an LPF whose cutoff frequency is envelope-modulated (base 2 exponentially scaled, range of ~ 8-2637hz) with resonance (1-27). the signal is then fed through a distortion effect, and output.

there are two main ways to play Vic: hitting the s key or the toggle button will turn on a metronome that will continually output bang messages at a frequency controlled by the dial in the upper-right hand corner (bpm >= 472.44). hitting the d key or pressing the bang button will pulse over the entire envelope upon hit. 

And that's it! enjoy! if you use/modify this max patch for anything you're doing, please let me know, i'd love to hear it. :)
