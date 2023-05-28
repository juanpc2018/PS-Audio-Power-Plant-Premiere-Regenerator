# PS Audio Power Plant Premiere Regenerator

Measuiring the Output of the PS Audio </br>

Digital Oscilloscope FFT can be deceiving, </br>
because you can set FFT anyway, </br>
to look good or to look bad, to show more noise than actually is, </br>
show less noise than actually is, there is No baseline, </br>
its a floating measurement. </br>

The proper way to measure AC noise was invented decades ago, when scopes  </br>
didint had FFT </br>
devices like ONEAC Line Viewer 103, </br>
or devices like Entech https://www.dailymotion.com/video/x6be5r5 </br>

The Entech is a Noise Audio Amplifier </br>
The ONEAC its an Isolation Transformer, 100:1 </br>
and other 2x transormers 10:1 connected out of Phase, </br>
between Line and Neutral, and Neutral and Ground. </br>
https://www.flickr.com/photos/50698989@N06/albums/72157709362098427 </br>
Making Only Noise Visible. </br>
[CM](https://github.com/juanpc2018/PS-Audio-Power-Plant-Premiere-Regenerator/blob/main/Oscilloscope/DS0014.PNG)
[NM](https://github.com/juanpc2018/PS-Audio-Power-Plant-Premiere-Regenerator/blob/main/Oscilloscope/DS0015.PNG)
 
The PS Audio PPP CleanWave, is a 5 second Degauser Wave, </br>
a high frequency Sine wave injected to main 60Hz sine. </br>
[1](https://github.com/juanpc2018/PS-Audio-Power-Plant-Premiere-Regenerator/blob/main/Oscilloscope/DS0044.PNG)
[2](https://github.com/juanpc2018/PS-Audio-Power-Plant-Premiere-Regenerator/blob/main/Oscilloscope/DS0025.PNG)
[3](https://github.com/juanpc2018/PS-Audio-Power-Plant-Premiere-Regenerator/blob/main/Oscilloscope/DS0046.PNG)
[4](https://github.com/juanpc2018/PS-Audio-Power-Plant-Premiere-Regenerator/blob/main/Oscilloscope/DS0048.PNG)

MultiWave is a 60Hz sine wave + 3rd Harmonic Sine Wave, </br>
the purpose of MW is to make Sine Wave Fatter in the RMS region,  </br>
why? because most equipments save manufacvturing $$ by reducing capacitors size </br>
most dont have enough capacitance in the PSU. </br>
MW solves that problem. </br>
The sine wave from the Wall has between 3% and 5% THD,  </br>
but THD is in the High frequency Range, affecting the noise floor, </br>
MultiWave also has 3-5% THD but only in the 3rd Harmonic,  </br>
increasing power, without increasing Noise floor. </br>
MultiWave is the Desired Way to Use the Power Plant Premiere </br>

Standar Sine, No CleanWave, No MultiWave, has very low %THD, </br>
The 8-Bit Scope i have cannot measure less than 0.6%  </br>
givees around ~0.7% THD. </br>
would require 12-Bit, 16-Bit 24-Bit ADC to know exactly.  </br>
That wave is Desired for Electronic Laboratory Design & Repair </br>

PS Audio converts 120 AC from the Wall to DC, back to 120vAC </br>
using DDS, DA converter, generates a flawless AC signal. </br>
but thats "too pure" for most equipments, thats why MultiWave was invented. </br>

The screen of the PPP is basic, but does Not have 60000 count Digital Multimeter precision, </br>
just a basic display, and needs manual calibration. </br>

Under the PSAudio has a trimmer, that allows to change the amplitide / voltage of the output. </br>
when gives 120v Pure, usually most multimeters detect 122 when MultiWave is Activated. </br>
The Oscilloscope detected 120vAC RMS with MultiWave.  </br>

Works? Yes,  </br>
a must have for Analog Audio Mastering Equipment, </br>
Analog Audio Recording, High Precision Masterclocks, etc..  </br>

Some PSUs are designed in a way that does Not improve. </br>
but most equipment does. </br>
