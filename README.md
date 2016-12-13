# unix-basic-instructions

<I>UNIX is a platform to let you can control , maintain the file and the system.The instructions are written on Terminal</I>

<b>show the files in the same level catalog:</b>

```{r echo=FALSE}
ls
```{r}

<b>change to another directory(go deeper):</b>

```{r}
cd/filename lv1/filename lv2
```{r}

<b>back to the former directory(the lastest directory you went berfor):</b>

```{r}
cd -
```{r}

<b>back to the upper directory(closer to root):</b>

```{r}
cd --
```{r}

<b>back to the user's root directory:</b>

```{r}
cd ~
```{r}

<b>back to the system's root directory(in mac os is Macintosh HD):</b>

```{r}
cd /
```{r}

<b>create the directory:</b>

```{r}
mkdir
```{r}

<b>call the gcc compiler to compile the c code:</b>

```{r}
gcc filename -o filename
```{r}

<b>call the gcc compiler to compile the c++ code:</b>

```{r}
g++ filename -o filename
```{r}

<b>if it is compiled ,and the compiler doesn't show any error then it will come out of the execution file(compiler->Assembly language->Assember->Machine language->Linker merge it and put it in the disk).</b>

<b>And you can call it's filename to let loader to load it to memory and execute it:</b>

```{r}
./filename
```{r}

<b>check if you have gcc or not:</b>

```{r}
which gcc
```{r}

<b>download or update the program or files:</b>
< depent by case Ex: pipe python3>

```{r}
pipe
```{r}

<b>see the information of the instruction:</b>

```{r}
man instructionname
```{r}

<b>quite the information page:</b>

```{r}
q
```{r}
