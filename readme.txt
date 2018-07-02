Instructions:
This python script(written in python3+) reads csv data file and automatically creates a html file on the same directory. The script can be a demo of python reading data from file and re-constructing into different format of files. To run this script properly, you should:

1. Copy the python file and data csv file to your Linux machine folder. With SFTP or any other methods.
2. Enter the directory you've just transferred the two files. Run the python script(e.g. python3 data.py).
3. Initiate python HTTP server by typing 'python3 -m http.server 8080' and hit enter button.
4. When your python HTTP server is up, type the url 'http://your linus machine ip:8080/data.html' on a browser to view the data table(e.g. http://192.168.128.144:8080/data.html).

All done. Note: The html data table can be sorted and filtered. Have a try.

P.S. The data html file is driven by open-sourced JS codes. ALL rights belong to original author.