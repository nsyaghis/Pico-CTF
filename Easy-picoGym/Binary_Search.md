<h1 align="center">Binary Search</h1>

Binary search a data search algorithm that works by dividing data into two parts until it finds the value it is looking for.

The programme will randomly pick a new number every time we connect. We can always try again, but we have to start our binary search from scratch - try around 500. 


 ## Set Up SSH Connection

 ### 1. Open a Terminal
 You will use SSH (Secure Shell) to connect to the remote server.

### 2. Use the Provided SSH Command
 In your terminal, enter the following command to connect to the CTF server:

```
ssh -p 55441 ctf-player@atlas.picoctf.net
```
This will connect you to the CTF server on port ``` 64458 ```

### 3. Enter the Password: 
When prompted, enter the provided password ```6dd28e9b```. Passwords in a shell are hidden, so it will not show as you type.

### 4. Accept the Fingerprint:
 If this is the first time connecting, you will be prompted to accept the server's fingerprint. Type ```yes``` and press Enter.

 well here we explore the flag in guessing the correct number. if we have succeeded, we will be given the flag key.

 ![alt text](/images/Binary.png)
 ``` 
 picoCTF{g00d_gu355_de9570b0}
 ```