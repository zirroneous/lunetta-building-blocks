# lunetta-building-blocks

these little **"stanley boards"** are some of the basic fundamental circuits that make up "lunettas," experimental digital synthesizers, which are centered around the CD4000 series of CMOS logic chips.

conceptually introduced in the late 1960's by **Stanley Lunetta**, of sacramento, ca. (accomplished percussionist and avante-garde musician, performance artist, and music instructor at UC Davis and Chico.) 

![sTANg portrait](https://github.com/zirroneous/lunetta-building-blocks/blob/main/sTANg3.jpg)

his name for them was "**moosack machines**," and they were built into sonic sculptures, often glued in place within the sculpture (or as a prominent feature of the sculpture,) and wired point to point.

![sound sculpture photo](https://github.com/zirroneous/lunetta-building-blocks/blob/main/soundsculptures.gif)

http://moosack.net/stang/me.html
http://moosack.net/stang/sculpts.html

he informally taught some of his students at the university, who carried the work forward, naming the circuits "**lunettas**," which were [revived](https://electro-music.com/forum/topic-23850.html) in the **synthdiy** section of the forums on electro-music.com in the late 'aughts : 

https://electro-music.com/forum/forum-160.html

to start, why not go to the roots? **forum 160 has the goods.** i recommend starting with the pinned threads. that should keep you occupied for a minute. i imagine there's more on morphwoggler.

lunetta circuits, as it goes, are generally simple and low-part count themselves, with some only requiring running jacks to the panel from the i/o pins of a chip. others are more involved, combining several of the concepts together, going wild with the boolean expressions, introducing linear functions via transistors and opamps, etc. 

the supply is, generally speaking, a single-sided supply between 9 and 12vdc. this is within the tolerance of the CD4000 series of chips. as a rule, **negative voltages do not play nice with lunettas**, because the inputs are expecting a binary digital signal fluctuating between gnd (logic 0) and supply voltage (logic 1).

that's basically the major rule, don't blow your chips up. protect your inputs and outputs. beyond that, and a few other general guidelines, the tendency is toward the experimental and expressive. often, the resulting instrument is playable and intuitive to its respective builder, but abstract and difficult to comprehend to everyone else. this is the nature of the realm of lunettas, as it is in some ways a game one plays with themselves.

## THE BOARDS

the boards comprise "shorthands" for circuits which a lunetta builder often finds themselves having to do often for various reasons. little shortcut boards that setup the skeletal support circuitry, making it a tiny bit quicker to get to the fun experimentation part of the process. proto-macros or something. i don't know. not quite modules, but ingredients for them. 

lunettas circuits, as it goes, are generally simple and low-part count themselves, with some only requiring running jacks to the panel from the i/o pins of a chip. others are more involved, combining several of the concepts together, going wild with the boolean expressions, introducing linear functions via transistors and opamps, etc.

the designs are done in EasyEDA, by a **n00b**, and should be considered **unverified beta**. be nice.

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
