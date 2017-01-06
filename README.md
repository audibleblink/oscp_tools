# OSCP Tools

A collection of modded scripts from around the web to be used with OSCP


### CHANGELOG

- linuxprivesc.py

  - added a `sudo -ll` check for programs runnable via sudo
  - clearer denotation of sections

- recon_scan

  - multithreaded http/s, ssh, dns, smb, mysql scanner
  - fixed all absolute paths so script can be run from anywhere
  - consolidated scan output files
  - create a folder for each target and place scan results in there
  - fixed bug where results were overwritten if more than 1 http site existed
    on the same server
