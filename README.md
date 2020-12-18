# GPT2Explorer
This is basically a portable stand-alone text generator for windows using GPT2 OpenAI released models in 2019 for commonplace nowadays laptops/desktop computers.

GPT2Explorer is simply a basic window graphical user interface wrapping the demo gpt2tc.exe command line generator engine from Fabrice Bellard.

Excutable has been built via pyinstaller and Gui has been built with PySimpleGUI framework and a notepad template from Israel Dryer, wrapping the gpt2tc.exe engine.

Quick Start
  
  1. Unpack the GPT2-Explorer folder from the .zip file on your pc, where you want, then, you must also 
  
  2. Add the content of https://bellard.org/nncp/gpt2tc-2020-07-25.tar.gz to the GPT2-Explorer folder.
  
  3. Download the available small model https://bellard.org/nncp/gpt2tc-117M.tar.gz and place the gpt2_117M.bin file into the GPT2-Explorer folder

Then, it should run stand-alone on windows10 64bit with a decent cpu and 4Gb Ram, by clicking on GPT2-Explorer.exe .
Load the filter named 'NoFilter.flt' and click on the <Generate button>, wait 5 seconds and read.

My 2017 laptop pc delivers 32 words/s with the small model, XL model can run on a 8Gb RAM recen laptop (altough it can take minutes to deliver outputs)
Answer time can be quite different depending on your hardware performances.

See help.txt in this Zip file for more detailed install info and usage.

Other model will have to be built separately or downloaded ( need still to figure this out as it reaches 600Mb (medium), 1.6 Gb (Large), and 3Gb (XL)).

Writers, curious, teachers and poets and others, have fun but use responsibly.
This is much more for educational purpose than anything else.

Don't expect much support, i'm a desesperate amateur with the machines and i have work, life etc.
