1. Download gdrive
```bash
wget https://docs.google.com/uc?id=0B3X9GlR6EmbnQ0FtZmJJUXEyRTA&export=download
``` 
2. Rename the file downloaded
```bash
mv uc?id=0B3X9GlR6EmbnQ0FtZmJJUXEyRTA gdrive
``` 
3. move the file to /usr/bin
```bash
mv gdrive /usr/bin
```
4. Give permissions
```bash
sudo chmod +x /usr/bin/gdrive
```
5. Connect to google drive
```bash
gdrive about
``
Afert this step, copy and open the link provided by gdrive,thereafter copy the key priovied and paste to the terminal  to connect to google drive servic
6. Configure crontab to use with gdrive

- Example
0 0 * * 0 root /path/to/script


get files and directories with id's
* gdrive list
