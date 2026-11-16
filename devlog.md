Sept 17 
- [ ] ordered daisy 
- [ ] 

Sept 13 - prep for class 1
- [ ] considering options for design projects
- [ ] daisy based?
- [ ] daisy boards with control inputs currently sold out
- [ ] daisy control boxes not on sale at present
- [ ] considering using leap controller as built into controller box for noisy hand waving theremin type device
- [ ] considering design something like a K-devices plug in gen to port to ableton move and use as live effects/creation box
- [ ] considering using an ordered sonorous objects electromagnetic mic (or use electrosuch with wireless) as input for looper, sound generator box
- [ ] thinking a lot about controller devices

Sept 20
- [ ] bought $10 karaoke mic as possible daisy hack box
- [ ] started reading Jeff Kaiser and Gregory Taylor’s building max loopers  book
- [ ] interested in saturation/feedback loops within looper

Sept 22
- [ ] trying to figure out RNBO and Move 


Sept 26
- [ ] Karooke mic was pulled apart, all switches on circuit board so of no real use
- [ ] 


Sept 27
- [ ] checking ada fruit for interface ideas
- [ ] ipod scroller https://www.adafruit.com/product/6310
- [ ] capacitive https://www.adafruit.com/product/6310
- [ ] rotary controllers https://www.adafruit.com/product/5752#description
- [ ] tactile switches for karaoke rebuild? https://www.adafruit.com/product/5493
- [ ] joystick switch? https://www.adafruit.com/product/480
- [ ] 808 type switch board https://www.adafruit.com/product/5631
- [ ] grid switch board https://www.adafruit.com/product/5157
- [ ] 
Sept 30
- [ ] json editor https://jsoneditoronline.org/#left=local.kasabe&right=local.kuvuqe

Oct 6 
- [ ] new plan - build prototype looper on Move in RNBO. If its good, buy a daisy board with similar knobs/buttons
- [ ] exported looper on Move through RNBO, have basic access to parameters.
- [ ] Next plan is to make use the move template to assign pads to transport buttons
- [ ] working on adding saturation and gate

**Oct distractions**
Dracula at the Grand Theatre - 300 cues, music and sound design, full on wireless, big show - opened
GoodNight Desdemona @ Canstage - 100 or so cues, music and sound design, fairly big show - opened
King James Bible @ NAC - remount but 4 days of 12 hour days to get it opened
Treemonisha @ Centennial Theatre in Winnipeg - sound design, minimal gig but in the theatre long days

Nov 6
- [ ] learning control of led’s and controllers on Move
- [ ] Can access param on knob controllers on Move but can’t yet assign record/play/stop to pads
- [ ] can access led’s on pads 
- [ ] working with simple noise with filter to try to test controller assign
- [ ] working with basic synth to get Move pads to work as keys
- [ ] considering routing for adding tanh and freq shifter inside loopers
- [ ] still trying to get one looper set up to work with line of pads and assignable controllers per looper, controlled by side selector button
- [ ] Move controllers send +1 or -1, working to figure out best way to route use += and then scaling to control filter data
- [ ] still can’t get controllers to work i

Nov 10
- [ ] learning more about graph setups for control of patches for Move
- [ ] still considering porting to Daisy and building a box
- [ ] working out how to test within Max on laptop, once ported to Move there is no visual feedback, just have to keep porting over tests until it works
- [ ] Using midi in Ableton Move 
- [ ] AI lies about rnbo - accum doesn’t do what it says

Nov 14
- [ ] midin - midiparse - stripnote - sel (note number) - for bang from Move keypad. Phew. Can now get single messages
- [ ] infinite controllers send out cc 1 if you rotate right, cc 127 if you rotate right. Trying to change that to +1, -1 for accum
- [ ] ack - figuring out something in max then finding it doesn’t work in rnbo is a drag
- [ ] building loops in gen has too many errors in console to be useable
- [ ] list.nth 1 - to get second value in cc message (array.index 1 - in max)
- [ ] better - use ctlin to scale to +1, -1 then use 2 + to create tally, followed by clip 1 127. Phew
- [ ] Now have control over basics from Move, pads, LED’s and control knobs. Will need to learn how to do banks of controllers for each looper 
- [ ] Now back to working on looper, will investigate groove~ based loop. Not sure if I want 4 channels at same time or 4 unsynced loops. Best would be a sync/unsync button but…..
- [ ] looking at the looper graawaa created for Geoff Kaiser in 2014, has some errors now that may be beyond me, also codebox….
- [ ] 

