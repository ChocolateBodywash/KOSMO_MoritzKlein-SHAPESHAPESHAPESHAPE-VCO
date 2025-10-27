## KOSMO Format - SHAPE SHAPE SHAPE SHAPE VCO

![](/IMG/SHAPE4VCO.jpg)

A KOSMO format of Moritz Klein’s "Shapes VCO" with a few added features

[![Moritz Klein’s VCA](https://img.youtube.com/vi/QBatvo8bCa4/0.jpg)](https://www.youtube.com/watch?v=QBatvo8bCa4)

The shapes VCO was probably one of the first synth projects I ever did, so this one is dear to my heart.
I love this VCO! Parts are easy to find, it stays in tune and it sounds awesome.

I felt I needed to push it further, the 40106 schmitt trigger inverter contains 6 inverters. What if I used all of them?
Well that was too much, but with the amount of op amps I needed I worked out 4 was the most I could get. I'm pretty sure it would be impossible to fit anymore without making this a massive 20cm module or something..

### Features

- For ease of use, there is one CV input that goes to a buffered multiple circuit. All four then get mixed into one output.

- Realizing it would be impossible to tune, I added a switch for each VCO. This also makes it easy to add or remove VCOs on the fly.

- Instead of a coarse tuning knob, I added an octave switch. This required a precision shunt voltage reference and a series of voltage dividers. The only catch was that it needed to be a negative voltage, so I inverted the whole thing. Problem solved.

- One easy win was adding a Look Mum No Computer link cable, this makes it compatible with the 1221 ocsilator expander. 

- The FM knob wouldn’t fit, so I used a trimpot instead. A compromise had to be made somewhere.

- There is also a center trimpot that acts like a coarse tuning knob just in case. All of these controls get summed together.

---
Note: This was created by a hobbyist with no formal engineering training outside various late night YouTube binges. 
I’ve confirmed these designs to work but I make no guarantees on the design working efficiently.. or working at all.

Additional credit: Analog Output (Richard Holmes) for footprint libraries and front panel templates.
