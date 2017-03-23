# unix-basic-instructions

<I>UNIX is a platform to let you can control , maintain the file and the system.The instructions are written on Terminal</I>
<I>Which we call it a command line in usual</I>

<b>show the files in the same level catalog:</b>

```
ls
```

<b>change to another directory(go deeper):</b>

```
cd/filename lv1/filename lv2
```

<b>back to the former directory(the lastest directory you went berfor):</b>

```
cd -
```

<b>back to the upper directory(closer to root):</b>

```
cd --
```

<b>back to the user's root directory:</b>

```
cd ~
```

<b>back to the system's root directory(in mac os is Macintosh HD):</b>

```
cd /
```

<b>create the directory:</b>

```
mkdir
```

<b>call the gcc compiler to compile the c code:</b>

```
gcc filename -o filename
```

<b>call the gcc compiler to compile the c++ code:</b>

```
g++ filename -o filename
```

<b>if it is compiled ,and the compiler doesn't show any error then it will come out of the execution file(compiler->Assembly language->Assember->Machine language->Linker merge it and put it in the disk).</b>

<b>And you can call it's filename to let loader to load it to memory and execute it:</b>

```
./filename
```

<b>check if you have gcc or not:</b>

```
which gcc
```

<b>download or update the program or files:</b>
< depent by case Ex: pipe python3>

```
pipe
```

<b>see the information of the instruction:</b>

```
man instructionname
```

<b>quite the information page:</b>

```
q
```

<I>other professional instructions</I>

<b>using xxd, a command-line "hex editor.":</b>

```
xxd -c 36 -g 2 -s 54 filename.bmp    
```

<b>notes：</b>

<b>-s means start from where,and the address is by hexadecimal(transform from decimal to hexadecimal)in the case 0000036</b>

<b>-g means how many words in one block by byte</b>

<b>-c means how many data in a row by byte</b>

<b>Test the file category:</b>
```
file  <filename>
```
<b>If you meet :"-bash: ./2: Permission denied" when execute file on command line:</b>
```
chmod u+x  <filename>
```
