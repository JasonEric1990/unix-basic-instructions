# unix-basic-instructions

<I>UNIX is a platform to let you can control , maintain the file and the system.The instructions are written on Terminal</I>

<b>show the files in the same level catalog:</b>

```{r echo=FALSE}
ls
```{r}

<b>change to another directory(go deeper):</b>

```{r}
cd/filename lv1/filename lv2
```

<b>back to the former directory(the lastest directory you went berfor):</b>

```{r}
cd -
```

<b>back to the upper directory(closer to root):</b>

```{r}
cd --
```

<b>back to the user's root directory:</b>

```{r}
cd ~
```

<b>back to the system's root directory(in mac os is Macintosh HD):</b>

```{r}
cd /
```

<b>create the directory:</b>

```{r}
mkdir
```

<b>call the gcc compiler to compile the c code:</b>

```{r}
gcc filename -o filename
```

<b>call the gcc compiler to compile the c++ code:</b>

```{r}
g++ filename -o filename
```

<b>if it is compiled ,and the compiler doesn't show any error then it will come out of the execution file(compiler->Assembly language->Assember->Machine language->Linker merge it and put it in the disk).</b>

<b>And you can call it's filename to let loader to load it to memory and execute it:</b>

```{r}
./filename
```

<b>check if you have gcc or not:</b>

```{r}
which gcc
```

<b>download or update the program or files:</b>
< depent by case Ex: pipe python3>

```{r}
pipe
```

<b>see the information of the instruction:</b>

```{r}
man instructionname
```

<b>quite the information page:</b>

```{r}
q
```
