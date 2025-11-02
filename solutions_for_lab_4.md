# Solutions for exercises from lab 4  
*Author: Arda Yanıkan*  
*System: macOS Terminal*  

---

## Exercise 1
```bash
cd ~
ls -l
ls -lhS /var/log
nano firstname.txt
# (write: Arda)
echo "Yanıkan" > lastname.txt
cat firstname.txt lastname.txt
cat lastname.txt >> firstname.txt
ls -d */ > folders_list.txt
## Exercise 8
```bash
find /Users -type f -empty 2>/dev/null
find ~ -type f > ~/my_files.txt
find / -user "$USER" 2>/dev/null
find ~ -type f -mtime -1
find /usr -type f -iname "*mozilla*" 2>/dev/null
find /usr -type d -name "bin" 2>/dev/null


