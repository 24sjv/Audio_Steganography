*Audio Steganography: Hiding Data in Audio*


Steganography is the practice of hiding a secret message inside of (or even on top of) something that is not secret......


Audio steganography is the process of hiding a message inside an audio container.......




# Requirements
This tool require python3



>>>>> FOR EASY PROCESS USE MY REPOSITORY

                                     gitclone https://github.com/24sjv/Audio_Steganography.git
                 


## Steps
Hiddenwave have two python scripts.

~~~ HiddenWave.py----- for hide secret information.</li>
~~~ ExWave.py----- for extract secret information for wave audio file.


Step-1---Hide Secret Information in Audio file
       
       > Go to kali Linux and open terminal.
       > In terminal, go to directory where the Audio Steganography Folder is located.
       > First run python3 HiddenWave.py
       > And run this command python3 HiddenWave.py -f Demo.wav -m " Your Secret Msg" -o output.wav
       > It will show Done.

Step-2---Extract Secret Message from the audio file

         
       > First run python3 ExWave.py 
       > to extract secret message run the following command  python3 ExWave.py -f output.wav
       > You will view your secret message

### For easy process Use gitclone https://github.com/24sjv/Audio_Steganography.git 

