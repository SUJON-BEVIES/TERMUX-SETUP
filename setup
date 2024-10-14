import os
import time
import sys

os.system('clear')

def slowprint(s):
    for c in s + '\n':
        sys.stdout.write(c)
        sys.stdout.flush()
        time.sleep(5. / 100)

logo2 = '''
\033[1;32;40m
████████╗\033[1;33;40m██████╗░░█████╗░░██████╗██╗░█████╗░
\033[1;32;40m╚══██╔══╝\033[1;33;40m██╔══██╗██╔══██╗██╔════╝██║██╔══██╗
\033[1;32;40m░░░██║░░░\033[1;33;40m██████╦╝███████║╚█████╗░██║██║░░╚═╝
\033[1;32;40m░░░██║░░░\033[1;33;40m██╔══██╗██╔══██║░╚═══██╗██║██║░░██╗
\033[1;32;40m░░░██║░░░\033[1;33;40m██████╦╝██║░░██║██████╔╝██║╚█████╔╝
\033[1;32;40m░░░╚═╝░░░\033[1;33;40m╚═════╝░╚═╝░░╚═╝╚═════╝░╚═╝░╚════╝░
\033[1;32;40m
'''

print(logo2)
slowprint('\n Welcome To \033[1;31;40mTermux \033[1;33;40mBasic Installer\n')
time.sleep(1)

s = ' \033[1;31;40m[\033[1;33;40m1\033[1;31;40m] \033[1;36;40mStart Basic Installation \n \033[1;31;40m[\033[1;33;40m2\033[1;31;40m] \033[1;36;40mShow all packages \n \033[1;31;40m[\033[1;33;40m3\033[1;31;40m] \033[1;36;40mFollow on Facebook \n \033[1;31;40m[\033[1;33;40m4\033[1;31;40m] \033[1;36;40mGithub \n \033[1;31;40m[\033[1;33;40m5\033[1;31;40m] \033[1;36;40mExit \n'
print(s)

mo = input('\033[1;33;40mEnter \033[1;31;40m>>>\033[1;33;40m ')

if mo == '1':
    os.system('clear')
    print('Allow the Button For Access the Storage in Termux')
    os.system('termux-setup-storage')
    commands = [
        "apt upgrade -y",
        "pkg install python2 -y",
        "pip install --upgrade pip",
        "pip install requests",
        "pip install mechanize",
        "pip2 install requests",
        "pip2 install mechanize",
        "pip2 install bs4",
        "pip install lolcat",
        "pip2 install lolcat",
        "pkg install wget -y",
        "pkg install php -y",
        "pkg install nano -y",
        "pkg install curl -y",
        "pkg install tor -y",
        "pkg install openssh -y",
        "pkg install bash -y",
        "apt install python-dev -y",
        "apt install ruby -y",
        "apt install perl -y",
        "apt install nmap -y",
        "apt install clang -y",
        "apt install jq -y",
        "apt install macchanger -y",
        "apt install tar -y",
        "apt install zip -y",
        "apt install unzip -y",
        "apt install bmon -y",
        "apt install proot -y",
        "apt install java -y",
        "apt install figlet -y"
    ]
    for command in commands:
        os.system(command)

    os.system('xdg-open https://www.facebook.com/ariyanahmedsujontorabbu')
    os.system('clear')
    print(logo2)
    print('All Basic Packages Installed successfully\n')
    input('\nPress the enter key to exit ')

elif mo == '2':
    os.system('clear')
    print(logo2)
    slowprint('''
[01]  termux-setup-storage
[02]  apt upgrade -y
[03]  pkg install python2
[04]  pip install --upgrade pip
[05]  pip install requests
[06]  pip install mechanize
[07]  pip2 install requests
[08]  pip2 install mechanize
[09]  pip2 install bs4
[10]  pip install lolcat
[11]  pip2 install lolcat
[12]  pkg install wget
[13]  pkg install php -y
[14]  pkg install nano -y
[15]  pkg install curl -y
[16]  pkg install tor -y
[17]  pkg install openssh
[18]  pkg install bash
[19]  apt install python-dev -y
[20]  apt install ruby -y
[21]  apt install perl -y
[22]  apt install nmap -y
[23]  apt install clang -y
[24]  apt install jq -y
[25]  apt install macchanger -y
[26]  apt install tar -y
[27]  apt install zip -y
[28]  apt install unzip -y
[29]  apt install bmon -y
[30]  apt install proot -y
[31]  apt install java -y
[32]  apt install figlet -y
    ''')
    m = input('Press Enter to Continue ')
    if m == '':
        os.system('python tbasic.py')

elif mo == '3':
    os.system('xdg-open https://www.facebook.com/ariyanahmedsujontorabbu')
elif mo == '4':
    os.system('xdg-open https://www.github.com/SUJON-BEVIES')
elif mo == '5':
    sys.exit()
