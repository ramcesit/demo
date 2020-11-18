# demo
1. Compress multiple files
tar -cvzf my_files.tar.gz latin.pth craft_mlt_25k.pth

2. Split my_files into 20 MB
split -b 20M my_files.tar.gz "my_files.tar.gz.part"


3. Combine all parts into a single file
cat my_files.tar.gz.parta* >complete.tar.gz


4. Unzip the file 
tar -xvzf complete.tar.gz
