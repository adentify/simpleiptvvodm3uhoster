# simpleiptvvodm3uhoster
Host your own VOD system compatible with most IPTV apps that support Xtream API m3u lists. 

NB: This is my first experiment in getting ChatGPT to write as much of rhe code as I can, currently this only includes the bash scripts:
 - to get directory/file listings and generate the raw m3u files
 - run tests against these m3u files to check public availability/access

2025-09-02:
Getting basic system to traverse directories and get file names then output to a vod.m3u
Created tests.sh to check the output of the file, checks using curl
added basic security whilst alpha work is done.
