# CTF
 Capture the Flag (CTF) challenges covering Cryptography, OSINT, Miscellaneous, and Forensics categories, designed to test and engage participants in diverse cybersecurity skills.

 
# CRYPTOGRAPHY

# ROTTEN TO THE CORE

> Can you find the rotten apple in the given string?

#### NLPC{i0e_r4fo_p0exn_dro_b0ddox_4zzvo}

##### Solution

Reading the question given we can guess that the string is encoded using ROT.
Decode the given text on https://www.dcode.fr/rot-cipher or any other ROT decoder.

![image](https://github.com/user-attachments/assets/aa0587f5-f677-4aa9-acd2-3441fe5fc8df)

##### Flag: DBFS{y0u_h4ve_f0und_the_r0tten_4pple}

# ONE RING TO RULE THEM ALL

> Have you read Lord of the Ring's BOOK?

Three Rings for the Elven-kings under the sky,
Seven for the Dwarf-lords in their halls of stone,
Nine for Mortal Men doomed to die,
One for the Dark Lord on his dark throne,
In the Land of Mordor where the Shadows lie,
One ring to rule them all, one ring to find them,
One ring to bring them all and in the darkness bind them
In the Land of Mordor where the Shadows lie.

#### 4:4 8:8 2:5 8:5 3:2 1:5 5:9 7:3 6:10 3:1 3:3 3:4

##### Solution

Reading the question given we can see that it is related to the book cipher
Decode it using https://www.boxentriq.com/code-breaking/book-cipher or any other book cipher decoder

![image](https://github.com/user-attachments/assets/ce5d07ab-25b1-497a-9d31-683814848d0e)

##### Flag: DBFS{Dark Shadows in Mordor for Elvenkings lie to find Nine Mortal Men}

# I CHOOSE YOU PIKACHU

> Isn't Pikachu the best?

#### pi pi pi pi pi pi pi pi pi pi pika pipi pi pipi pi pi pi pipi pi pi pi pi pi pi pi pipi pi pi pi pi pi pi pi pi pi pi pichu pichu pichu pichu ka chu pipi pipi pipi ka ka pikachu ka ka pikachu pi pi pi pi pikachu pi pi pi pi pi pi pi pi pi pi pi pi pi pikachu pipi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pikachu ka ka pikachu pichu pichu pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pikachu pipi pipi ka ka ka ka pikachu pichu pi pi pi pi pi pi pi pi pi pi pi pi pikachu pi pi pikachu pipi ka ka ka pikachu pichu pichu pi pi pi pikachu pipi ka ka pikachu pi pi pi pi pikachu pichu ka ka ka pikachu pikachu pipi pipi ka ka ka ka ka ka ka pikachu pichu pi pi pikachu ka pikachu pipi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pikachu

##### Solution

The language is pika lang and can be decoded using https://martin.ingesen.no/Pikalang/.
It decodes to what can be identified as Brainfuck language. 
Decode the Brainfuck language using https://md5decrypt.net/en/Brainfuck-translator/ or any other decoder.

![image](https://github.com/user-attachments/assets/11ba693a-627a-4232-b487-6c052e0ca6f1)

![image](https://github.com/user-attachments/assets/01c1a4cd-3008-41d5-82d0-6b97f04da321)

##### Flag: DBFS{y0u_ar3_c00ked}

# GROOVING TO THE MUSIC

> Let's Dance.

#### ![image](https://github.com/user-attachments/assets/8a5a6e51-d0b6-40b7-aefd-58064153cb6f)

##### Solution

We can find the language used to encode here https://puzzculture.com/2021/01/21/musical-cryptography-hiding-messages-in-the-music/
Decode it using the key given.

![image](https://github.com/user-attachments/assets/507b58e9-277d-45f4-ab43-0322f934dbb6)

##### Flag: DBFS{music_is_the_answer}

# MISCELLANEOUS

# QR A CUTIE

> Scan me to unlock the surprise.

#### ![a1](https://github.com/user-attachments/assets/f376de5f-ff7f-4c6b-9d17-9fe28c86ca53)

#### ![a2](https://github.com/user-attachments/assets/073f9db1-0f29-4337-b7c3-52928d91dae7)

#### ![a3](https://github.com/user-attachments/assets/5c477188-5e59-4850-be0a-a15c7cfde028)

#### ![b1](https://github.com/user-attachments/assets/9f484deb-eceb-45ec-9b28-038b09ecb2a0)

#### ![b2](https://github.com/user-attachments/assets/d39afb28-b0ab-4e2f-8355-6fa06ce0b96a)

#### ![b3](https://github.com/user-attachments/assets/cb9815a3-6893-4d3e-ac7f-0188d8eacf9c)

##### Solution

Combine the QR code in correct order.
You can do it using https://www.fotor.com/features/combine-images/

![image](https://github.com/user-attachments/assets/1819c5ce-c7e1-423b-9fb6-28b795ce505f)

![image](https://github.com/user-attachments/assets/946dd3cf-fdab-4c17-b191-6de91fe1f706)

click on website.

![image](https://github.com/user-attachments/assets/dbb63b3d-9878-461e-b1dc-92f1c85ed14e)

##### Flag: DBFS{QR_4LL_th3_w4y}

# I LOVE CRYPTOGRAMS

> Can you solve this?

#### ![Decode me](https://github.com/user-attachments/assets/f5b2828a-5e01-4a1c-a504-0cafe17bd821)

##### Solution

To decode it you need the hit and trial method. See which letter fits perfectly where based on common letters and repetitions.
OR
It is a quote by Rachel Maddow. If you can find it, you are the winner.

##### Flag: DBFS{WHY DOES ACCOUNTABILITY KEEP HITTING A GLASS CEILING?}

