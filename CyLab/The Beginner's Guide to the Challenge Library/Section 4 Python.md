

## PW Crack 2

chr(0x34) + chr(0x65) + chr(0x63) + chr(0x39) = 4ec9

chr in python reads as character, 0x__ reads a hex

```
Please enter correct password for flag: 4ec9
Welcome back... your flag, user:
academy{tr45h_51ng1ng_d99a9ef4}
```

## PW Crack 3

do: `$ bvi level3.hash.bin`

```
$daniel bvi level3.hash.bin
00000000  F4 17 19 38 89 02 E5 1C 11 1A 57 78 B4 66 9F CB                         ...8......Wx.f..
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
"level3.hash.bin" 16 bytes                                             00000000 11110100 \364 0xF4 244
```

```
level_3_pw_check()
#The strings below are 7 possibilities for the correct password.
#(Only 1 is correct)
pos_pw_list = ["6997", "3ac8", "f0ac", "4b17", "ec27", "4e66", "865e"]
```

```
$daniel python3 level3.py
Please enter correct password for flag: ec27
Welcome back... your flag, user:
academy{m45h_fl1ng1ng_b8034615}
``` 

## PW Crack 4

