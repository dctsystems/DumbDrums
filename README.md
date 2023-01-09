# DumbDrums
Basic Drumloop Step Sequencer for MainStage

Can you believe how hard it is to play a basic drum loop in Mainstage? Really???!!!
Ultrabeat has a basic step sequencer, but it's preset sounds are all electronic
Drum Designer has great sounding kits but no way to play loops though them.

However built into the Scripter node is a demo "Probability Drum Sequencer".
This is based on that, but supports mulitple patterns, allowing you to switch between them.
To use, create a drum designer channel strip and insert a Scripter in the MidiFX slot.
Either load the PST preset file into the scripter, or just copy/paste the txt file into the
script editor.

There's no UI to edit patterns, but its trivial - just add/edit the big array in the text file.
Each row is one drum. Each loop is 1 bar, 16 steps per bar. The numbers are the volume from 0-100.
When you're done, hit "run" and your new pattern loads up. you can add new/extra patterns just by
adding them to the end of the list.

