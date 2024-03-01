
[macOS language list](https://gist.github.com/mculp/4b95752e25c456d425c6)

These can be directly used on macOS machine with the installation of audio pkgs from Apple to synthesise speech.

# Command Line Instructions

## 1. Use Mac Mini LING000107 for the participant.

## 2. Open Terminal.app (/Applications/Utilities/Terminal.app)

Execute the following command to get LING000107’s IP address (inet) if the computing is using SFU’s Wifi network:
    
    ifconfig en1

## 3. On the typist’s computer, open Terminal, and execute the following command to remote control LING000107 (assume the IP you got from Step 3 is 142.58.17.176):

    ssh lab-user@142.58.17.176

## 4. After logging in with ssh, execute the following command to enter typing mode

    say --voice="Daniel (Enhanced)"

## 5. Type the following, and press enter

    This is a test, can you hear me? Please acknowledge
