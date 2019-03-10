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
curl <url>
    -s|--silent                           # silent
    -o <outputfile>                       # Save response
    -O                                    # save file
    -d|--data 'name=bob'                  # url-encode and post data
    -d '@filename'                        # url-encode file data and post
    -u|--user <user>:<password> --basic   # Basic Auth
    -X|--request <method>                 # POST, PUT, DELETE, GET (default)
    -H|--header <header>                  # "Content-Type: application/json", "Accept: application/json"
    --proxy-user <domain>\\<usr>:<pwd> \
    --proxy <protocol>://<url>:<port> \
    --proxy-ntlm
    -v|--verbose
    -k|--insecure                         # allows curl to perform "insecure" SSL connections
VISUAM=vi crontab -e                      # Edit crontab (-l=list) minute hour dayOfMonth month dayOfWeek user command
```

## D

```bash
date -v1d -v+1m -v-1d -v-fri "+%d/%m/%Y"  # Display the last Friday of the month -v:adjust
df -hl                                    # free disk space -i:inode -h:human -l:locally-mounted
du -sh * | sort -h                        # disk usage. -s:entry for each file, -h:human -c:total
diff file1 file2                          # -w|--ignore-all-space -B|--ignore-blank-line -y|--side-by-side -r|--recursive -q|--brief(only file)
dirname                                   # directory portion of pathname
dig +short generali.fr                    # DNS lookup utility
```

## E

```bash
env                                       # print environment variables
export VAR1=value1                        # export var for subsequently started processes in a shell
exec command arguments
echo -n "$HOME"                           # -n:no print newline
exit                                      # exit from script
```

## F

```bash
find
fg                                        # Send job to foreground
file <filename>                           # determine file type
free -h                                   # display memory usage
for i in {1..10}; do echo $i; done
for afile in *; do echo "> $afile"; done  # * will match every file in the directory
```

## G

```bash
Grep 
gzip voir tar
```


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



https://ss64.com/bash/
