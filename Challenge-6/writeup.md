Shattered_Trust:

initially this task provides a zip folder

After extracting files I found decryption stage1 stage2 stage3 stage4

In the decryption there is a decryption.enc.txt and password.txt 
after decrypting the password.txt In cyberchef(multiple from base64) I found password to be lollipop

openssl enc -d -aes-256-cbc -pbkdf2 -in description.txt.enc -out decrypted.txt -pass file:password.txt

later I decrypted the decryption.enc.txt file as i know the passsword later I found the flag format "flag1_flag2_flag3_flag4"

after that in stage1 I found the flag as="b_oracle_master" by changing the server.py code by connecting cipher.bin
