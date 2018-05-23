# CVE-2018-8174-msf
This is a metasploit module which creates a malicious word document to exploit CVE-2018-8174 - VBScript memory corruption vulnerability.

This module is a very quick port and uses the exploit sample that was found in the wild. The exploit works only for Microsoft Office 32-bit.

There are a lot of things that need to get better at this module but I will update it in the future if I find some time.

## Installation
1) Copy the CVE-2018-8174.rb to /usr/share/metasploit-framework/modules/exploits/windows/fileformat/
2) Copy the CVE-2018-8174.rtf to /usr/share/metasploit-framework/data/exploits/


The exploit doesn't work very well with meterpreter shellcode so it's better to use non-staged reverse shell.


## Disclaimer

DO NOT USE THIS SOFTWARE FOR ILLEGALL PURPOSES.

THE AUTHOR DOES NOT KEEP ANY RESPONSIBILITY FOR ANY MISUSE OF THE CODE PROVIDED HERE.


