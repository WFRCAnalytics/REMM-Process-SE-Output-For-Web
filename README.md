# REMM-Process-SE-Output-For-Web
Process progression metrics output for use in the web app

1. Process-Centers-For-Web
- load se pickles from shared drive
- run script

2. Process-TAZ-Outputs-For-Web
- old se output is from wfrc data portal (RTP 2019)
- new se output is from REMM travel model output (RTP 2023)
- if running for first time, script will "pause" to run apportion function in arcgis pro

3. Update-TAZ-Outputs-For-Web
- Run process script first
- For ArcGIS Online, setup username and password in windows credential manager 
- For File Server, setup username, ip address, and password in windows credential manager