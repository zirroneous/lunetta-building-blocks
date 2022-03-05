# lunetta-building-blocks

these little "stanley boards" are some of the basic fundamental circuits that make up "lunettas," experimental digital synthesizers, conceptually introduced in the 80's and 90's by stanley lunetta.

===

i'll be fleshing out with pertinent historical data, and due credit and regard, as time passes.

to start, why not go to the roots? here is the lunetta forum on electro-music, where i first learned of this rich and storied strange fucking hobby. forum 160 has the goods. :

https://electro-music.com/forum/forum-160.html

that should keep you occupied for a minute.

===

## THE BOARDS

the boards comprise "shorthands" for circuits which a lunetta builder often finds themselves having to do often for various reasons. little shortcut boards that setup the skeletal support circuitry, making it a tiny bit quicker to get to the fun experimentation part of the process. proto-macros or something. i don't know. not quite modules, but ingredients for them.

the designs are done in EasyEDA, by a n00b, and should be considered unverified beta. be nice.

the first batch of boards is presently in my posession, troubleshooting underway!!

thus far: 

### 001 : 6 x 40106 oscs.

the most basic oscillator, more or less pulled straight from the datasheet examples. you get 6 from one chip. extra kludge space holes on these. i'll bet you know what these are, and that your thumbs are happy to get a break.

### 002 : 6 x 4069 buffers.

w/ spots for ac caps, which can be bypassed/jumpered if you want.

### 003 : basic af 4046 vco

one of the simplest vco circuits that can be pulled from the 4046 pll chip.

### 004 : 4015 shift reg

get your rungle going.

### 005 : 4017 counter

baby seq's, top octaves, harmonic divisions. hooray!

### 006 : 4040 divier

wired as a basic pulse divider. i dunno what else to say. bare bones af. you'll wanna add your support circuitry.

### 007 : 7809 9v single-sided regulated power supply

kiss that battery snap goodbye, hoss! i'll probably make this a little happier, later on, but this works fine.

### 008 : 4051 multiplex

10 to 1 analog switch triggered by 3x parallel data inputs

with these i left space for choice of components on the switch inputs, and have 100k pulldowns in place for the logic in's.

### 009 : CD40XX generic 4 x logic gates

works with several quad 2-input gate chips. "iio" means what you think it means.

### 010 : ms20esque single supply sallen-key hp/lp vcf.

this one is jacked from a schematic by tim escobedo. the footprints for panel components should be rear-mounted. (i think.)

##### <3, molg.
