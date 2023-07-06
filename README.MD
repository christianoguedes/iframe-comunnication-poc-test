Test application to send messages through iframe from different domains without having problems such as 'blocked cross domain'.

To execute, type in the directory of this repository:

`python3 -m http.server 8000 & python3 -m http.server 8001 & python3 -m http.server 8002`

Open in browser http://localhost:8000

After open:
- First frame 2s delayed
- Second frame 5s delayed

To all kill execute:
pkill -fi http.server
