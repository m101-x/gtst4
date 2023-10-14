
         Linux For User
-kali linux was  previously known as back track

    Tools of kali
           1) information gathering 
- Tools for information gathering, in system, network, host
        -dmitry
        -ike- scan
        -legion
        -maltego
        -net discover
        -nmap
        -p0f
        -recon-ng
        -spider foot
        

             2) vulnerablity anyalisis
-Tools for Finding Vulnerabilities
           -legion
           -lynis  
           -nikto
           -nmap
           -unix perives

            3) web application analysis
-Tools for Finding Vulnerabilities and exploits on websites.
             -burpsuite
             -commix
             -httrack
             -paros
             -skipfish
             -sqlmap
             -webscarab
             -wpscan
             -ZAP
             
        4) Database Assessment
-Tools for Finding Vulnerabilities and exploits on Databases.
              -jsql injection
              -mdb-sql
              -oscanner
              -sidguesser
              -sqldict
              -sql map
              -sql ninja
              -sqlsus

            5) Password Attacks
-Tools for exploiting Passwords for login,websites,application, windows..
               -cewl
               -crunch
               -hashcat
               -medusa
               -ncrack
               -ophcrack
               -rainbow crack
               -raracki_mt

             6) Wireless Attacks
-Tools for exploiting Wireless Systems like wifi, bluetooth..
                -aircrack-ng
                -wifite
                -fern  wifi cracker
                -kismet
                -mdk3 
                -mofc
                -mfterm
                -pixiewps
                -cowpatty
                -reaver

              7) Reverse Engineering
-Tools for exploiting Softwares, Mobile Applications and any binary files
               -apktool
               -ghidra
               -Nasm shell
               -dex2jar
               -clang
               -ollydbg
               -javasnoop
               -java-gui
               -radare2

             8) Exploitation Tools
-Tools for exploiting Softwares, Mobile ,Computers ,websites...
               -armitage
               -metasploit framework
               -search sploit
               -termineter
               -sqlmap

            9) Sniffing & Spoofing
-Tools for Listening or hijacking networks
              -driftnet
              -hamster
              -macchanger
              -netsniff-ng
              -wireshark
              -responder
              -mitmproxy

             10) POST exploitation
-Tools for Maintaining our access. Used after exploiting a system
             -exe2hex
             -weevely
             -powersploit
             -nishang
             -mimikatz
             -proxychains4

            11) Forensics
-Tools for Doing researches and investigate a Cyber Attacks.
             -binwalk
             -autopsy
             -chkrookit
             -foremost
             -galleta
             -hashdeep

           12) Reporting tools
-Tools for Report preparation. After some forensic you will get data and you will write report
            -cutycapt
            -maltego
            -pipal

            13) Social Engineering tools
-Tools Used for Social Engineering attacks
            -maltego
            -msf payload
            -backdoor framework
            
            14) System Services
-Buttons used to start some services
             -beef start 
             -beef stop
             -dradis start
             -dradis stop

           15) Usually used applications
-Softwares for some basic purposes
 
		    Workspace manager 
- Used to Classify our works on different windows
           
           Folder managers
   1) Dolphin
  2) Nautilus 
  3) Thunar

             Linux Commands 
● Linux Systems uses shell. The shell help us to Communicate with the kernel and helps to execute codes.
● Shell also called “Terminal”
● The terminal have 5 parts.
○ Username = mihret
○ Hostname = kali
○ Current Directory = PATH 
○ Priviledge = $-(user) , #-(root) 
○ Command place = _ 
● Home directory is ~ 
● Local directory with . 
● All directory *

             Linux Command Basics 
● On linux there are over 100 commands. 
●  those commands have their own options and arguments

            What is command 
- Small programs that do one task well

       ls / List Directory
-SYNOPSIS ls [OPTION]... [FILE]... 
-List information about the FILEs (the current directory by default).
      
● ls -l
● ls -a  :used to access hidden files on linux
-Linux hidden files start with dot
● ls filename 
● ls -R => recursive
-You can combine them   ex: ls-rla

        cd / Change Directory
SYNOPSIS cd [directory]
It is used to change current working directory.
    ● cd / => root  
    ● cd => home
    ● cd .. => 1x Back
    ● cd ../.. => 2x Back 
    ● cd foldername
If folder name have space you have to add the name inside “ folder name “
      cd “folder name”
      
         Pwd / print working directory 
 SYNOPSIS pwd [-options]
It prints the path of the working directory, starting from the root. 
Example after typing pwd: /home/mx/Desktop/OSLab

            echo 
SYNOPSIS echo {option} {string}
echo command in linux is used to display line of text/string that are passed as an argument . This is a built in command that is mostly used in shell scripts and batch files to output status text to the screen or a file
   -You can write texts into files.
    ○ echo text > file.txt 
    -You can add texts(append) 
    ○ echo text >> file.txt
    
         cat / head / tail / less 
SYNOPSIS cat [FILE]...
Used to show the content of a file

       touch
SYNOPSIS touch FILE
-Creates any kind of Files with the name you gave it. With empty inside

      Mkdir / make directory
SYNOPSIS mkdir [FOLDER-NAME]  
DESCRIPTION Creates Folder with the name u gave it.
- DON’T forget to add the “ “ when you are using folders with space between them.

      clear 
SYNOPSIS clear 
-Clears your screen.

    rm / remove
SYNOPSIS rm [FILE1] [FILE2] [FILE3] 
 Remove file.
 ● rm -r => recursive
 ● rm -i => for prompt(ask) 
 ● rm -f => force delete
 -You can use them in combination too like, rm -rf ‘filename’
 
     Cp| mv / copy,move 
 SYNOPSIS cp {oldFILEplace} {newfilePlace}
                 Mv {oldFILEplace} {newfilePlace}
 - Copy/move files & folders.
 
        grep - global search for regular expression
  ● grep [options] pattern [files] 
  ● The grep filter searches a file for a particular pattern of characters, and displays all lines that contain that pattern. The pattern that is searched in the file is referred to as the regular expression (grep stands for global search for regular expression and print out)
  grep -i “search” file 
      ○ - case insensitive 
  ● grep -c “search” file 
       ○ - count numbers 
  ● grep -l “search” * 
      ○ - displays filename 
  ● grep -R “search” foldername 
      ○ - search text in folders 
  ● grep -v ‘term’ filename  
      ○ To display without this term 
  ● grep -n “term” file 
     ○ To display the term find number
    
	 Wc - word count
SYNOPSIS wc {OPTION}... {FILE}... 
- It is used to find out number of lines, word count, byte and characters count in the files specified in the file arguments.
- Line(-l) word(-w) byte(-c)

      Multiple Command Executions 
● You can run/ execute multiple commands in 1 line. 
● using 3 methods: 
- And ( && ) 
 -Or ( || ) 
 - Pipeing( | )
 
        AND ( && )
-On AND operation All commands you entered will be executed. If both are working without error
        
        OR ( || ) 
On OR operation the command will be executed. If it have error or not

     Piping ( | )  
-On pipe, will help you run commands by using the output of the 1st command as the input for the next one.