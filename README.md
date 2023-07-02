# File_Encryptor

## Create script to encrypt files and folder

### Usage

python encrypt.py path(file or folder)

Examples:
    python encrypt.py test.txt(file)
    or
    python encrypt.py ./testdir(folder)

encrypted files("original_file_name.bin") will be generated in original location after the program running

Example :
    
    Original file : Binary.txt(file)
    Encrypted file : Binary.bin
    
    Original Folder : ./Cipher
    Encrypted Folder : ./Cipher.bin

# Speech-to-Text Converter

This Python script converts the Speech input into Text using NLP (Natural Langauge Processing).

## Requirements

**Installation Required** :

* Python Speech Recognition module:

    `pip install speechrecognition`

* PyAudio:
  * Use the following command for linux users

    `sudo apt-get install python3-pyaudio`

  * Windows users can install pyaudio by executing the following command in a terminal

    `pip install pyaudio`

* Python pyttsx3 module:

    `pip install pyttsx3`

### How to run the script

-   Enter the audio input by speaking into the microphone.
-   Run converter_terminal.py script
-   Output Text will be displayed

# Convert_JPEG_to_PNG

This project contains a simply python script to change file extension from .jpeg to .png

## Requirements
Pillow module

`pip install pillow`

## Two methods:

I accomplished this task in two ways
### Using Terminal
- Add the image in jpeg format with name as 'input' in this folder.
- Run converter_terminal.py script
- output image will be generated in this folder

### Using GUI
Just run the converter_GUI.py script and pick any jpeg image from any location and then press 'Convert Jpeg to Png'

# Digital Clock using Python and Tkinter
This script create a digital clock as per the system's current time.

## Library Used
* tkinter
* time

### To install required external modules
* Run `pip install tkinter` 

### How to run the script
- Execute `python3 digital_clock.py`

### Screenshot/GIF showing the sample use of the script

![Digital Clock Output](https://github.com/rohitchandra781/Python_Project/blob/main/Digital_Clock/Output.png)

# Convert a json file into a csv
This script take a json file as input and generate a csv file in output.

### Prerequisites modules
* json
* Run `pip install json` to install required external modules.

### How to run the script
- Execute `python3 converter.py`

