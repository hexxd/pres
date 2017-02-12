# What is pres?

I got inspired as a summer researcher giving a research presentation in my college's Chemistry department after every previous presenter manually clicked from slide to slide on their computers. Physical clickers are expensive and most apps I found don't work well, so I created pres (pronounced "press"), which is a PowerPoint presentation controller built with TouchOSC and Max. It was written entirely in Max 7 and relies on the <a href="http://www.iamas.ac.jp/~aka/max/#aka_keyboard">aka.keyboard</a> object by Mayasuki Akamatsu, as well as <a href="http://hexler.net/software/touchosc">TouchOSC</a> (© Hexler Limited).

<br>

# Getting Started
### Introduction

If you're new to GitHub, welcome! You can download the entire repository as a .zip file by clicking "Clone or download" button over on the right there. Make sure that the "Branch" listed on the left says "master".

If you want to open and edit the Max patch itself, you'll need to download the aka.keyboard object, which you can find at the link above. You'll also need to download Max 7, if you haven't already (PLEASE NOTE: if you would like to open this file in Max, you <em>don't</em> have to buy the software. Max can be downloaded for free and can open any patch without requiring you to buy a license).

If you just want to use the program, either open the .mxf files in Max or <a href="https://www.dropbox.com/s/412o4uv9s8966w7/pres2.12.17.zip?dl=0">download the .app</a>. Windows .exe files are currently not supported :(
<br>
### Configuration

<ol>
<li>Install the <a href="http://hexler.net/software/touchosc">TouchOSC Editor</a></li>
<li>Install the TouchOSC app on the mobile device you'd like to use. Sorry that it's not free! However, it is cheaper than any clicker you could buy. It's a great, tremendously flexible piece of software and an even greater excuse to get into the world of electronic music, MIDI and OSC!</li>
<li>Open the pres.touchosc file with the TouchOSC Editor. In the top right corner of the editor window, click "Sync". Make sure your computer and iOS or Android device are connected to the same wifi network.</li>
<<<<<<< HEAD
<<<<<<< HEAD
<li>In the TouchOSC app on your device, touch “Layout > Add”: your computer’s IP address may appear (both devices must be on the same wifi network) or you may have to enter it manually using “Edit > +”</li>
<li>Once you have entered the IP address, touch it, and the “pres” layout open in the editor should synchronize onto your device.</li>
<li>Under “Connections” touch “OSC”. Make sure that “Host” shows your computer’s IP Address, the outgoing port is 8000, and the incoming port is 9000.</li>
<li>Leave the app or patch running in the background while you present. That's all there is to it!</li>
=======
<li></li>
>>>>>>> origin/master
=======
<li></li>
>>>>>>> origin/master
</ol>
