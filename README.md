Forus
=====

test play url:
http://101.227.14.43:8080/hls/live/cctvxw/index.m3u8

m3u8 format:
#EXTM3U
#EXT-X-VERSION:3
#EXT-X-MEDIA-SEQUENCE:58304
#EXT-X-TARGETDURATION:10
#EXTINF:8.904,
58304.ts
#EXTINF:10.017,
58305.ts
#EXTINF:10.001,
58306.ts

tracker protocol:
request:
http://livetracker.12399.org/query?c=cctvxw&k=58304.ts

response:
{"tsz": 315421, "tmd5": "639129455bbb911224e36c9668a0885e", "block_num": 4, 
"blocks":[{"sn": 0, "sz": 102400, "md5": "639129455bbb911224e36c9668a0885e"}, 
{"sn": 1, "sz": 102400, "md5": "639129455bbb911224e36c9668a0885e"},
{"sn": 2, "sz": 102400, "md5": "639129455bbb911224e36c9668a0885e"},
{"sn": 3, "sz": 8221, "md5": "639129455bbb911224e36c9668a0885e"}], 
"urls": [{"ip": "10.121.33.41", "port": 14347, "nat": 1}, 
{"ip": "10.121.33.42", "port": 14347, "nat": 5}, 
{"ip": "10.121.33.45", "port": 14344, "nat": 2},
{"ip": "10.121.33.49", "port": 14342, "nat": 4}]}

p2p protocol:
后续补充
