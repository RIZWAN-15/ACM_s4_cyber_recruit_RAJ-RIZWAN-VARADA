Letter from Hogwarts:

This task initially gives a pdf which needs password to open and flag might be there in the pdf

I tried brutforce so I installed rock.you.txt from online 
then later for bruteforce I converted pdf to hash
by
pdf2john Letter_from_Hogwarts.pdf > hash.txt

later the pdf turns to hash value and this hash value and the hash value of rock.you.txt is comparing
john --wordlist=wordlist.txt hash.txt

at last i found the password for pdf and inside the pdf I found the flag

final flag=potter{w3lc0m3_70_h0gw4r75}
