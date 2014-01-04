fuzzyftp
========

I created this project as part of my thesis, where I presented computer security
and it’s importance in the modern world. I tested the fuzzyftp on different FTP
servers with a goal of finding existing vulnerabilities to prove that fuzzyftp can
be used to find vulnerabilities in real world FTP servers. The table below presents
the FTP servers and existing vulnerabilities that I was able to detect with Peach 
and Sulley FTP input file.

| FTP Server | Known Vulnerabilities | Sulley | Peach |
| -----------| --------------- 
| SlimFTPd 3.15 | CWD | 0 | 1 |
| | STOR | 0 | 1 |
| | MKD | 0 | 1 |
| | STAT | 0 | 1 |
| | Other | 0 | 10 |
| | None | 0 | 0 |
| EasyFTP 1.7.0.11 | CWD | 1 | 1 |
| EasyFTP 1.7.0.11 | LIST | 1 | 1 |
| EasyFTP 1.7.0.11 | MKD | 1 | 1 |
| EasyFTP 1.7.0.11 | DELE | 1 | 1 |
| EasyFTP 1.7.0.11 | STOR | 1 | 1 |
| EasyFTP 1.7.0.11 | RNFR | 1 | 1 |
| EasyFTP 1.7.0.11 | RMD | 1 | 1 |
| EasyFTP 1.7.0.11 | XRMD | 1 | 1 |
| EasyFTP 1.7.0.11 | NLST | 1 | 1 |
| EasyFTP 1.7.0.11 | APPE | 1 | 1 |
| EasyFTP 1.7.0.11 | RETR | 1 | 1 |
| EasyFTP 1.7.0.11 | SIZE | 1 | 1 |
| EasyFTP 1.7.0.11 | XCWD | 1 | 1 |
| Cesar FTP 0.99g | MKD | 0 | 1 |
| Serv-U 4.1.0.0 | MDTM | 0 | 0 |

