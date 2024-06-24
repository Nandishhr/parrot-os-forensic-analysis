<h1>Lhedge - Linux Forensic Analysis Tool</h1>
Please ensure you download the following dependecies before using Lhedge Services for Parrot OS:
<br><br>
1. Install Rsyslog
<ul>
 <li>`sudo apt update`</li>
 <li>sudo apt install rsyslog</li>
 <li>sudo systemctl enable rsyslog</li>
 <li>sudo systemctl start rsyslog</li>
 <li>sudo systemctl status rsyslog</li>
</ul>
2. Install Python3-Docx
<ul>
 <li>sudo apt install python3-docx</li>
</ul>
3. Install Watchdog
<ul>
 <li>sudo apt install python3-watchdog</li>
</ul>
4. Instal ClamAV
<ul>
 <li>sudo apt update</li>
 <li>sudo apt install clamav clamav-daemon</li>
 <li>sudo freshclam</li>
 <li>sudo systemctl enable clamav-daemon</li>
 <li>sudo systemctl start clamav-daemon</li>
 <li>sudo systemctl status clamav-daemon</li>
</ul>
5. Install GeoIPLookup
<ul>
 <li>sudo apt install geoip-bin</li>
</ul>
<h3>Set Up Download Directory</h3>
Create a folder and install NW.js inside it
<ul>
 <li>cd /path/to/directory</li>
 <li>npm init -y</li>
 <li>npm install nw --save-dev</li>
</ul>
Copy and paste all the files of Lhedge-Version1 into directory.
<br>
Create a dekstop launcher into the directory. 
<ul>
 <li>cd /path/to/directory</li>
 <li>sudo python3 run.py</li>
</ul>
Cut and paste Lhedge.desktop into your Desktop for easy access to the app.
<br>
Alternative: You can also give a command in your directory through the terminal to access the app.
<ul>
 <li>cd /path/to/directory</li>
 <li>sudo npx nw .</li>
</ul>
<br>
