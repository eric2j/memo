# shell / bash / cli - from a to z

Apprenez moi des commandes linux.

## A

```bash
alias ll='ls -alF'                      # set or dispaly alias
awk                                     # pattern scanning and text processing language
addgroup ccjava --gid 1001              # add group to system
adduser --uid 1001 --gid 1001 --home /home/ccjava --shell=/bin/bash ccjava
arch                                    # machine hardware name
echo "script.sh" | at now +1 hours      # delay command
```

## B

```bash
bash myscript.sh  
bg                                      # move task in background (see fg)
basename filename.ext                   # strip directory and suffix from filenames
echo user:password | base64             # encode / decode (-d) data and print to standard output
```

## C

```bash
cal                                     # displays a calendar and the date
cat                                     # concatenate and print file
cd                                      # change directory
chmod                                   # user/group/other read/write/execute. 644=u:read+write go:read, go-w=deny write permission
                                        # -R recursive
chown [-R] <user>:<group> file          # change file owner and group
clear                                   # clear the terminal screen
column -t -s ","                        # Columnate lists. -t:table, -s delimiter
cp                                      # -L:follow sym links, -p:preserve attributes, -R recurse
cut -d':' -f1,2                         # cut -d:delimiter, -f:field
curl                                    # transfert URL
VISUAM=vi crontab -e                    # Edit crontab (-l=list) minute hour dayOfMonth month dayOfWeek user command
```

## D

```bash
date
df
du
diff
dirname
dig
```



## E



```bash
env
export
exec
echo
```



Find fg file
Grep 
gzip voir tar



Head history 
Ifconfig
Jq join
Kill

## L
```bash
less
ls
ln -s <source> <link>
locate
lscpu                                   # display information about the CPU architecture
```

Man “mkdir -p” more mv
Netstat nmon nslookup
O
Ping ps pwd
Q
Rev rsync (preserve link)
Sed source sort



Tail Tee tldr top 
tar archive, avec -z compress gzip



Uniq uname
Vi
Wget wc whereis which whoami
Xargs
Y
Z
$






> Written with [StackEdit](https://stackedit.io/).