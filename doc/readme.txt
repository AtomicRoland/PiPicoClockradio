Installation   
============                           

The first step is to install BBC Basic on the Pico, if you haven't already done 
so. The designers of the Pico have thought carefully about how you can provide 
the Pico with the program (firmware) you want to use as simply as possible. This 
can be a program with a specific task (such as my Electron Video card), but also 
an environment with a programming language such as Micro Python or of course BBC Basic.

There is a small white push button on the Pico to select the boot mode. If you 
turn on the Pico without pressing this button, it will start normally. However, 
if you press this button and then connect the Pico to your computer, it will be
shown as a USB drive in the Finder (Apple MacOS) or Explorer (Windows). All you 
have to do is drag the file with your program or firmware to the drive icon of the
Pi Pico. The file will then be copied to the Pico's flash memory and when finished,
the Pico will automatically reboot and start your program or firmware.

Let's do this step by step:
     • If the Pico is connected to your computer, disconnect it for a while.
     • In the file Explorer or Finder open the folder where 
       bbcbasic_console_rpico.uf2 is located.
     • Press the white button and connect the USB cable to your computer with your 
       other hand.
     • A new “drive” icon will now appear in the Finder or Explorer. This is 
       called RPI-RP2.
     • Drag and drop the uf2 file to this icon.
     • Wait a moment until the file has been copied and the Pico restarts 
       automatically.

During this restart, your computer may prompt you to unmount (eject) the media 
before removing it. Ignore this message, the file has been successfully copied 
and it can do no harm to remove the medium  without to eject it.
BBC Basic is now installed and ready to use.

The second step is to install the clock radio program. Step by step it goes as 
follows:
     • Open the clockradio.txt file in a text editor
     • Select the entire text and copy it to the clipboard
     • In BBC Basic type the command
	NEW <enter>
     • Paste the text into the console window
     • When the text is pasted, press ESCAPE
     • Save the file with the name autorun.bbc

With these steps, the clock radio is ready to use. You can now start the program 
directly with the RUN statement. By using the name autorun.bbc the program will 
start automatically when the Pico is powered on or reset.

Have fun with it!

