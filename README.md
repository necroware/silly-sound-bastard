# Silly Sound Bastard

![Photo](longboard/photo.jpg)

It is yet another clone of the well known Covox Speech Thing. I wanted to get
some practice in EDA and what is one of the simplest part to make, which you
could have fun with? If you are in retro community, you would understand, why it
was a Covox clone.

# What is special about it?

Well, it is still a simple Covox clone. However, I wanted to make something
brute, what you can solder easily, using some through holes parts, but still
with some space for experiments. So I made it with a quad switch, three of which
can be used to control bypass capacitors, to play with low-pass filtering and 
one for switching between mono and (fake-)stereo sound.

# Bill of materials

I have a good news for someone, who is especially keen to solder. Instead of
using two types of resistors with 1/2 relation, I just used all the same types,
but doubbled one row to maintain the relation. This way you don't need to search
for resistors with a proper 1/2 relation, but just can take any resistors, you
have at hand. The parallel port connector is not a through hole part, but rather
a normal connector, like used in any printer cable. It is quite easy to find and
can be directly soldered to the edge of the PCB.

Part   | Count | Remarks
-------|-------| ----------
R1..R26|26x    | 1kOhm resistor
C1     |1x     | 1uF tantalum capacitor
C2     |1x     | 2.2uF tantalum capacitor
C3     |1x     | 3.3uF tantalum capacitor
C4     |1x     | 3.3uF electrolytic capacitor
SW1    |1x     | Quad-Switch (like LCSC C559139)
AUDIO1 |1x     | 3,5mm Audio jack port (like LCSC C145816)
LPT    |1x     | DB25 parallel port M-plug

LCSC is the parts distributor (see http:://lcsc.com)

# There is a long and a short variants?

![Long Board](longboard/silly-sound-bastard-pcb.svg)
![Short Board](shortboard/silly-sound-bastard-pcb.svg)

Yes, I actually made two variants. The long board has switches, variable low 
pass filtering and uses three rows of same resistors. If you are not interested 
in all of that, you have a set of two types of resistors with a proper 1/2 
relation and space is more important for you, then take the short variant. You
will need less parts and get a more compact solution.

Part      | Count | Remarks
----------|-------| ----------
R1..R8,R17|9x     | 2kOhm resistor
R9..R16   |8x     | 1kOhm resistor
C1        |1x     | 3.3uF electrolytic capacitor
C2        |1x     | 2.2uF tantalum or electrolytic capacitor
AUDIO1    |1x     | 3,5mm Audio jack port (like LCSC C18166)
LPT       |1x     | DB25 parallel port M-plug

LCSC is the parts distributor (see http:://lcsc.com)





