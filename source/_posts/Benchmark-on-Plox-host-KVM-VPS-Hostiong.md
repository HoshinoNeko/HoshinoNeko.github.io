---
title: Benchmark on Plox.host KVM VPS Hostiong
date: 2021-12-28 19:47:21
tags: vps
---
Lemonbench full test result [https://paste.ubuntu.com/p/TXFBkKymGC](https://paste.ubuntu.com/p/TXFBkKymGC)
<!-- more -->
```bash
LemonBench Linux System Benchmark Utility Version 20201005 Intl BetaVersion 
 
 Bench Start Time:	2021-12-28 06:33:53
 Bench Finish Time:	2021-12-28 07:07:45
 Test Mode:		Full Mode
 
 -> System Information
 
 OS Release:		Debian GNU/Linux "Sid (Testing)" 11.1 (x86_64)
 CPU Model:		Intel(R) Xeon(R) CPU E5-2690 0 @ 2.90GHz  2.90 GHz
 CPU Cache Size:	20480 KB
 CPU Number:		1 vCPU
 Virt Type:		KVM
 Memory Usage:		301.62 MB / 976.38 MB
 Swap Usage:		82.86 MB / 1023.00 MB
 Disk Usage:		2.01 GB / 19.59 GB
 Boot Device:		/dev/vda1
 Load (1/5/15min):	4.52 1.72 0.69 
 CPU Usage:		11.8% used, 0.0% iowait, 0.0% steal
 Kernel Version:	5.10.0-9-amd64
 Network CC Method:	bbr + fq

 -> Network Information

 IPV4 - IP Address:	[US] 66.11.123.*
 IPV4 - ASN Info:	398395 (DOT-TECH-LLC - Dot-Tech LLC, US)
 IPV4 - Region:		United States Texas Dallas
 IPV6 - IP Address:	[US] 2602:ffc5:105:301::1217:*
 IPV6 - ASN Info:	398395 (DOT-TECH-LLC - Dot-Tech LLC, US)
 IPV6 - Region:		United States United States 

 -> Media Unlock Test

 HBO Now:				Yes
 Bahamut Anime:				No
 Abema.TV:				No
 Princess Connect Re:Dive Japan:	Yes
 BBC:					No
 Bilibili China Mainland Only:		No
 Bilibili Hongkong/Macau/Taiwan:	No
 Bilibili Taiwan Only:			No

 -> CPU Performance Test (Standard Mode, 3-Pass @ 30sec)

 1 Thread Test:			705 Scores

 -> Memory Performance Test (Standard Mode, 3-Pass @ 30sec)

 1 Thread - Read Test :		13330.21 MB/s
 1 Thread - Write Test:		11803.07 MB/s

 -> Disk Speed Test (4K Block/1M Block, Direct-Write)

 Test Name		Write Speed				Read Speed
 10MB-4K Block		16.6 MB/s (4059 IOPS, 0.63 s)		27.9 MB/s (6808 IOPS, 0.38 s)
 10MB-1M Block		352 MB/s (335 IOPS, 0.03 s)		313 MB/s (298 IOPS, 0.03 s)
 100MB-4K Block		18.3 MB/s (4467 IOPS, 5.73 s)		25.0 MB/s (6106 IOPS, 4.19 s)
 100MB-1M Block		509 MB/s (485 IOPS, 0.21 s)		775 MB/s (739 IOPS, 0.14 s)
 1GB-4K Block		21.4 MB/s (5226 IOPS, 48.98 s)		23.5 MB/s (5725 IOPS, 44.71 s)
 1GB-1M Block		153 MB/s (146 IOPS, 6.85 s)		382 MB/s (364 IOPS, 2.74 s)

 -> Speedtest.net Network Speed Test

 Node Name			Upload Speed	Download Speed	Ping Latency	Server Name
 Speedtest Default		57.42 MB/s	112.01 MB/s	3.30 ms		Cloudflare (United States Dallas, TX)
 China, Nanjing CU  		33.18 MB/s	37.52 MB/s	268.92 ms	China Unicom (China Nanjing)
 China, Shanghai CU 		34.73 MB/s	84.05 MB/s	271.19 ms	China Unicom 5G (China ShangHai)
 China, Hangzhou CT 		Fail: Timeout Exceeded after 60 seconds
 China, Nanjing CT  		21.82 MB/s	55.55 MB/s	225.54 ms	China Telecom JiangSu 5G (China Nanjing)
 China, Guangzhou CT		6.13 MB/s	39.21 MB/s	228.79 ms	ChinaTelecom 5G (China Guangzhou)
 China, Wuhan CT    		2.80 MB/s	19.77 MB/s	235.09 ms	China Telecom Wuhan Branch (China Wuhan)
 China, Shenyang CM 		Fail: Timeout Exceeded after 60 seconds
 China, Hangzhou CM 		30.79 MB/s	92.68 MB/s	220.96 ms	China Mobile Group Zhejiang Co.,Ltd (China Hangzhou)
 China, Nanning CM  		31.33 MB/s	69.50 MB/s	289.54 ms	GX ChinaMobile (China Nanning)
 China, Lanzhou CM  		22.19 MB/s	53.31 MB/s	256.51 ms	Lanzhou,China Mobile,Gansu (China Lanzhou)
 Hong Kong, CSL     		27.08 MB/s	5.63 MB/s	190.51 ms	CSL (Hong Kong Kwai Chung)
 Hong Kong, PCCW    		50.01 MB/s	57.99 MB/s	189.68 ms	STC (China Hong Kong)
 Korea, South Korea 		43.02 MB/s	58.85 MB/s	174.75 ms	kdatacenter.com (South Korea Seoul)
 Japan, GLBB        		Fail: Timeout Exceeded after 60 seconds
 Taiwan, FET        		Fail: Timeout Exceeded after 60 seconds
 Taiwan, Chief      		55.02 MB/s	90.78 MB/s	172.66 ms	Chief Telecom (Taiwan Taoyuan)
 Taiwan, TWM        		56.14 MB/s	98.48 MB/s	167.73 ms	Taiwan Mobile (Taiwan Taoyuan)
 Singapore, Singtel 		Fail: Timeout Exceeded after 60 seconds
 Singapore, M1      		36.72 MB/s	16.46 MB/s	251.12 ms	M1 Limited (Singapore Singapore)
 Singapore, NME     		1.71 MB/s	11.17 MB/s	282.02 ms	NewMedia Express (Singapore Singapore)
 USA, Century Link  		106.93 MB/s	98.39 MB/s	56.17 ms	CenturyLink (United States Seattle, WA)

 -> Traceroute Test (IPV4)


Traceroute to China, Beijing CU (TCP Mode, Max 30 Hop)
============================================================
traceroute to 123.125.99.1 (123.125.99.1), 30 hops max, 32 byte packets
 1  10.0.2.1  1.30 ms  *  LAN Address
 2  *
 3  206.71.158.6  0.93 ms  AS396998  United States, Texas, Dallas, path.net
 4  219.158.33.49  260.25 ms  AS4837  United States, California, Los Angeles, ChinaUnicom
 5  219.158.96.233  250.51 ms  AS4837  China, Guangdong, Guangzhou, ChinaUnicom
 6  173.241.128.50  243.25 ms  AS3257  United States, California, Los Angeles, gtt.net
 7  219.158.96.233  251.66 ms  AS4837  China, Guangdong, Guangzhou, ChinaUnicom
 8  219.158.111.121  277.66 ms  AS4837  China, ChinaUnicom
 9  219.158.3.141  274.76 ms  AS4837  China, Beijing, ChinaUnicom
10  *
11  *
12  61.148.4.234  280.64 ms  AS4808  China, Beijing, ChinaUnicom
13  124.65.194.46  279.58 ms  AS4808  China, Beijing, ChinaUnicom
14  61.135.113.154  281.03 ms  AS4808  China, Beijing, ChinaUnicom
15  *
16  123.125.99.1  296.45 ms  AS4808  China, Beijing, ChinaUnicom


Traceroute to China, Beijing CT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 180.149.128.1 (180.149.128.1), 30 hops max, 32 byte packets
 1  10.0.2.1  1.02 ms  *  LAN Address
 2  *
 3  206.71.158.6  36.87 ms  AS396998  United States, Texas, Dallas, path.net
 4  129.250.7.69  43.10 ms  AS2914  ntt.com
 5  129.250.2.104  32.18 ms  AS2914  United States, California, Los Angeles, ntt.com
 6  129.250.7.69  29.21 ms  AS2914  ntt.com
 7  129.250.2.104  35.65 ms  AS2914  United States, California, Los Angeles, ntt.com
 8  218.30.53.108  36.34 ms  AS4134  United States, California, Los Angeles, ChinaTelecom
 9  202.97.41.197  181.14 ms  AS4134  China, Beijing, ChinaTelecom
10  202.97.12.53  195.35 ms  AS4134  China, Beijing, ChinaTelecom
11  *
12  *
13  *
14  180.149.128.1  187.49 ms  AS23724  China, Beijing, ChinaTelecom


Traceroute to China, Beijing CM (TCP Mode, Max 30 Hop)
============================================================
traceroute to 211.136.25.153 (211.136.25.153), 30 hops max, 32 byte packets
 1  10.0.2.1  1.29 ms  *  LAN Address
 2  *
 3  206.71.158.6  17.04 ms  AS396998  United States, Texas, Dallas, path.net
 4  129.250.4.154  43.83 ms  AS2914  United States, California, San Jose, ntt.com
 5  129.250.5.77  145.57 ms  AS2914  Japan, Tokyo, ntt.com
 6  129.250.4.154  44.43 ms  AS2914  United States, California, San Jose, ntt.com
 7  129.250.5.77  143.20 ms  AS2914  Japan, Tokyo, ntt.com
 8  129.250.2.51  251.50 ms  AS2914  China, Hong Kong, ntt.com
 9  129.250.5.33  264.76 ms  AS2914  ntt.com
10  *
11  *
12  *
13  *
14  *
15  *
16  221.176.21.229  286.55 ms  AS9808  China, Beijing, ChinaMobile
17  111.24.17.162  288.67 ms  AS9808  China, Beijing, ChinaMobile
18  111.24.3.18  291.57 ms  AS9808  China, Beijing, ChinaMobile
19  *
20  *
21  211.136.95.226  289.68 ms  AS56048  China, Beijing, ChinaMobile
22  211.136.95.226  310.34 ms  AS56048  China, Beijing, ChinaMobile
23  *
24  211.136.25.153  290.30 ms  AS56048  China, Beijing, ChinaMobile


Traceroute to China, Shanghai CU (TCP Mode, Max 30 Hop)
============================================================
traceroute to 58.247.0.49 (58.247.0.49), 30 hops max, 32 byte packets
 1  10.0.2.1  1.49 ms  *  LAN Address
 2  *
 3  206.71.158.6  19.87 ms  AS396998  United States, Texas, Dallas, path.net
 4  219.158.33.49  256.76 ms  AS4837  United States, California, Los Angeles, ChinaUnicom
 5  219.158.96.233  249.33 ms  AS4837  China, Guangdong, Guangzhou, ChinaUnicom
 6  199.229.231.206  240.55 ms  AS3257  gtt.net
 7  219.158.96.233  251.84 ms  AS4837  China, Guangdong, Guangzhou, ChinaUnicom
 8  219.158.8.141  278.96 ms  AS4837  China, Shanghai, ChinaUnicom
 9  219.158.113.134  269.07 ms  AS4837  China, Shanghai, ChinaUnicom
10  219.158.113.109  267.26 ms  AS4837  China, Shanghai, ChinaUnicom
11  *
12  139.226.214.33  277.32 ms  AS17621  China, Shanghai, ChinaUnicom
13  58.247.0.49  272.53 ms  AS17621  China, Shanghai, ChinaUnicom


Traceroute to China, Shanghai CT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 180.153.28.1 (180.153.28.1), 30 hops max, 32 byte packets
 1  10.0.2.1  3.83 ms  *  LAN Address
 2  *
 3  206.71.158.6  15.85 ms  AS396998  United States, Texas, Dallas, path.net
 4  63.223.46.26  40.10 ms  AS3491,AS31713  United States, pccw.com
 5  218.30.54.96  40.27 ms  AS4134  United States, Florida, Miami, ChinaTelecom
 6  63.223.46.26  40.17 ms  AS3491,AS31713  United States, pccw.com
 7  218.30.54.96  43.07 ms  AS4134  United States, Florida, Miami, ChinaTelecom
 8  202.97.63.93  70.14 ms  AS4134  United States, California, Los Angeles, ChinaTelecom
 9  202.97.41.237  219.65 ms  AS4134  China, Shanghai, ChinaTelecom
10  *
11  *
12  61.152.26.73  215.60 ms  AS4812  China, Shanghai, ChinaTelecom
13  *
14  *
15  101.227.255.34  228.68 ms  AS4812  China, Shanghai, ChinaTelecom
16  *
17  180.153.28.1  213.41 ms  AS4812  China, Shanghai, ChinaTelecom


Traceroute to China, Shanghai CM (TCP Mode, Max 30 Hop)
============================================================
traceroute to 221.183.55.22 (221.183.55.22), 30 hops max, 32 byte packets
 1  10.0.2.1  1.75 ms  *  LAN Address
 2  *
 3  206.71.158.6  26.31 ms  AS396998  United States, Texas, Dallas, path.net
 4  129.250.4.154  45.77 ms  AS2914  United States, California, San Jose, ntt.com
 5  129.250.5.77  145.55 ms  AS2914  Japan, Tokyo, ntt.com
 6  129.250.4.154  39.95 ms  AS2914  United States, California, San Jose, ntt.com
 7  129.250.5.77  150.33 ms  AS2914  Japan, Tokyo, ntt.com
 8  129.250.2.51  251.71 ms  AS2914  China, Hong Kong, ntt.com
 9  129.250.6.123  251.64 ms  AS2914  China, Hong Kong, ntt.com
10  *
11  223.120.2.57  285.15 ms  AS58453  China, Hong Kong, ChinaMobile
12  *
13  *
14  221.183.55.22  260.98 ms  AS9808  China, Shanghai, ChinaMobile


Traceroute to China, Guangzhou CU (TCP Mode, Max 30 Hop)
============================================================
traceroute to 210.21.4.130 (210.21.4.130), 30 hops max, 32 byte packets
 1  10.0.2.1  2.03 ms  *  LAN Address
 2  *
 3  206.71.158.6  20.00 ms  AS396998  United States, Texas, Dallas, path.net
 4  219.158.39.101  270.87 ms  AS4837  United States, California, San Jose, ChinaUnicom
 5  219.158.116.237  258.57 ms  AS4837  China, Shanghai, ChinaUnicom
 6  173.205.56.142  255.83 ms  AS3257  United States, California, San Jose, gtt.net
 7  219.158.116.237  260.41 ms  AS4837  China, Shanghai, ChinaUnicom
 8  219.158.8.185  251.68 ms  AS4837  China, Beijing, ChinaUnicom
 9  219.158.7.129  252.75 ms  AS4837  China, Shanghai, ChinaUnicom
10  *
11  112.91.0.246  250.34 ms  AS17816  China, Guangdong, Guangzhou, ChinaUnicom
12  120.80.175.70  257.68 ms  AS17622  China, Guangdong, Guangzhou, ChinaUnicom
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *


Traceroute to China, Guangzhou CT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 113.108.209.1 (113.108.209.1), 30 hops max, 32 byte packets
 1  10.0.2.1  1.31 ms  *  LAN Address
 2  *
 3  206.71.158.6  19.62 ms  AS396998  United States, Texas, Dallas, path.net
 4  218.30.54.100  39.86 ms  AS4134  United States, California, San Jose, ChinaTelecom
 5  202.97.58.249  207.08 ms  AS4134  China, Guangdong, Guangzhou, ChinaTelecom
 6  218.30.54.100  39.65 ms  AS4134  United States, California, San Jose, ChinaTelecom
 7  202.97.58.249  207.22 ms  AS4134  China, Guangdong, Guangzhou, ChinaTelecom
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *


Traceroute to China, Guangzhou CM (TCP Mode, Max 30 Hop)
============================================================
traceroute to 211.139.129.5 (211.139.129.5), 30 hops max, 32 byte packets
 1  10.0.2.1  1.15 ms  *  LAN Address
 2  *
 3  206.71.158.6  19.64 ms  AS396998  United States, Texas, Dallas, path.net
 4  211.139.129.5  208.59 ms  AS56040  China, Guangdong, Guangzhou, ChinaMobile


Traceroute to China, Shanghai CU AS9929 (TCP Mode, Max 30 Hop)
============================================================
traceroute to 210.13.66.238 (210.13.66.238), 30 hops max, 32 byte packets
 1  10.0.2.1  1.08 ms  *  LAN Address
 2  *
 3  206.71.158.6  3.06 ms  AS396998  United States, Texas, Dallas, path.net
 4  154.54.28.73  1.64 ms  AS174  United States, Texas, Dallas, cogentco.com
 5  154.54.44.229  7.21 ms  AS174  United States, Texas, Houston, cogentco.com
 6  154.54.47.213  1.60 ms  AS174  United States, Texas, Dallas, cogentco.com
 7  154.54.44.229  6.78 ms  AS174  United States, Texas, Houston, cogentco.com
 8  154.54.29.222  22.45 ms  AS174  cogentco.com
 9  154.54.42.65  30.54 ms  AS174  United States, Arizona, Phoenix, cogentco.com
10  154.54.45.162  42.57 ms  AS174  United States, California, Los Angeles, cogentco.com
11  154.54.25.150  42.58 ms  AS174  United States, California, Los Angeles, cogentco.com
12  38.142.239.114  195.94 ms  AS174  China, Guangdong, Guangzhou, cogentco.com
13  210.14.186.141  191.51 ms  *  China, ChinaUnicom
14  218.105.2.210  191.67 ms  AS9929  China, Shanghai, ChinaUnicom
15  210.13.116.86  195.11 ms  AS9929  China, Shanghai, ChinaUnicom
16  *
17  210.13.64.110  194.99 ms  AS9929  China, Shanghai, ChinaUnicom
18  210.13.66.237  196.29 ms  AS9929  China, Shanghai, ChinaUnicom
19  210.13.66.238  197.91 ms  AS9929  China, Shanghai, ChinaUnicom


Traceroute to China, Shanghai CT CN2 (TCP Mode, Max 30 Hop)
============================================================
traceroute to 58.32.0.1 (58.32.0.1), 30 hops max, 32 byte packets
 1  10.0.2.1  1.33 ms  *  LAN Address
 2  *
 3  206.71.158.6  20.41 ms  AS396998  United States, Texas, Dallas, path.net
 4  129.250.4.154  44.69 ms  AS2914  United States, California, San Jose, ntt.com
 5  129.250.5.77  141.34 ms  AS2914  Japan, Tokyo, ntt.com
 6  129.250.4.154  39.64 ms  AS2914  United States, California, San Jose, ntt.com
 7  129.250.5.77  145.89 ms  AS2914  Japan, Tokyo, ntt.com
 8  129.250.7.54  146.34 ms  AS2914  ntt.com
 9  129.250.2.59  147.11 ms  AS2914  Japan, Tokyo, ntt.com
10  120.88.54.134  188.77 ms  AS2914  Japan, Tokyo, ntt.com
11  *
12  59.43.130.213  197.69 ms  *  China, Shanghai, ChinaTelecom
13  101.95.88.42  181.19 ms  AS4812  China, Shanghai, ChinaTelecom
14  101.95.88.42  202.56 ms  AS4812  China, Shanghai, ChinaTelecom
15  *
16  58.32.0.1  206.87 ms  AS4812  China, Shanghai, ChinaTelecom


Traceroute to China, Guangzhou CT CN2 Gaming Broadband (TCP Mode, Max 30 Hop)
============================================================
traceroute to 119.121.0.1 (119.121.0.1), 30 hops max, 32 byte packets
 1  10.0.2.1  1.42 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  19.91 ms  http: 403  http: 403
 4  129.250.4.154  40.54 ms  http: 403  http: 403
 5  129.250.5.77  149.68 ms  http: 403  http: 403
 6  129.250.4.154  45.79 ms  http: 403  http: 403
 7  129.250.5.77  142.60 ms  http: 403  http: 403
 8  129.250.7.54  175.41 ms  http: 403  http: 403
 9  129.250.2.69  147.22 ms  http: 403  http: 403
10  59.43.186.185  195.94 ms  http: 403  http: 403
11  59.43.187.69  204.05 ms  http: 403  http: 403
12  *
13  59.43.17.205  202.37 ms  http: 403  http: 403
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *


Traceroute to China, Beijing Dr.Peng Home Network (TCP Mode, Max 30 Hop)
============================================================
traceroute to 14.131.128.1 (14.131.128.1), 30 hops max, 32 byte packets
 1  10.0.2.1  1.28 ms  http: 403  http: 403
 2  *
 3  *
 4  *
 5  *
 6  *
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *


Traceroute to China, Beijing Dr.Peng Network IDC Network (TCP Mode, Max 30 Hop)
============================================================
traceroute to 211.167.230.100 (211.167.230.100), 30 hops max, 32 byte packets
 1  10.0.2.1  1.15 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  19.46 ms  http: 403  http: 403
 4  173.205.56.182  256.22 ms  http: 403  http: 403
 5  219.158.98.153  246.55 ms  http: 403  http: 403
 6  199.229.231.214  257.35 ms  http: 403  http: 403
 7  219.158.98.153  241.76 ms  http: 403  http: 403
 8  219.158.115.157  275.26 ms  http: 403  http: 403
 9  219.158.9.214  288.21 ms  http: 403  http: 403
10  *
11  125.33.186.150  289.55 ms  http: 403  http: 403
12  202.96.13.186  281.21 ms  http: 403  http: 403
13  61.149.212.242  280.82 ms  http: 403  http: 403
14  202.99.1.234  280.85 ms  http: 403  http: 403
15  124.205.97.138  275.73 ms  http: 403  http: 403
16  218.241.255.178  285.30 ms  http: 403  http: 403
17  218.241.245.158  274.56 ms  http: 403  http: 403
18  *
19  211.167.230.100  274.66 ms  http: 403  http: 403


Traceroute to China, Beijing CERNET (TCP Mode, Max 30 Hop)
============================================================
traceroute to 202.205.109.205 (202.205.109.205), 30 hops max, 32 byte packets
 1  10.0.2.1  1.22 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  0.75 ms  http: 403  http: 403
 4  129.250.4.154  44.43 ms  http: 403  http: 403
 5  129.250.5.77  149.98 ms  http: 403  http: 403
 6  129.250.4.154  46.32 ms  http: 403  http: 403
 7  129.250.5.77  145.95 ms  http: 403  http: 403
 8  129.250.2.51  252.68 ms  http: 403  http: 403
 9  129.250.6.123  250.47 ms  http: 403  http: 403
10  203.131.254.214  249.84 ms  http: 403  http: 403
11  101.4.114.181  276.65 ms  http: 403  http: 403
12  *
13  *
14  *
15  101.4.113.110  279.45 ms  http: 403  http: 403
16  219.224.102.230  279.77 ms  http: 403  http: 403
17  *
18  202.205.109.205  279.54 ms  http: 403  http: 403


Traceroute to China, Beijing CSTNET (TCP Mode, Max 30 Hop)
============================================================
traceroute to 159.226.254.1 (159.226.254.1), 30 hops max, 32 byte packets
 1  10.0.2.1  1.14 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  15.59 ms  http: 403  http: 403
 4  63.223.17.94  187.63 ms  http: 403  http: 403
 5  63.217.16.34  187.90 ms  http: 403  http: 403
 6  63.223.17.94  187.60 ms  http: 403  http: 403
 7  63.217.16.34  185.99 ms  http: 403  http: 403
 8  159.226.254.9  223.66 ms  http: 403  http: 403
 9  159.226.254.49  228.46 ms  http: 403  http: 403
10  159.226.254.1  221.42 ms  http: 403  http: 403


Traceroute to China, Beijing GCable (TCP Mode, Max 30 Hop)
============================================================
traceroute to 211.156.140.17 (211.156.140.17), 30 hops max, 32 byte packets
 1  10.0.2.1  1.12 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  25.40 ms  http: 403  http: 403
 4  129.250.7.69  29.00 ms  http: 403  http: 403
 5  129.250.2.104  33.02 ms  http: 403  http: 403
 6  129.250.7.69  29.52 ms  http: 403  http: 403
 7  129.250.2.104  32.22 ms  http: 403  http: 403
 8  218.30.53.108  34.36 ms  http: 403  http: 403
 9  202.97.59.133  186.13 ms  http: 403  http: 403
10  202.97.85.41  186.85 ms  http: 403  http: 403
11  *
12  *
13  *
14  106.120.252.158  201.60 ms  http: 403  http: 403
15  *
16  211.156.131.93  213.23 ms  http: 403  http: 403
17  211.156.140.17  204.95 ms  http: 403  http: 403


Traceroute to China, Hongkong CU (TCP Mode, Max 30 Hop)
============================================================
traceroute to 203.160.95.218 (203.160.95.218), 30 hops max, 32 byte packets
 1  10.0.2.1  1.10 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  0.76 ms  http: 403  http: 403
 4  129.250.4.154  39.26 ms  http: 403  http: 403
 5  129.250.5.77  148.96 ms  http: 403  http: 403
 6  129.250.4.154  39.64 ms  http: 403  http: 403
 7  129.250.5.77  144.31 ms  http: 403  http: 403
 8  *
 9  *
10  *
11  43.252.86.65  263.70 ms  http: 403  http: 403
12  119.252.139.14  248.86 ms  http: 403  http: 403
13  202.77.22.89  251.52 ms  http: 403  http: 403
14  203.160.95.218  248.51 ms  http: 403  http: 403


Traceroute to China, Hongkong CT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 203.215.232.173 (203.215.232.173), 30 hops max, 32 byte packets
 1  10.0.2.1  1.27 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  15.68 ms  http: 403  http: 403
 4  218.30.54.72  32.97 ms  http: 403  http: 403
 5  *
 6  218.30.54.72  31.41 ms  http: 403  http: 403
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *


Traceroute to China, Hongkong CT CN2 (TCP Mode, Max 30 Hop)
============================================================
traceroute to 203.8.25.187 (203.8.25.187), 30 hops max, 32 byte packets
 1  10.0.2.1  1.14 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  19.42 ms  http: 403  http: 403
 4  129.250.4.154  43.07 ms  http: 403  http: 403
 5  129.250.5.77  148.50 ms  http: 403  http: 403
 6  129.250.4.154  40.49 ms  http: 403  http: 403
 7  129.250.5.77  148.99 ms  http: 403  http: 403
 8  129.250.7.54  169.90 ms  http: 403  http: 403
 9  129.250.2.69  156.91 ms  http: 403  http: 403
10  59.43.184.197  191.71 ms  http: 403  http: 403
11  59.43.248.146  190.55 ms  http: 403  http: 403
12  203.8.25.187  191.47 ms  http: 403  http: 403


Traceroute to China, Hongkong CM (TCP Mode, Max 30 Hop)
============================================================
traceroute to 203.142.105.9 (203.142.105.9), 30 hops max, 32 byte packets
 1  10.0.2.1  1.03 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  14.52 ms  http: 403  http: 403
 4  129.250.4.154  43.29 ms  http: 403  http: 403
 5  129.250.5.77  152.28 ms  http: 403  http: 403
 6  129.250.4.154  44.20 ms  http: 403  http: 403
 7  129.250.5.77  144.62 ms  http: 403  http: 403
 8  129.250.2.51  250.78 ms  http: 403  http: 403
 9  129.250.6.123  258.68 ms  http: 403  http: 403
10  203.131.254.2  289.76 ms  http: 403  http: 403
11  223.120.2.117  278.18 ms  http: 403  http: 403
12  223.120.3.90  275.85 ms  http: 403  http: 403
13  *
14  *
15  203.142.126.10  272.60 ms  http: 403  http: 403
16  *
17  *
18  203.142.105.9  275.25 ms  http: 403  http: 403


Traceroute to China, Hongkong HGC (TCP Mode, Max 30 Hop)
============================================================
traceroute to 218.188.104.30 (218.188.104.30), 30 hops max, 32 byte packets
 1  10.0.2.1  1.20 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  20.41 ms  http: 403  http: 403
 4  154.54.28.73  2.03 ms  http: 403  http: 403
 5  154.54.44.229  6.85 ms  http: 403  http: 403
 6  154.54.28.73  1.73 ms  http: 403  http: 403
 7  154.54.44.229  7.05 ms  http: 403  http: 403
 8  154.54.29.222  22.56 ms  http: 403  http: 403
 9  154.54.42.65  30.68 ms  http: 403  http: 403
10  154.54.44.86  42.16 ms  http: 403  http: 403
11  154.54.3.70  42.46 ms  http: 403  http: 403
12  38.19.141.26  207.65 ms  http: 403  http: 403
13  203.78.181.201  197.85 ms  http: 403  http: 403
14  203.78.181.194  191.55 ms  http: 403  http: 403
15  175.41.58.226  284.50 ms  http: 403  http: 403
16  *
17  218.189.5.24  285.49 ms  http: 403  http: 403
18  218.188.104.30  291.26 ms  http: 403  http: 403


Traceroute to China, Hongkong HKBN (TCP Mode, Max 30 Hop)
============================================================
traceroute to 210.6.23.239 (210.6.23.239), 30 hops max, 32 byte packets
 1  10.0.2.1  1.16 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  1.09 ms  http: 403  http: 403
 4  154.54.28.73  1.30 ms  http: 403  http: 403
 5  154.54.41.65  6.73 ms  http: 403  http: 403
 6  154.54.28.73  1.41 ms  http: 403  http: 403
 7  154.54.41.65  6.53 ms  http: 403  http: 403
 8  154.54.29.222  22.57 ms  http: 403  http: 403
 9  154.54.42.65  30.86 ms  http: 403  http: 403
10  154.54.44.86  42.05 ms  http: 403  http: 403
11  154.54.0.6  190.53 ms  http: 403  http: 403
12  154.18.8.154  192.29 ms  http: 403  http: 403
13  61.244.225.102  191.88 ms  http: 403  http: 403
14  203.186.235.137  194.22 ms  http: 403  http: 403
15  *
16  210.6.23.239  191.82 ms  http: 403  http: 403


Traceroute to China, Hongkong PCCW (TCP Mode, Max 30 Hop)
============================================================
traceroute to 202.85.125.60 (202.85.125.60), 30 hops max, 32 byte packets
 1  10.0.2.1  1.07 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  25.29 ms  http: 403  http: 403
 4  63.223.20.45  192.11 ms  http: 403  http: 403
 5  63.222.45.38  195.74 ms  http: 403  http: 403
 6  63.222.45.38  192.19 ms  http: 403  http: 403
 7  63.222.45.38  195.72 ms  http: 403  http: 403
 8  202.153.103.69  193.78 ms  http: 403  http: 403
 9  202.153.99.203  193.92 ms  http: 403  http: 403
10  202.85.125.60  190.45 ms  http: 403  http: 403


Traceroute to China, Hongkong TGT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 202.123.76.239 (202.123.76.239), 30 hops max, 32 byte packets
 1  10.0.2.1  1.28 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  2.59 ms  http: 403  http: 403
 4  129.250.4.154  40.35 ms  http: 403  http: 403
 5  129.250.5.77  149.29 ms  http: 403  http: 403
 6  129.250.4.154  43.75 ms  http: 403  http: 403
 7  129.250.5.77  142.38 ms  http: 403  http: 403
 8  *
 9  129.250.6.115  253.01 ms  http: 403  http: 403
10  203.131.254.14  252.55 ms  http: 403  http: 403
11  203.78.72.100  251.91 ms  http: 403  http: 403
12  203.78.73.75  251.70 ms  http: 403  http: 403
13  *
14  202.123.76.239  249.27 ms  http: 403  http: 403


Traceroute to China, Hongkong WTT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 59.152.252.242 (59.152.252.242), 30 hops max, 32 byte packets
 1  10.0.2.1  1.21 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  0.70 ms  http: 403  http: 403
 4  129.250.4.154  40.02 ms  http: 403  http: 403
 5  129.250.5.77  146.37 ms  http: 403  http: 403
 6  *
 7  129.250.5.77  150.17 ms  http: 403  http: 403
 8  *
 9  129.250.6.178  241.84 ms  http: 403  http: 403
10  203.131.246.154  298.81 ms  http: 403  http: 403
11  *
12  *
13  59.152.252.196  295.74 ms  http: 403  http: 403
14  59.152.252.242  290.15 ms  http: 403  http: 403


Traceroute to Singapore, China CT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 203.215.233.1 (203.215.233.1), 30 hops max, 32 byte packets
 1  10.0.2.1  1.28 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  19.84 ms  http: 403  http: 403
 4  129.250.2.218  34.49 ms  http: 403  http: 403
 5  129.250.3.208  34.12 ms  http: 403  http: 403
 6  129.250.2.218  30.09 ms  http: 403  http: 403
 7  129.250.3.208  42.62 ms  http: 403  http: 403
 8  218.30.53.129  32.36 ms  http: 403  http: 403
 9  202.97.49.226  54.37 ms  http: 403  http: 403
10  202.97.71.41  126.91 ms  http: 403  http: 403
11  202.97.65.133  292.60 ms  http: 403  http: 403
12  203.215.233.1  301.36 ms  http: 403  http: 403


Traceroute to Singapore, China CT CN2 (TCP Mode, Max 30 Hop)
============================================================
traceroute to 183.91.61.1 (183.91.61.1), 30 hops max, 32 byte packets
 1  10.0.2.1  1.24 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  19.90 ms  http: 403  http: 403
 4  129.250.4.154  43.34 ms  http: 403  http: 403
 5  129.250.5.77  144.59 ms  http: 403  http: 403
 6  *
 7  129.250.5.77  145.85 ms  http: 403  http: 403
 8  129.250.7.54  146.38 ms  http: 403  http: 403
 9  117.103.177.106  190.78 ms  http: 403  http: 403
10  59.43.247.237  224.59 ms  http: 403  http: 403
11  183.91.61.1  229.29 ms  http: 403  http: 403


Traceroute to Singapore, Singtel (TCP Mode, Max 30 Hop)
============================================================
traceroute to 118.201.1.11 (118.201.1.11), 30 hops max, 32 byte packets
 1  10.0.2.1  1.15 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  19.93 ms  http: 403  http: 403
 4  129.250.4.18  2.18 ms  http: 403  http: 403
 5  *
 6  129.250.4.8  5.61 ms  http: 403  http: 403
 7  *
 8  64.125.26.204  35.53 ms  http: 403  http: 403
 9  64.125.26.183  29.83 ms  http: 403  http: 403
10  *
11  64.125.35.202  30.59 ms  http: 403  http: 403
12  203.208.173.81  202.96 ms  http: 403  http: 403
13  203.208.182.254  201.40 ms  http: 403  http: 403
14  203.208.182.253  189.50 ms  http: 403  http: 403
15  203.208.153.246  223.14 ms  http: 403  http: 403
16  203.208.182.254  204.81 ms  http: 403  http: 403
17  165.21.138.70  203.61 ms  http: 403  http: 403
18  165.21.138.86  211.61 ms  http: 403  http: 403
19  165.21.138.82  205.67 ms  http: 403  http: 403
20  165.21.138.66  210.10 ms  http: 403  http: 403
21  165.21.49.126  190.27 ms  http: 403  http: 403
22  203.125.232.130  199.12 ms  http: 403  http: 403
23  118.201.1.11  203.01 ms  http: 403  http: 403


Traceroute to Singapore, StarHub (TCP Mode, Max 30 Hop)
============================================================
traceroute to 203.116.46.33 (203.116.46.33), 30 hops max, 32 byte packets
 1  10.0.2.1  1.14 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  24.58 ms  http: 403  http: 403
 4  129.250.7.69  33.44 ms  http: 403  http: 403
 5  129.250.3.219  32.29 ms  http: 403  http: 403
 6  129.250.4.154  43.56 ms  http: 403  http: 403
 7  *
 8  129.250.5.22  139.16 ms  http: 403  http: 403
 9  129.250.2.242  197.06 ms  http: 403  http: 403
10  129.250.4.134  208.52 ms  http: 403  http: 403
11  116.51.18.138  247.65 ms  http: 403  http: 403
12  203.117.164.209  235.51 ms  http: 403  http: 403
13  61.8.243.1  235.56 ms  http: 403  http: 403
14  *
15  203.116.46.33  244.27 ms  http: 403  http: 403


Traceroute to Singapore, M1 (TCP Mode, Max 30 Hop)
============================================================
traceroute to 118.189.184.1 (118.189.184.1), 30 hops max, 32 byte packets
 1  10.0.2.1  1.35 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  1.10 ms  http: 403  http: 403
 4  63.223.34.142  212.78 ms  http: 403  http: 403
 5  63.217.59.46  250.30 ms  http: 403  http: 403
 6  63.223.34.142  216.81 ms  http: 403  http: 403
 7  63.217.59.46  250.26 ms  http: 403  http: 403
 8  202.65.246.137  252.59 ms  http: 403  http: 403
 9  202.65.246.186  251.17 ms  http: 403  http: 403
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *


Traceroute to Singapore, M1 GamePro (TCP Mode, Max 30 Hop)
============================================================
traceroute to 118.189.38.17 (118.189.38.17), 30 hops max, 32 byte packets
 1  10.0.2.1  1.10 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  19.97 ms  http: 403  http: 403
 4  63.223.58.70  217.99 ms  http: 403  http: 403
 5  63.218.249.254  222.13 ms  http: 403  http: 403
 6  63.223.58.70  218.10 ms  http: 403  http: 403
 7  63.218.249.254  218.22 ms  http: 403  http: 403
 8  203.211.158.72  215.50 ms  http: 403  http: 403
 9  203.211.159.149  210.96 ms  http: 403  http: 403
10  129.126.64.122  224.24 ms  http: 403  http: 403
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *


Traceroute to Singapore, AWS (TCP Mode, Max 30 Hop)
============================================================
traceroute to 13.228.0.251 (13.228.0.251), 30 hops max, 32 byte packets
 1  10.0.2.1  3.41 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  19.97 ms  http: 403  http: 403
 4  129.250.4.154  44.60 ms  http: 403  http: 403
 5  129.250.5.77  145.14 ms  http: 403  http: 403
 6  129.250.7.69  28.29 ms  http: 403  http: 403
 7  129.250.2.177  139.30 ms  http: 403  http: 403
 8  129.250.6.131  147.24 ms  http: 403  http: 403
 9  61.200.80.86  133.89 ms  http: 403  http: 403
10  150.222.77.231  145.27 ms  http: 403  http: 403
11  *
12  54.239.52.95  154.41 ms  http: 403  http: 403
13  15.230.152.87  146.01 ms  http: 403  http: 403
14  *
15  52.93.8.110  208.64 ms  http: 403  http: 403
16  52.93.11.51  217.94 ms  http: 403  http: 403
17  52.93.11.80  222.30 ms  http: 403  http: 403
18  52.93.11.77  225.08 ms  http: 403  http: 403
19  52.93.11.38  211.34 ms  http: 403  http: 403
20  *
21  *
22  150.222.108.155  216.22 ms  http: 403  http: 403
23  *
24  *
25  *
26  13.228.0.251  214.80 ms  http: 403  http: 403


Traceroute to Japan, NTT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 61.213.155.84 (61.213.155.84), 30 hops max, 32 byte packets
 1  10.0.2.1  1.25 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  10.59 ms  http: 403  http: 403
 4  129.250.4.154  43.99 ms  http: 403  http: 403
 5  *
 6  129.250.4.154  38.92 ms  http: 403  http: 403
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *


Traceroute to Japan, IIJ (TCP Mode, Max 30 Hop)
============================================================
traceroute to 202.232.15.70 (202.232.15.70), 30 hops max, 32 byte packets
 1  10.0.2.1  1.25 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  19.90 ms  http: 403  http: 403
 4  173.241.128.62  38.24 ms  http: 403  http: 403
 5  58.138.88.89  139.85 ms  http: 403  http: 403
 6  173.241.128.62  38.20 ms  http: 403  http: 403
 7  58.138.88.93  159.66 ms  http: 403  http: 403
 8  58.138.101.10  138.80 ms  http: 403  http: 403
 9  210.130.142.114  138.73 ms  http: 403  http: 403
10  202.232.15.70  137.80 ms  http: 403  http: 403


Traceroute to Japan, SoftBank (TCP Mode, Max 30 Hop)
============================================================
traceroute to 210.175.32.26 (210.175.32.26), 30 hops max, 32 byte packets
 1  10.0.2.1  1.25 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  19.27 ms  http: 403  http: 403
 4  129.250.4.154  39.79 ms  http: 403  http: 403
 5  129.250.5.77  145.23 ms  http: 403  http: 403
 6  129.250.4.154  40.31 ms  http: 403  http: 403
 7  129.250.5.77  145.55 ms  http: 403  http: 403
 8  129.250.6.131  150.69 ms  http: 403  http: 403
 9  203.105.72.62  142.00 ms  http: 403  http: 403
10  *
11  *
12  *
13  143.90.232.241  150.29 ms  http: 403  http: 403
14  143.90.47.33  145.67 ms  http: 403  http: 403
15  143.90.161.82  142.61 ms  http: 403  http: 403
16  143.90.54.30  149.71 ms  http: 403  http: 403
17  210.175.32.123  145.98 ms  http: 403  http: 403
18  210.175.32.26  146.91 ms  http: 403  http: 403


Traceroute to Japan, KDDI (TCP Mode, Max 30 Hop)
============================================================
traceroute to 106.162.242.108 (106.162.242.108), 30 hops max, 32 byte packets
 1  10.0.2.1  1.43 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  0.94 ms  http: 403  http: 403
 4  208.116.133.198  34.32 ms  http: 403  http: 403
 5  203.181.106.189  30.90 ms  http: 403  http: 403
 6  208.116.133.198  34.28 ms  http: 403  http: 403
 7  203.181.106.185  30.60 ms  http: 403  http: 403
 8  106.187.12.41  140.58 ms  http: 403  http: 403
 9  27.85.131.22  140.58 ms  http: 403  http: 403
10  111.87.220.242  137.12 ms  http: 403  http: 403
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *


Traceroute to Japan, China CT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 203.215.236.3 (203.215.236.3), 30 hops max, 32 byte packets
 1  10.0.2.1  1.27 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  16.99 ms  http: 403  http: 403
 4  63.223.46.26  40.15 ms  http: 403  http: 403
 5  218.30.54.96  40.06 ms  http: 403  http: 403
 6  63.223.46.26  41.74 ms  http: 403  http: 403
 7  218.30.54.96  43.08 ms  http: 403  http: 403
 8  202.97.63.93  74.03 ms  http: 403  http: 403
 9  202.97.39.230  68.79 ms  http: 403  http: 403
10  202.97.6.89  181.44 ms  http: 403  http: 403
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *


Traceroute to Japan, China CT CN2 (TCP Mode, Max 30 Hop)
============================================================
traceroute to 202.55.27.4 (202.55.27.4), 30 hops max, 32 byte packets
 1  10.0.2.1  1.47 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  19.02 ms  http: 403  http: 403
 4  129.250.4.154  39.62 ms  http: 403  http: 403
 5  129.250.5.77  148.92 ms  http: 403  http: 403
 6  129.250.4.154  43.74 ms  http: 403  http: 403
 7  129.250.5.77  149.18 ms  http: 403  http: 403
 8  129.250.7.54  145.87 ms  http: 403  http: 403
 9  129.250.2.69  146.21 ms  http: 403  http: 403
10  120.88.54.134  187.83 ms  http: 403  http: 403
11  202.55.27.4  190.55 ms  http: 403  http: 403


Traceroute to Japan, Amazon AWS (TCP Mode, Max 30 Hop)
============================================================
traceroute to 13.112.63.251 (13.112.63.251), 30 hops max, 32 byte packets
 1  10.0.2.1  1.23 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  25.35 ms  http: 403  http: 403
 4  63.223.17.94  185.05 ms  http: 403  http: 403
 5  63.217.17.42  190.88 ms  http: 403  http: 403
 6  63.223.17.94  187.43 ms  http: 403  http: 403
 7  63.217.17.42  184.91 ms  http: 403  http: 403
 8  52.93.35.84  190.62 ms  http: 403  http: 403
 9  52.93.35.99  187.52 ms  http: 403  http: 403
10  *
11  *
12  *
13  *
14  *
15  52.93.129.99  185.12 ms  http: 403  http: 403
16  150.222.253.186  185.81 ms  http: 403  http: 403
17  *
18  *
19  *
20  52.95.31.214  190.51 ms  http: 403  http: 403
21  15.230.154.39  190.23 ms  http: 403  http: 403
22  52.93.250.26  193.13 ms  http: 403  http: 403
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  13.112.63.251  186.55 ms  http: 403  http: 403


Traceroute to South Korea, KT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 210.114.41.101 (210.114.41.101), 30 hops max, 32 byte packets
 1  10.0.2.1  1.13 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  2.42 ms  http: 403  http: 403
 4  76.74.48.138  31.08 ms  http: 403  http: 403
 5  *
 6  76.74.48.138  39.56 ms  http: 403  http: 403
 7  *
 8  112.190.31.25  191.10 ms  http: 403  http: 403
 9  *
10  112.174.21.54  168.76 ms  http: 403  http: 403
11  *
12  220.90.203.10  168.17 ms  http: 403  http: 403
13  211.37.130.73  174.07 ms  http: 403  http: 403
14  211.37.137.22  175.49 ms  http: 403  http: 403
15  210.114.41.101  168.73 ms  http: 403  http: 403


Traceroute to South Korea, SK (TCP Mode, Max 30 Hop)
============================================================
traceroute to 175.122.253.62 (175.122.253.62), 30 hops max, 32 byte packets
 1  10.0.2.1  1.15 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  19.78 ms  http: 403  http: 403
 4  63.223.43.202  31.12 ms  http: 403  http: 403
 5  63.218.73.34  30.70 ms  http: 403  http: 403
 6  63.223.43.202  31.03 ms  http: 403  http: 403
 7  63.218.73.34  31.48 ms  http: 403  http: 403
 8  58.229.4.170  165.50 ms  http: 403  http: 403
 9  1.255.74.66  166.39 ms  http: 403  http: 403
10  *
11  *
12  175.122.253.62  172.43 ms  http: 403  http: 403


Traceroute to South Korea, LG (TCP Mode, Max 30 Hop)
============================================================
traceroute to 211.174.62.44 (211.174.62.44), 30 hops max, 32 byte packets
 1  10.0.2.1  1.02 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  3.44 ms  http: 403  http: 403
 4  63.218.50.97  30.98 ms  http: 403  http: 403
 5  63.218.51.142  30.80 ms  http: 403  http: 403
 6  63.218.50.97  31.04 ms  http: 403  http: 403
 7  63.218.51.142  30.95 ms  http: 403  http: 403
 8  1.208.112.21  30.90 ms  http: 403  http: 403
 9  1.208.147.161  173.04 ms  http: 403  http: 403
10  1.208.148.2  173.26 ms  http: 403  http: 403
11  *
12  1.208.145.238  179.69 ms  http: 403  http: 403
13  61.42.202.122  167.13 ms  http: 403  http: 403
14  *
15  *
16  *
17  211.174.62.44  166.30 ms  http: 403  http: 403


Traceroute to South Korea, China CT CN2 (TCP Mode, Max 30 Hop)
============================================================
traceroute to 218.185.246.3 (218.185.246.3), 30 hops max, 32 byte packets
 1  10.0.2.1  1.09 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  14.80 ms  http: 403  http: 403
 4  129.250.4.154  39.63 ms  http: 403  http: 403
 5  129.250.5.77  145.46 ms  http: 403  http: 403
 6  129.250.4.154  39.61 ms  http: 403  http: 403
 7  129.250.5.77  145.40 ms  http: 403  http: 403
 8  129.250.7.54  149.22 ms  http: 403  http: 403
 9  117.103.177.106  187.78 ms  http: 403  http: 403
10  120.88.54.134  192.05 ms  http: 403  http: 403
11  59.43.183.1  222.29 ms  http: 403  http: 403
12  59.43.187.210  246.85 ms  http: 403  http: 403
13  59.43.181.165  228.36 ms  http: 403  http: 403
14  218.185.246.3  230.31 ms  http: 403  http: 403


Traceroute to South Korea, Amazon AWS (TCP Mode, Max 30 Hop)
============================================================
traceroute to 13.124.63.251 (13.124.63.251), 30 hops max, 32 byte packets
 1  10.0.2.1  1.29 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  1.00 ms  http: 403  http: 403
 4  63.223.33.66  141.74 ms  http: 403  http: 403
 5  63.222.57.30  146.09 ms  http: 403  http: 403
 6  63.223.33.98  142.13 ms  http: 403  http: 403
 7  63.222.57.30  156.49 ms  http: 403  http: 403
 8  52.93.251.179  138.07 ms  http: 403  http: 403
 9  *
10  52.93.251.73  147.19 ms  http: 403  http: 403
11  52.93.66.131  146.31 ms  http: 403  http: 403
12  *
13  54.239.122.80  179.74 ms  http: 403  http: 403
14  52.93.248.184  171.81 ms  http: 403  http: 403
15  52.93.248.171  172.43 ms  http: 403  http: 403
16  54.239.122.221  177.41 ms  http: 403  http: 403
17  52.93.247.8  169.00 ms  http: 403  http: 403
18  *
19  *
20  *
21  *
22  *
23  *
24  13.124.63.251  175.06 ms  http: 403  http: 403


Traceroute to China, Taiwan Chief (TCP Mode, Max 30 Hop)
============================================================
traceroute to 202.133.242.116 (202.133.242.116), 30 hops max, 32 byte packets
 1  10.0.2.1  1.12 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  1.85 ms  http: 403  http: 403
 4  154.54.12.121  1.49 ms  http: 403  http: 403
 5  154.54.28.73  1.52 ms  http: 403  http: 403
 6  *
 7  154.54.47.213  1.71 ms  http: 403  http: 403
 8  154.54.44.229  6.78 ms  http: 403  http: 403
 9  154.54.29.222  22.49 ms  http: 403  http: 403
10  154.54.42.77  30.62 ms  http: 403  http: 403
11  154.54.44.86  43.58 ms  http: 403  http: 403
12  154.54.25.150  42.75 ms  http: 403  http: 403
13  154.54.1.22  140.40 ms  http: 403  http: 403
14  66.28.4.234  170.40 ms  http: 403  http: 403
15  154.18.24.66  170.42 ms  http: 403  http: 403
16  103.123.252.13  172.26 ms  http: 403  http: 403
17  113.21.95.72  172.59 ms  http: 403  http: 403
18  103.123.254.38  173.54 ms  http: 403  http: 403
19  202.133.242.114  174.74 ms  http: 403  http: 403
20  202.133.242.116  172.92 ms  http: 403  http: 403


Traceroute to China, Taiwan APTG (TCP Mode, Max 30 Hop)
============================================================
traceroute to 210.200.69.90 (210.200.69.90), 30 hops max, 32 byte packets
 1  10.0.2.1  1.12 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  4.29 ms  http: 403  http: 403
 4  63.223.60.58  37.40 ms  http: 403  http: 403
 5  134.159.61.77  37.96 ms  http: 403  http: 403
 6  63.223.60.58  37.64 ms  http: 403  http: 403
 7  134.159.61.77  37.83 ms  http: 403  http: 403
 8  202.84.247.18  38.59 ms  http: 403  http: 403
 9  202.84.247.18  142.68 ms  http: 403  http: 403
10  202.84.141.2  176.47 ms  http: 403  http: 403
11  202.84.143.6  178.33 ms  http: 403  http: 403
12  202.84.140.202  176.25 ms  http: 403  http: 403
13  202.84.137.250  181.24 ms  http: 403  http: 403
14  211.76.96.76  176.11 ms  http: 403  http: 403
15  211.76.100.53  176.18 ms  http: 403  http: 403
16  210.200.80.254  176.12 ms  http: 403  http: 403
17  210.200.80.254  178.35 ms  http: 403  http: 403
18  210.200.80.254  176.80 ms  http: 403  http: 403
19  210.200.69.90  175.75 ms  http: 403  http: 403


Traceroute to China, Taiwan CHT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 203.75.129.162 (203.75.129.162), 30 hops max, 32 byte packets
 1  10.0.2.1  1.19 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  7.99 ms  http: 403  http: 403
 4  63.218.50.97  31.92 ms  http: 403  http: 403
 5  202.39.82.226  30.73 ms  http: 403  http: 403
 6  63.218.50.97  31.05 ms  http: 403  http: 403
 7  202.39.82.226  30.87 ms  http: 403  http: 403
 8  202.39.84.86  30.99 ms  http: 403  http: 403
 9  202.39.91.66  208.00 ms  http: 403  http: 403
10  220.128.6.38  209.27 ms  http: 403  http: 403
11  *
12  220.128.27.106  166.34 ms  http: 403  http: 403
13  220.128.4.17  165.81 ms  http: 403  http: 403
14  211.22.229.45  166.23 ms  http: 403  http: 403
15  1.1.1.2  167.41 ms  http: 403  http: 403
16  *
17  *
18  203.75.129.162  166.37 ms  http: 403  http: 403


Traceroute to China, Taiwan TFN (TCP Mode, Max 30 Hop)
============================================================
traceroute to 219.87.66.3 (219.87.66.3), 30 hops max, 32 byte packets
 1  10.0.2.1  1.23 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  12.94 ms  http: 403  http: 403
 4  129.250.4.154  47.72 ms  http: 403  http: 403
 5  129.250.5.77  145.13 ms  http: 403  http: 403
 6  129.250.4.154  39.05 ms  http: 403  http: 403
 7  129.250.5.77  145.38 ms  http: 403  http: 403
 8  129.250.3.192  140.69 ms  http: 403  http: 403
 9  129.250.7.6  170.15 ms  http: 403  http: 403
10  129.250.7.41  169.89 ms  http: 403  http: 403
11  61.58.33.222  164.16 ms  http: 403  http: 403
12  60.199.14.242  175.06 ms  http: 403  http: 403
13  60.199.28.6  184.85 ms  http: 403  http: 403
14  *
15  219.87.66.3  178.48 ms  http: 403  http: 403


Traceroute to China,Taiwan FET (TCP Mode, Max 30 Hop)
============================================================
traceroute to 211.73.144.38 (211.73.144.38), 30 hops max, 32 byte packets
 1  10.0.2.1  1.39 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  19.89 ms  http: 403  http: 403
 4  129.250.4.154  41.93 ms  http: 403  http: 403
 5  129.250.5.77  141.74 ms  http: 403  http: 403
 6  129.250.4.154  45.47 ms  http: 403  http: 403
 7  129.250.3.219  29.34 ms  http: 403  http: 403
 8  129.250.3.192  130.93 ms  http: 403  http: 403
 9  129.250.7.6  167.03 ms  http: 403  http: 403
10  129.250.6.18  160.85 ms  http: 403  http: 403
11  199.245.24.37  234.31 ms  http: 403  http: 403
12  192.72.155.33  178.20 ms  http: 403  http: 403
13  139.175.59.222  166.60 ms  http: 403  http: 403
14  *
15  *
16  *
17  211.73.144.38  177.67 ms  http: 403  http: 403


Traceroute to China, Taiwan KBT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 61.63.0.102 (61.63.0.102), 30 hops max, 32 byte packets
 1  10.0.2.1  1.50 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  23.83 ms  http: 403  http: 403
 4  62.115.125.193  31.77 ms  http: 403  http: 403
 5  62.115.125.193  32.30 ms  http: 403  http: 403
 6  62.115.125.193  31.48 ms  http: 403  http: 403
 7  62.115.125.193  31.77 ms  http: 403  http: 403
 8  62.115.175.219  191.86 ms  http: 403  http: 403
 9  203.78.181.145  195.60 ms  http: 403  http: 403
10  175.41.61.174  194.44 ms  http: 403  http: 403
11  175.41.61.166  193.71 ms  http: 403  http: 403
12  *
13  203.187.9.226  205.54 ms  http: 403  http: 403
14  58.86.1.174  181.78 ms  http: 403  http: 403
15  61.63.63.6  188.55 ms  http: 403  http: 403
16  58.86.0.206  186.43 ms  http: 403  http: 403
17  61.63.0.123  192.36 ms  http: 403  http: 403
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *


Traceroute to China, Taiwan TAIFO (TCP Mode, Max 30 Hop)
============================================================
traceroute to 103.31.196.203 (103.31.196.203), 30 hops max, 32 byte packets
 1  10.0.2.1  1.07 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  11.67 ms  http: 403  http: 403
 4  63.218.50.97  31.08 ms  http: 403  http: 403
 5  202.39.82.226  30.81 ms  http: 403  http: 403
 6  63.218.50.97  30.96 ms  http: 403  http: 403
 7  202.39.82.226  31.94 ms  http: 403  http: 403
 8  211.72.108.102  158.47 ms  http: 403  http: 403
 9  220.128.12.2  158.45 ms  http: 403  http: 403
10  220.128.14.98  166.00 ms  http: 403  http: 403
11  220.128.2.69  166.08 ms  http: 403  http: 403
12  210.242.214.5  166.36 ms  http: 403  http: 403
13  *
14  103.31.197.66  168.51 ms  http: 403  http: 403
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *


Traceroute to United States, Los Angeles China CT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 218.30.33.17 (218.30.33.17), 30 hops max, 32 byte packets
 1  10.0.2.1  1.11 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  3.25 ms  http: 403  http: 403
 4  129.250.2.218  32.46 ms  http: 403  http: 403
 5  129.250.3.208  31.92 ms  http: 403  http: 403
 6  129.250.2.218  30.33 ms  http: 403  http: 403
 7  129.250.3.208  31.96 ms  http: 403  http: 403
 8  218.30.53.129  30.92 ms  http: 403  http: 403
 9  218.30.33.17  51.31 ms  http: 403  http: 403


Traceroute to United States, Los Angeles China CT CN2 (TCP Mode, Max 30 Hop)
============================================================
traceroute to 66.102.252.100 (66.102.252.100), 30 hops max, 32 byte packets
 1  10.0.2.1  1.26 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  20.08 ms  http: 403  http: 403
 4  *
 5  62.115.143.39  32.90 ms  http: 403  http: 403
 6  *
 7  62.115.143.39  32.01 ms  http: 403  http: 403
 8  213.248.79.253  31.97 ms  http: 403  http: 403
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *


Traceroute to United States, Los Angeles PCCW (TCP Mode, Max 30 Hop)
============================================================
traceroute to 63.218.42.81 (63.218.42.81), 30 hops max, 32 byte packets
 1  10.0.2.1  1.71 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  19.55 ms  http: 403  http: 403
 4  63.218.42.81  31.59 ms  http: 403  http: 403


Traceroute to United States, Los Angeles HE (TCP Mode, Max 30 Hop)
============================================================
traceroute to 66.220.18.42 (66.220.18.42), 30 hops max, 32 byte packets
 1  10.0.2.1  1.07 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  0.70 ms  http: 403  http: 403
 4  63.218.22.246  1.42 ms  http: 403  http: 403
 5  184.104.196.170  1.26 ms  http: 403  http: 403
 6  63.223.32.62  1.54 ms  http: 403  http: 403
 7  62.115.176.10  1.31 ms  http: 403  http: 403
 8  184.104.196.170  2.06 ms  http: 403  http: 403
 9  *
10  184.104.196.185  29.84 ms  http: 403  http: 403
11  62.115.14.42  30.40 ms  http: 403  http: 403
12  66.220.18.42  29.79 ms  http: 403  http: 403


Traceroute to United States, Los Angeles GTT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 173.205.77.98 (173.205.77.98), 30 hops max, 32 byte packets
 1  10.0.2.1  1.12 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  23.81 ms  http: 403  http: 403
 4  129.250.7.69  27.43 ms  http: 403  http: 403
 5  129.250.3.94  26.69 ms  http: 403  http: 403
 6  129.250.7.69  26.56 ms  http: 403  http: 403
 7  129.250.3.94  29.22 ms  http: 403  http: 403
 8  140.174.28.58  31.53 ms  http: 403  http: 403
 9  23.203.155.191  31.93 ms  http: 403  http: 403
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *


Traceroute to United States, San Fransico ATT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 12.169.215.33 (12.169.215.33), 30 hops max, 32 byte packets
 1  10.0.2.1  1.05 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  0.78 ms  http: 403  http: 403
 4  192.205.32.233  1.43 ms  http: 403  http: 403
 5  *
 6  192.205.32.233  1.64 ms  http: 403  http: 403
 7  *
 8  32.130.16.15  45.30 ms  http: 403  http: 403
 9  12.122.2.82  41.76 ms  http: 403  http: 403
10  12.122.28.122  39.65 ms  http: 403  http: 403
11  12.122.149.85  45.31 ms  http: 403  http: 403
12  12.244.156.30  45.53 ms  http: 403  http: 403
13  12.169.215.33  45.67 ms  http: 403  http: 403


Traceroute to United States, New York TATA (TCP Mode, Max 30 Hop)
============================================================
traceroute to 66.198.181.100 (66.198.181.100), 30 hops max, 32 byte packets
 1  10.0.2.1  1.61 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  0.80 ms  http: 403  http: 403
 4  209.120.152.154  2.04 ms  http: 403  http: 403
 5  64.86.92.21  36.74 ms  http: 403  http: 403
 6  209.120.152.154  1.43 ms  http: 403  http: 403
 7  64.86.92.21  36.65 ms  http: 403  http: 403
 8  64.86.92.23  36.72 ms  http: 403  http: 403
 9  63.243.137.133  36.81 ms  http: 403  http: 403
10  216.6.87.43  37.22 ms  http: 403  http: 403
11  64.86.62.25  36.44 ms  http: 403  http: 403
12  209.58.75.217  36.78 ms  http: 403  http: 403
13  209.58.75.198  36.57 ms  http: 403  http: 403
14  *
15  66.198.181.100  37.60 ms  http: 403  http: 403


Traceroute to United States, San Jose China CT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 218.30.33.17 (218.30.33.17), 30 hops max, 32 byte packets
 1  10.0.2.1  1.38 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  18.56 ms  http: 403  http: 403
 4  129.250.2.218  29.30 ms  http: 403  http: 403
 5  129.250.3.208  34.19 ms  http: 403  http: 403
 6  129.250.2.218  29.54 ms  http: 403  http: 403
 7  129.250.3.208  31.83 ms  http: 403  http: 403
 8  218.30.53.129  34.21 ms  http: 403  http: 403
 9  218.30.33.17  51.53 ms  http: 403  http: 403


Traceroute to United States, San Jose NTT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 23.11.26.62 (23.11.26.62), 30 hops max, 32 byte packets
 1  10.0.2.1  1.35 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  15.96 ms  http: 403  http: 403
 4  129.250.4.153  21.84 ms  http: 403  http: 403
 5  129.250.2.190  20.56 ms  http: 403  http: 403
 6  129.250.4.153  20.90 ms  http: 403  http: 403
 7  129.250.2.190  21.00 ms  http: 403  http: 403
 8  140.174.28.86  20.63 ms  http: 403  http: 403
 9  23.203.151.173  22.84 ms  http: 403  http: 403
10  *
11  *
12  *
13  23.11.26.62  21.03 ms  http: 403  http: 403


Traceroute to United States, Fremont HE (TCP Mode, Max 30 Hop)
============================================================
traceroute to 72.52.104.74 (72.52.104.74), 30 hops max, 32 byte packets
 1  10.0.2.1  1.41 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  0.72 ms  http: 403  http: 403
 4  62.115.176.10  1.44 ms  http: 403  http: 403
 5  184.105.64.221  39.81 ms  http: 403  http: 403
 6  63.218.22.246  1.69 ms  http: 403  http: 403
 7  62.115.176.10  1.28 ms  http: 403  http: 403
 8  72.52.104.74  39.87 ms  http: 403  http: 403


Traceroute to United States, Las Vegas Level3 (TCP Mode, Max 30 Hop)
============================================================
traceroute to 205.216.62.38 (205.216.62.38), 30 hops max, 32 byte packets
 1  10.0.2.1  1.34 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  23.22 ms  http: 403  http: 403
 4  4.69.206.165  1.71 ms  http: 403  http: 403
 5  4.68.110.70  1.24 ms  http: 403  http: 403
 6  4.69.206.169  1.59 ms  http: 403  http: 403
 7  4.68.110.70  1.53 ms  http: 403  http: 403
 8  67.14.54.178  2.27 ms  http: 403  http: 403
 9  216.34.172.42  2.14 ms  http: 403  http: 403
10  216.39.66.3  2.48 ms  http: 403  http: 403
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *


Traceroute to United States, San Jose ZAYO (TCP Mode, Max 30 Hop)
============================================================
traceroute to 64.125.191.31 (64.125.191.31), 30 hops max, 32 byte packets
 1  10.0.2.1  1.17 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  0.97 ms  http: 403  http: 403
 4  *
 5  *
 6  *
 7  *
 8  64.125.28.98  47.89 ms  http: 403  http: 403
 9  *
10  64.125.26.141  82.12 ms  http: 403  http: 403
11  64.125.23.119  47.80 ms  http: 403  http: 403
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *


Traceroute to United States, Ashburn Cogentco (TCP Mode, Max 30 Hop)
============================================================
traceroute to 149.127.109.166 (149.127.109.166), 30 hops max, 32 byte packets
 1  10.0.2.1  1.46 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  19.12 ms  http: 403  http: 403
 4  154.54.47.213  1.69 ms  http: 403  http: 403
 5  154.54.44.229  6.85 ms  http: 403  http: 403
 6  154.54.28.73  2.05 ms  http: 403  http: 403
 7  154.54.44.229  6.83 ms  http: 403  http: 403
 8  154.54.28.69  20.27 ms  http: 403  http: 403
 9  154.54.24.221  36.45 ms  http: 403  http: 403
10  154.54.46.190  37.17 ms  http: 403  http: 403
11  38.140.164.58  37.31 ms  http: 403  http: 403
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *


Traceroute to German, Telekom (TCP Mode, Max 30 Hop)
============================================================
traceroute to 80.146.191.1 (80.146.191.1), 30 hops max, 32 byte packets
 1  10.0.2.1  1.31 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  15.27 ms  http: 403  http: 403
 4  129.250.4.154  41.50 ms  http: 403  http: 403
 5  129.250.4.45  45.03 ms  http: 403  http: 403
 6  *
 7  129.250.4.45  45.02 ms  http: 403  http: 403
 8  80.157.203.93  40.65 ms  http: 403  http: 403
 9  87.137.218.25  161.43 ms  http: 403  http: 403
10  80.146.191.1  171.19 ms  http: 403  http: 403


Traceroute to German, Frankfurt O2 (TCP Mode, Max 30 Hop)
============================================================
traceroute to 82.113.108.25 (82.113.108.25), 30 hops max, 32 byte packets
 1  10.0.2.1  1.27 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  19.89 ms  http: 403  http: 403
 4  209.120.138.250  1.15 ms  http: 403  http: 403
 5  94.142.99.249  42.38 ms  http: 403  http: 403
 6  209.120.138.250  1.74 ms  http: 403  http: 403
 7  94.142.99.253  42.80 ms  http: 403  http: 403
 8  213.140.35.239  119.18 ms  http: 403  http: 403
 9  213.140.36.232  115.35 ms  http: 403  http: 403
10  176.52.252.33  130.82 ms  http: 403  http: 403
11  62.53.8.186  130.69 ms  http: 403  http: 403
12  62.53.28.148  130.54 ms  http: 403  http: 403
13  62.53.14.103  131.38 ms  http: 403  http: 403
14  62.53.2.63  127.15 ms  http: 403  http: 403
15  82.113.108.25  131.10 ms  http: 403  http: 403


Traceroute to German, Frankfurt Vodafone (TCP Mode, Max 30 Hop)
============================================================
traceroute to 139.7.146.11 (139.7.146.11), 30 hops max, 32 byte packets
 1  10.0.2.1  1.20 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  16.49 ms  http: 403  http: 403
 4  63.223.46.26  40.27 ms  http: 403  http: 403
 5  195.2.19.209  56.78 ms  http: 403  http: 403
 6  63.223.46.26  40.35 ms  http: 403  http: 403
 7  195.2.19.209  56.52 ms  http: 403  http: 403
 8  195.2.31.177  136.81 ms  http: 403  http: 403
 9  195.2.31.114  136.93 ms  http: 403  http: 403
10  195.2.24.246  127.54 ms  http: 403  http: 403
11  195.2.9.41  136.73 ms  http: 403  http: 403
12  195.2.18.190  137.29 ms  http: 403  http: 403
13  *
14  145.253.5.57  137.15 ms  http: 403  http: 403
15  92.79.230.2  137.09 ms  http: 403  http: 403
16  139.7.148.84  137.03 ms  http: 403  http: 403
17  *
18  *
19  *
20  *
21  139.7.146.11  138.13 ms  http: 403  http: 403


Traceroute to German, Frankfurt China CT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 118.85.205.101 (118.85.205.101), 30 hops max, 32 byte packets
 1  10.0.2.1  1.22 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  19.92 ms  http: 403  http: 403
 4  218.30.54.72  34.04 ms  http: 403  http: 403
 5  202.97.90.138  63.18 ms  http: 403  http: 403
 6  218.30.54.72  31.85 ms  http: 403  http: 403
 7  202.97.90.138  74.18 ms  http: 403  http: 403
 8  118.85.205.101  162.86 ms  http: 403  http: 403


Traceroute to German, Frankfurt China CT CN2 (TCP Mode, Max 30 Hop)
============================================================
traceroute to 5.10.138.33 (5.10.138.33), 30 hops max, 32 byte packets
 1  10.0.2.1  1.28 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  19.83 ms  http: 403  http: 403
 4  *
 5  62.115.137.44  114.14 ms  http: 403  http: 403
 6  *
 7  62.115.137.44  111.79 ms  http: 403  http: 403
 8  *
 9  *
10  *
11  *
12  62.115.120.239  108.95 ms  http: 403  http: 403
13  80.239.193.226  109.82 ms  http: 403  http: 403
14  59.43.180.113  121.37 ms  http: 403  http: 403
15  5.10.138.33  121.06 ms  http: 403  http: 403


Traceroute to German, Frankfurt GTT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 213.200.65.70 (213.200.65.70), 30 hops max, 32 byte packets
 1  10.0.2.1  1.78 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  10.08 ms  http: 403  http: 403
 4  213.200.65.70  118.36 ms  http: 403  http: 403


Traceroute to German, FrankfurtCogentco (TCP Mode, Max 30 Hop)
============================================================
traceroute to 212.20.150.5 (212.20.150.5), 30 hops max, 32 byte packets
 1  10.0.2.1  1.27 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  2.10 ms  http: 403  http: 403
 4  154.54.47.213  1.71 ms  http: 403  http: 403
 5  154.54.3.214  11.64 ms  http: 403  http: 403
 6  154.54.47.213  1.77 ms  http: 403  http: 403
 7  154.54.3.214  11.66 ms  http: 403  http: 403
 8  154.54.44.170  23.52 ms  http: 403  http: 403
 9  154.54.6.222  122.69 ms  http: 403  http: 403
10  154.54.47.50  122.83 ms  http: 403  http: 403
11  154.54.30.186  121.23 ms  http: 403  http: 403
12  154.54.44.165  113.04 ms  http: 403  http: 403
13  130.117.0.122  122.84 ms  http: 403  http: 403
14  130.117.0.142  129.26 ms  http: 403  http: 403
15  212.20.150.5  125.65 ms  http: 403  http: 403


Traceroute to United Kingdom, Vodafone (TCP Mode, Max 30 Hop)
============================================================
traceroute to 194.62.232.211 (194.62.232.211), 30 hops max, 32 byte packets
 1  10.0.2.1  1.14 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  0.96 ms  http: 403  http: 403
 4  63.223.46.26  40.08 ms  http: 403  http: 403
 5  195.2.19.209  56.60 ms  http: 403  http: 403
 6  63.223.46.26  40.00 ms  http: 403  http: 403
 7  195.2.19.209  56.64 ms  http: 403  http: 403
 8  195.2.31.177  127.42 ms  http: 403  http: 403
 9  195.2.20.197  129.03 ms  http: 403  http: 403
10  195.2.24.246  127.44 ms  http: 403  http: 403
11  *
12  *
13  194.62.232.211  130.35 ms  http: 403  http: 403


Traceroute to United Kingdom， BT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 213.121.43.24 (213.121.43.24), 30 hops max, 32 byte packets
 1  10.0.2.1  1.02 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  10.23 ms  http: 403  http: 403
 4  69.174.5.6  63.86 ms  http: 403  http: 403
 5  166.49.195.146  115.49 ms  http: 403  http: 403
 6  69.174.5.6  36.31 ms  http: 403  http: 403
 7  166.49.195.138  106.09 ms  http: 403  http: 403
 8  166.49.209.133  105.30 ms  http: 403  http: 403
 9  62.6.201.249  110.04 ms  http: 403  http: 403
10  217.32.170.148  119.92 ms  http: 403  http: 403
11  194.72.7.101  119.58 ms  http: 403  http: 403
12  *
13  *
14  *
15  *
16  213.121.43.24  132.69 ms  http: 403  http: 403


Traceroute to United Kingdom, London TATA (TCP Mode, Max 30 Hop)
============================================================
traceroute to 80.231.131.34 (80.231.131.34), 30 hops max, 32 byte packets
 1  10.0.2.1  1.16 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  35.58 ms  http: 403  http: 403
 4  63.218.22.246  1.30 ms  http: 403  http: 403
 5  64.86.92.23  35.15 ms  http: 403  http: 403
 6  63.218.23.62  3.45 ms  http: 403  http: 403
 7  63.218.23.62  9.13 ms  http: 403  http: 403
 8  63.243.137.133  35.34 ms  http: 403  http: 403
 9  216.6.87.43  35.79 ms  http: 403  http: 403
10  216.6.57.5  35.86 ms  http: 403  http: 403
11  80.231.130.25  113.08 ms  http: 403  http: 403
12  80.231.130.25  112.38 ms  http: 403  http: 403
13  80.231.131.34  105.24 ms  http: 403  http: 403


Traceroute to Russia, China CT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 118.85.205.181 (118.85.205.181), 30 hops max, 32 byte packets
 1  10.0.2.1  0.97 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  5.69 ms  http: 403  http: 403
 4  63.223.46.26  40.04 ms  http: 403  http: 403
 5  218.30.54.96  41.07 ms  http: 403  http: 403
 6  63.223.46.26  40.08 ms  http: 403  http: 403
 7  218.30.54.96  43.27 ms  http: 403  http: 403
 8  202.97.49.226  62.33 ms  http: 403  http: 403
 9  202.97.61.210  154.73 ms  http: 403  http: 403
10  202.97.67.233  308.60 ms  http: 403  http: 403
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *


Traceroute to Russia, China CT CN2 (TCP Mode, Max 30 Hop)
============================================================
traceroute to 185.75.173.17 (185.75.173.17), 30 hops max, 32 byte packets
 1  10.0.2.1  1.54 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  25.05 ms  http: 403  http: 403
 4  *
 5  217.163.44.234  104.73 ms  http: 403  http: 403
 6  *
 7  217.163.47.130  104.43 ms  http: 403  http: 403
 8  59.43.182.2  130.76 ms  http: 403  http: 403
 9  185.75.173.17  153.65 ms  http: 403  http: 403


Traceroute to Russia, Moscow RT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 87.226.162.77 (87.226.162.77), 30 hops max, 32 byte packets
 1  10.0.2.1  1.11 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  12.05 ms  http: 403  http: 403
 4  *
 5  *
 6  *
 7  *
 8  195.122.183.218  125.10 ms  http: 403  http: 403
 9  185.140.151.251  154.03 ms  http: 403  http: 403
10  87.226.140.2  152.05 ms  http: 403  http: 403
11  *
12  87.226.162.77  159.35 ms  http: 403  http: 403


Traceroute to Russia, Moscow TTK (TCP Mode, Max 30 Hop)
============================================================
traceroute to 217.150.32.2 (217.150.32.2), 30 hops max, 32 byte packets
 1  10.0.2.1  1.16 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  19.05 ms  http: 403  http: 403
 4  63.218.233.6  131.97 ms  http: 403  http: 403
 5  188.43.202.234  153.18 ms  http: 403  http: 403
 6  63.218.233.6  130.99 ms  http: 403  http: 403
 7  188.43.202.234  151.93 ms  http: 403  http: 403
 8  188.43.202.233  158.71 ms  http: 403  http: 403
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *


Traceroute to Russia, Moscow MTS (TCP Mode, Max 30 Hop)
============================================================
traceroute to 195.34.32.71 (195.34.32.71), 30 hops max, 32 byte packets
 1  10.0.2.1  1.45 ms  http: 403  http: 403
 2  *
 3  206.71.158.6  18.90 ms  http: 403  http: 403
 4  4.69.135.162  131.60 ms  http: 403  http: 403
 5  213.242.69.98  140.72 ms  http: 403  http: 403
 6  4.69.135.162  131.52 ms  http: 403  http: 403
 7  213.242.69.98  138.19 ms  http: 403  http: 403
 8  212.188.54.1  144.06 ms  http: 403  http: 403
 9  212.188.2.38  155.56 ms  http: 403  http: 403
10  195.34.50.150  159.50 ms  http: 403  http: 403
11  195.34.53.253  156.53 ms  http: 403  http: 403
12  195.34.32.71  156.45 ms  http: 403  http: 403


 -> Traceroute Test (IPV6)

Traceroute to China, Beijing CU IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2408:80f0:4100:2005::3 (2408:80f0:4100:2005::3), 30 hops max, 32 byte packets
 1  *
 2  2602:ffc5:105::4  8.05 ms  http: 403  http: 403
 3  2604:4500:a::1c  8.71 ms  http: 403  http: 403
 4  fd80::afd:1039  7.52 ms  http: 403  http: 403
 5  fd80::afd:1025  9.03 ms  http: 403  http: 403
 6  fd80::afd:1011  0.50 ms  http: 403  http: 403
 7  fd80::afd:10be  0.74 ms  http: 403  http: 403
 8  2001:504:0:5::6939:1  0.89 ms  http: 403  http: 403
 9  *
10  2001:470:0:5b9::1  57.58 ms  http: 403  http: 403
11  *
12  *
13  *
14  2408:8000:2:8045::  199.58 ms  http: 403  http: 403
15  *
16  2408:8000:1100:2411::3  198.97 ms  http: 403  http: 403
17  2408:8000:1f10:3d04::3  207.70 ms  http: 403  http: 403
18  2408:80f0:4100:2006::1  194.62 ms  http: 403  http: 403
19  2408:80f0:4100:2006::b  202.12 ms  http: 403  http: 403
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *

Traceroute to China, Beijing CT IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2400:da00:2::29 (2400:da00:2::29), 30 hops max, 32 byte packets
 1  *
 2  2602:ffc5:105::4  51.98 ms  http: 403  http: 403
 3  2604:4500:a::1c  81.29 ms  http: 403  http: 403
 4  fd80::afd:102d  10.61 ms  http: 403  http: 403
 5  fd80::afd:1029  10.87 ms  http: 403  http: 403
 6  fd80::afd:1019  0.44 ms  http: 403  http: 403
 7  fd80::afd:10d2  0.72 ms  http: 403  http: 403
 8  fd80::afe:81  30.35 ms  http: 403  http: 403
 9  fd80::afd:3002  75.60 ms  http: 403  http: 403
10  fd80::afe:22  70.52 ms  http: 403  http: 403
11  *
12  2001:2035:0:ca6::2  51.12 ms  http: 403  http: 403
13  *
14  240e:0:a::cb:c29  227.87 ms  http: 403  http: 403
15  *
16  *
17  240e:1f:5000:f006::3  234.44 ms  http: 403  http: 403
18  240e:1f:5800:1c::2  240.14 ms  http: 403  http: 403
19  240e:97c:24:4000::  266.77 ms  http: 403  http: 403
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *

Traceroute to China, Beijing CM IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2409:8089:1020:50ff:1000::fd01 (2409:8089:1020:50ff:1000::fd01), 30 hops max, 32 byte packets
 1  *
 2  *
 3  *
 4  *
 5  *
 6  *
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *

Traceroute to China, Shanghai CU IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2408:8000:9000:20e6::b7 (2408:8000:9000:20e6::b7), 30 hops max, 32 byte packets
 1  *
 2  *
 3  *
 4  *
 5  *
 6  *
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *

Traceroute to China, Shanghai CT IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 240e:18:10:a01::1 (240e:18:10:a01::1), 30 hops max, 32 byte packets
 1  *
 2  *
 3  *
 4  *
 5  *
 6  *
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *

Traceroute to China, Shanghai CM IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2409:801e:5c03:2000::207 (2409:801e:5c03:2000::207), 30 hops max, 32 byte packets
 1  *
 2  *
 3  *
 4  *
 5  *
 6  *
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *

Traceroute to China, Guangzhou CU IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2408:8001:3011:310::3 (2408:8001:3011:310::3), 30 hops max, 32 byte packets
 1  *
 2  *
 3  *
 4  *
 5  *
 6  *
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *

Traceroute to China, Guangzhou CT IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 240e:ff:e02c:1:21:: (240e:ff:e02c:1:21::), 30 hops max, 32 byte packets
 1  *
 2  *
 3  *
 4  *
 5  *
 6  *
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *

Traceroute to China, Guangzhou CM IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2409:8057:5c00:30::6 (2409:8057:5c00:30::6), 30 hops max, 32 byte packets
 1  *
 2  *
 3  *
 4  *
 5  *
 6  *
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *

Traceroute to China, Beijing Dr.Peng IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2403:8880:400f::2 (2403:8880:400f::2), 30 hops max, 32 byte packets
 1  *
 2  *
 3  *
 4  *
 5  *
 6  *
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *

Traceroute to China, Beijing CERNET2 IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:da8:a0:1001::1 (2001:da8:a0:1001::1), 30 hops max, 32 byte packets
 1  *
 2  *
 3  *
 4  *
 5  *
 6  *
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *

Traceroute to China, Beijing CSTNET IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2400:dd00:0:37::213 (2400:dd00:0:37::213), 30 hops max, 32 byte packets
 1  *
 2  *
 3  *
 4  *
 5  *
 6  *
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  2400:dd00:0:37::213  1251.62 ms  http: 403  http: 403

Traceroute to China, Hongkong HKIX IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:7fa:0:1::ca28:a1a9 (2001:7fa:0:1::ca28:a1a9), 30 hops max, 32 byte packets
 1  *
 2  2602:ffc5:105::4  255.11 ms  http: 403  http: 403
 3  2604:4500:a::1c  1.94 ms  http: 403  http: 403
 4  fd80::afd:102d  8.26 ms  http: 403  http: 403
 5  fd80::afd:101d  20.29 ms  http: 403  http: 403
 6  fd80::afd:100d  0.38 ms  http: 403  http: 403
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *

Traceroute to China, Hongkong HE IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:470:0:490::2 (2001:470:0:490::2), 30 hops max, 32 byte packets
 1  *
 2  2602:ffc5:105::4  2.34 ms  http: 403  http: 403
 3  2604:4500:a::1c  4.30 ms  http: 403  http: 403
 4  fd80::afd:102d  19.25 ms  http: 403  http: 403
 5  fd80::afd:101d  2.51 ms  http: 403  http: 403
 6  fd80::afd:100d  4.74 ms  http: 403  http: 403
 7  fd80::afd:1002  28.59 ms  http: 403  http: 403
 8  *
 9  2001:470:0:5ab::2  0.81 ms  http: 403  http: 403
10  *
11  2001:470:0:5b9::1  51.47 ms  http: 403  http: 403
12  *
13  2001:470:0:463::2  154.37 ms  http: 403  http: 403
14  *
15  2001:470:0:5f9::1  197.13 ms  http: 403  http: 403
16  2001:470:0:490::2  190.21 ms  http: 403  http: 403

Traceroute to United States, San Jose HE IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:470:1:ff::1 (2001:470:1:ff::1), 30 hops max, 32 byte packets
 1  *
 2  2602:ffc5:105::4  7.27 ms  http: 403  http: 403
 3  2604:4500:a::1c  6.75 ms  http: 403  http: 403
 4  fd80::afd:1039  19.00 ms  http: 403  http: 403
 5  fd80::afd:1021  2.44 ms  http: 403  http: 403
 6  fd80::afd:100d  3.53 ms  http: 403  http: 403
 7  fd80::afd:1002  0.37 ms  http: 403  http: 403
 8  *
 9  2001:470:0:3e3::1  58.58 ms  http: 403  http: 403
10  2001:470:1:ff::1  74.33 ms  http: 403  http: 403

Traceroute to United States, Chicago NTT IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:418:0:5000::1026 (2001:418:0:5000::1026), 30 hops max, 32 byte packets
 1  *
 2  *
 3  *
 4  *
 5  *
 6  *
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *

Traceroute to United States, Los Angeles Telia IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:2000:3080:1e96::2 (2001:2000:3080:1e96::2), 30 hops max, 32 byte packets
 1  *
 2  *
 3  *
 4  *
 5  *
 6  *
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *

Traceroute to United States, Los Angeles GTT IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:668:0:3:ffff:0:d8dd:9d5a (2001:668:0:3:ffff:0:d8dd:9d5a), 30 hops max, 32 byte packets
 1  *
 2  *
 3  *
 4  *
 5  *
 6  *
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *

Traceroute to United States, Kansas City Sprint IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2600:0:1:1239:144:228:241:71 (2600:0:1:1239:144:228:241:71), 30 hops max, 32 byte packets
 1  *
 2  *
 3  *
 4  *
 5  *
 6  *
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *

Traceroute to United States, Los Angeles Verizon IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2600:80a:2::15 (2600:80a:2::15), 30 hops max, 32 byte packets
 1  *
 2  *
 3  *
 4  *
 5  *
 6  *
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *

Traceroute to United Status, Ashburn Cogentco IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:550:0:1000::9a36:4215 (2001:550:0:1000::9a36:4215), 30 hops max, 32 byte packets
 1  *
 2  *
 3  *
 4  *
 5  *
 6  *
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *

Traceroute to United States, San Jose Level3 IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:1900:2100::2eb5 (2001:1900:2100::2eb5), 30 hops max, 32 byte packets
 1  *
 2  *
 3  *
 4  *
 5  *
 6  *
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *

Traceroute to United States, Seattle Zayo IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:438:ffff::407d:d6a (2001:438:ffff::407d:d6a), 30 hops max, 32 byte packets
 1  *
 2  *
 3  *
 4  *
 5  *
 6  *
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *

Traceroute to France, Paris HE IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:470:0:349::1 (2001:470:0:349::1), 30 hops max, 32 byte packets
 1  *
 2  *
 3  *
 4  *
 5  *
 6  *
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *

Traceroute to German, Frankfurt NTT IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:728:0:5000::6f6 (2001:728:0:5000::6f6), 30 hops max, 32 byte packets
 1  *
 2  *
 3  *
 4  *
 5  *
 6  *
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *
```
---
