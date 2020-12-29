# GPT2Explorer
This is basically a portable stand-alone text generator for windows using GPT2 OpenAI released models in 2019 for commonplace nowadays laptops/desktop computers.

GPT2Explorer is simply a basic window graphical user interface wrapping the demo gpt2tc.exe command line generator engine from Fabrice Bellard.

Excutable has been built via pyinstaller and Gui has been built with PySimpleGUI framework and a notepad template from Israel Dryer, wrapping the gpt2tc.exe engine.

Quick Start
  
  1. Unpack the GPT2-Explorer folder from the .zip file on your pc, where you want, then, you must also 
  
  2. Download the available small model https://bellard.org/nncp/gpt2tc-117M.tar.gz and place the gpt2_117M.bin file into the GPT2-Explorer folder

Then, it should run stand-alone on windows10 64bit with a decent cpu and 4Gb Ram, by clicking on GPT2-Explorer.exe .


My 2017 laptop pc delivers 32 words/s with the small model, XL model can run on a 8Gb RAM recen laptop (altough it can take minutes to deliver outputs)
Answer time can be quite different depending on your hardware performances.

See help.txt with the GPT2Explorer.zip file for more detailed installations information and usage.


29.12.2020
           - Slicing fixed.
           - Embryo of batch function with possibilities of processing a dataset trough filters enabled.
	         - 3 buttons for speed access to included demos (Chatbot, Philosopher, Starwars like story) 

24.12.2020 - Recompiled with new bootloader to lower false-positive reactions of anti-virus working with heuristic rules. 

23-12-2020 - Updated version 0.02 uploaded. Minor changes for better stability. 
           - NoFilter.flt set by default & Help text also uploaded to Github.
           
18-12-2020 - Other models ( medium, large and XL ) can be downloaded currently via links provided in the model_download.txt 


Writers, curious, teachers and poets and others, have fun but use responsibly.
This is much more for educational purpose than anything else.

Don't expect much support, i'm a desesperate amateur with the machines and i have work, life etc.

Note : The .exe might be seen by anti-virus software as containing trojan (especially window defender while mc affee does not report anything). This behaviour is known for .exe compiled with pyinstaller since a while. 
