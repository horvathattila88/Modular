# Modular
Modular synth stuff

Most of these are designs from other people, i've just redrawn them to fit into a eurorack system. The PCB's are smaller than 100x100mm, so it's easier to have them manufactured, pick any of your favourite manufacturers. The plans are in EAGLE 7.4 format, you can generate gerbers from there, according to the manufacturers needs. 
I have uploaded this for hobbyists, i don't make any money out of it, you shouldn't sell the boards! 
The MFOS ones are designed by Ray Wilson - Music From Outer Space, please respect his heritage. 
Yusynth is Yves Usson

The PSU is my own design, (simple as Trump) you'll need a transformer with 2x12V AC secondaries, or 1x15V AC, connected to the center and one of the AC inputs. Two way, or one way rectifier, you choose, i like to use 2-way, with a center tap transformer. 
Don't use it for more than 7-800mA, for example, one bigger transformer on the bottom of the case and one PSU in each row... Install the SMD or the TH LED's, not both. There is no 5V rail, nor CV, or Gate, as i'm not using those, and found it's a bad solution. 
There is also a distribution board, it can be cut into more strips if needed. LED's and filtering caps can be soldered on those too, but not necessary. 

Part numbering is (most of the time) the same as in the MFOS webpage, you'll need to read through the documentation there. 
There are some exceptions, like the ringmodulator, i've made a dual ringmod without the VC sine osc, and the simple osc on a standalone module. It's quite straightforward though. 

Here is the status of the modules: 

PSU, rails - Tested OK, pinouts are the same as on the modules, be careful when making ribbon cables! 
MFOS VCF 12dBi state variable - Tested OK (sounds sweet) 
MFOS VC LFO - Tested OK 
MFOS VCO - Tested, not calibrated yet
