---
title: Network and performance test of FirstByte.ru 55RUB vps
date: 2021-10-25 21:05:28
tags: vps
---
Lemonbench full test result [https://paste.ubuntu.com/p/BSZsnpQPgT](https://paste.ubuntu.com/p/BSZsnpQPgT)
```bash
LemonBench Linux System Benchmark Utility Version 20201005 Intl BetaVersion 
 
 Bench Start Time:	2021-10-25 14:30:06
 Bench Finish Time:	2021-10-25 15:06:50
 Test Mode:		Full Mode
 
 -> System Information
 
 OS Release:		Ubuntu 20.04.3 LTS (Focal Fossa)  (x86_64)
 CPU Model:		QEMU Virtual CPU version 2.5+  2.00 GHz
 CPU Cache Size:	16384 KB
 CPU Number:		1 vCPU
 Virt Type:		KVM
 Memory Usage:		165.02 MB / 477.93 MB
 Swap Usage:		91.50 MB / 329.13 MB
 Disk Usage:		3.59 GB / 7.16 GB
 Boot Device:		/dev/vda2
 Load (1/5/15min):	0.66 0.30 0.12 
 CPU Usage:		15.0% used, 0.0% iowait, 10.0% steal
 Kernel Version:	5.4.0-84-generic
 Network CC Method:	bbr + fq

 -> Network Information

 IPV4 - IP Address:	[RU] 147.78.64.*
 IPV4 - ASN Info:	204997 (FIRSTBYTE-AS - Network Management Ltd, SC)
 IPV4 - Region:		Russian Federation Moscow 
 IPV6 - IP Address:	[RU] 2a04:5200:fff1::*
 IPV6 - ASN Info:	50113 (SuperServersDatacenter - NTX Technologies s.r.o., CZ)
 IPV6 - Region:		Russian Federation Russian Federation 

 -> Media Unlock Test

 HBO Now:				No
 Bahamut Anime:				No
 Abema.TV:				No
 Princess Connect Re:Dive Japan:	Yes
 BBC:					No
 Bilibili China Mainland Only:		No
 Bilibili Hongkong/Macau/Taiwan:	No
 Bilibili Taiwan Only:			No

 -> CPU Performance Test (Standard Mode, 3-Pass @ 30sec)

 1 Thread Test:			565 Scores

 -> Memory Performance Test (Standard Mode, 3-Pass @ 30sec)

 1 Thread - Read Test :		10124.29 MB/s
 1 Thread - Write Test:		7463.25 MB/s

 -> Disk Speed Test (4K Block/1M Block, Direct-Write)

 Test Name		Write Speed				Read Speed
 10MB-4K Block		16.0 MB/s (3902 IOPS, 0.66 s)		18.7 MB/s (4567 IOPS, 0.56 s)
 10MB-1M Block		501 MB/s (478 IOPS, 0.02 s)		826 MB/s (787 IOPS, 0.01 s)
 100MB-4K Block		14.9 MB/s (3647 IOPS, 7.02 s)		13.6 MB/s (3310 IOPS, 7.73 s)
 100MB-1M Block		905 MB/s (863 IOPS, 0.12 s)		1.3 GB/s (1222 IOPS, 0.08 s)
 1GB-4K Block		14.6 MB/s (3555 IOPS, 71.99 s)		19.8 MB/s (4823 IOPS, 53.07 s)
 1GB-1M Block		686 MB/s (653 IOPS, 1.53 s)		1.6 GB/s (1556 IOPS, 0.64 s)

 -> Speedtest.net Network Speed Test

 Node Name			Upload Speed	Download Speed	Ping Latency	Server Name
 Speedtest Default		11.50 MB/s	11.20 MB/s	1.88 ms		Opticom (Russia Mytishchi)
 China, Nanjing CU  		12.57 MB/s	7.42 MB/s	236.45 ms	China Unicom (China Nanjing)
 China, Shanghai CU 		12.74 MB/s	11.82 MB/s	210.43 ms	China Unicom 5G (China ShangHai)
 China, Hangzhou CT 		5.48 MB/s	0.65 MB/s	332.74 ms	China Telecom ZheJiang Branch (China Hangzhou)
 China, Nanjing CT  		12.40 MB/s	0.79 MB/s	265.75 ms	China Telecom JiangSu 5G (China Nanjing)
 China, Guangzhou CT		7.80 MB/s	0.49 MB/s	257.93 ms	ChinaTelecom 5G (China Guangzhou)
 China, Wuhan CT    		12.02 MB/s	1.00 MB/s	263.21 ms	China Telecom Wuhan Branch (China Wuhan)
 China, Shenyang CM 		Fail: Timeout Exceeded after 60 seconds
 China, Hangzhou CM 		12.93 MB/s	11.68 MB/s	308.89 ms	China Mobile Group Zhejiang Co.,Ltd (China Hangzhou)
 China, Nanning CM  		12.50 MB/s	6.31 MB/s	10.57 ms	GX ChinaMobile (China Nanning)
 China, Lanzhou CM  		12.97 MB/s	1.68 MB/s	258.78 ms	Lanzhou,China Mobile,Gansu (China Lanzhou)
 Hong Kong, CSL     		11.26 MB/s	3.29 MB/s	350.43 ms	CSL (Hong Kong Kwai Chung)
 Hong Kong, PCCW    		12.86 MB/s	11.62 MB/s	193.10 ms	STC (China Hong Kong)
 Korea, South Korea 		12.25 MB/s	0.56 MB/s	266.91 ms	kdatacenter.com (South Korea Seoul)
 Japan, GLBB        		12.48 MB/s	8.45 MB/s	251.53 ms	Allied Telesis Capital Corporation (Japan Fussa-shi)
 Taiwan, FET        		Fail: Timeout Exceeded after 60 seconds
 Taiwan, Chief      		Fail: Host resolve failed: Timeout occurred in connect.
 Taiwan, TWM        		12.40 MB/s	11.56 MB/s	331.85 ms	Taiwan Mobile (Taiwan Taoyuan)
 Singapore, Singtel 		Fail: Timeout Exceeded after 60 seconds
 Singapore, M1      		12.96 MB/s	11.42 MB/s	204.62 ms	M1 Limited (Singapore Singapore)
 Singapore, NME     		12.71 MB/s	11.41 MB/s	184.32 ms	NewMedia Express (Singapore Singapore)
 USA, Century Link  		12.77 MB/s	0.39 MB/s	186.75 ms	CenturyLink (United States Seattle, WA)

 -> Traceroute Test (IPV4)


Traceroute to China, Beijing CU (TCP Mode, Max 30 Hop)
============================================================
traceroute to 123.125.99.1 (123.125.99.1), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.53 ms  *  Russian Federation, Moscow, ntx.ru
 3  92.63.203.78  0.65 ms  AS202984  Russian Federation, Moscow, ngs.ru
 4  92.63.203.104  0.98 ms  AS202984  Russian Federation, Moscow, ngs.ru
 5  193.106.112.103  1.97 ms  *  Russian Federation, Moscow, w-ix.ru
 6  188.43.228.198  1.73 ms  AS20485  Russian Federation, Moscow, ttk.ru
 7  *
 8  *
 9  *
10  *
11  *
12  *
13  61.51.169.146  247.56 ms  AS4808  China, Beijing, ChinaUnicom
14  61.148.158.106  250.69 ms  AS4808  China, Beijing, ChinaUnicom
15  61.135.113.154  238.53 ms  AS4808  China, Beijing, ChinaUnicom
16  *
17  123.125.99.1  240.36 ms  AS4808  China, Beijing, ChinaUnicom


Traceroute to China, Beijing CT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 180.149.128.1 (180.149.128.1), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.55 ms  *  Russian Federation, Moscow, ntx.ru
 3  31.28.19.184  11.08 ms  AS29076  Russian Federation, Moscow Oblast, Lobnya, cloud-ix.net
 4  62.115.135.108  11.96 ms  AS1299  telia.com
 5  62.115.143.24  18.82 ms  AS1299  Sweden, Stockholm County, Stockholm, telia.com
 6  62.115.143.29  38.93 ms  AS1299  telia.com
 7  *
 8  118.85.205.81  45.34 ms  AS4134  Germany, Hesse, Frankfurt, ChinaTelecom
 9  202.97.58.77  190.17 ms  AS4134  China, Beijing, ChinaTelecom
10  202.97.12.61  193.93 ms  AS4134  China, Beijing, ChinaTelecom
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


Traceroute to China, Beijing CM (TCP Mode, Max 30 Hop)
============================================================
traceroute to 211.136.25.153 (211.136.25.153), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.55 ms  *  Russian Federation, Moscow, ntx.ru
 3  109.239.134.45  2.91 ms  AS31500  Russian Federation, Moscow, gblnet.ru
 4  89.20.133.40  2.13 ms  AS12714  Russian Federation, Moscow, netbynet.ru
 5  212.1.239.118  37.47 ms  AS12714  Germany, Hesse, Frankfurt, netbynet.ru
 6  *
 7  223.120.10.85  43.87 ms  AS58453  Germany, Hesse, Frankfurt, ChinaMobile
 8  *
 9  *
10  *
11  *
12  111.24.2.97  267.42 ms  AS9808  China, Beijing, ChinaMobile
13  111.24.14.54  264.49 ms  AS9808  China, Beijing, ChinaMobile
14  *
15  *
16  211.136.95.226  291.32 ms  AS56048  China, Beijing, ChinaMobile
17  *
18  *
19  211.136.25.153  273.52 ms  AS56048  China, Beijing, ChinaMobile


Traceroute to China, Shanghai CU (TCP Mode, Max 30 Hop)
============================================================
traceroute to 58.247.0.49 (58.247.0.49), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.45 ms  *  Russian Federation, Moscow, ntx.ru
 3  109.239.134.45  5.59 ms  AS31500  Russian Federation, Moscow, gblnet.ru
 4  91.108.51.6  22.43 ms  *  Russian Federation, Saint Petersburg, gblnet.ru
 5  213.242.69.189  35.50 ms  AS3356  Sweden, Stockholm County, Stockholm, level3.com
 6  4.69.209.165  190.37 ms  AS3356  United States, California, San Jose, level3.com
 7  4.53.208.102  280.40 ms  AS3356  United States, California, San Jose, level3.com
 8  219.158.116.233  299.02 ms  AS4837  China, Shanghai, ChinaUnicom
 9  219.158.6.185  300.18 ms  AS4837  China, Beijing, ChinaUnicom
10  *
11  *
12  112.64.252.197  295.50 ms  AS17621  China, Shanghai, ChinaUnicom
13  58.247.0.49  296.42 ms  AS17621  China, Shanghai, ChinaUnicom


Traceroute to China, Shanghai CT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 180.153.28.1 (180.153.28.1), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.59 ms  *  Russian Federation, Moscow, ntx.ru
 3  109.239.134.45  2.50 ms  AS31500  Russian Federation, Moscow, gblnet.ru
 4  91.108.51.6  22.48 ms  *  Russian Federation, Saint Petersburg, gblnet.ru
 5  213.242.69.189  49.21 ms  AS3356  Sweden, Stockholm County, Stockholm, level3.com
 6  *
 7  212.72.45.222  49.51 ms  AS3356  Netherlands, North Holland, Amsterdam, level3.com
 8  *
 9  *
10  202.97.50.217  276.85 ms  AS4134  China, Shanghai, ChinaTelecom
11  101.95.88.97  266.26 ms  AS4812  China, Shanghai, ChinaTelecom
12  *
13  124.74.232.58  265.73 ms  AS4811  China, Shanghai, ChinaTelecom
14  101.227.255.46  240.24 ms  AS4812  China, Shanghai, ChinaTelecom
15  *
16  180.153.28.1  293.62 ms  AS4812  China, Shanghai, ChinaTelecom


Traceroute to China, Shanghai CM (TCP Mode, Max 30 Hop)
============================================================
traceroute to 221.183.55.22 (221.183.55.22), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.45 ms  *  Russian Federation, Moscow, ntx.ru
 3  194.186.66.33  2.00 ms  AS3216  Russian Federation, Moscow, beeline.ru
 4  79.104.235.70  19.10 ms  *  Russian Federation, beeline.ru
 5  *
 6  4.69.167.118  54.97 ms  AS3356  United Kingdom, London, level3.com
 7  *
 8  223.120.10.85  49.09 ms  AS58453  Germany, Hesse, Frankfurt, ChinaMobile
 9  *
10  *
11  221.183.55.22  271.45 ms  AS9808  China, Shanghai, ChinaMobile


Traceroute to China, Guangzhou CU (TCP Mode, Max 30 Hop)
============================================================
traceroute to 210.21.4.130 (210.21.4.130), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  1.80 ms  *  Russian Federation, Moscow, ntx.ru
 3  31.28.19.100  1.35 ms  AS29076  Russian Federation, Moscow, cloud-ix.net
 4  62.115.147.142  10.72 ms  AS1299  Russian Federation, Moscow, telia.com
 5  62.115.135.107  19.42 ms  AS1299  telia.com
 6  62.115.135.95  11.32 ms  AS1299  telia.com
 7  62.115.138.105  39.44 ms  AS1299  telia.com
 8  62.115.124.119  38.97 ms  AS1299  Germany, Hesse, Frankfurt, telia.com
 9  *
10  *
11  219.158.5.198  224.74 ms  AS4837  China, Shanghai, ChinaUnicom
12  219.158.103.33  202.37 ms  AS4837  China, Guangdong, Guangzhou, ChinaUnicom
13  219.158.8.189  205.44 ms  AS4837  China, Guangdong, Guangzhou, ChinaUnicom
14  *
15  112.96.0.2  211.02 ms  AS17816  China, Guangdong, Guangzhou, ChinaUnicom
16  *
17  120.80.91.62  208.61 ms  AS17816  China, Guangdong, Guangzhou, ChinaUnicom
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
 1  *
 2  185.188.180.89  0.61 ms  *  Russian Federation, Moscow, ntx.ru
 3  194.186.66.33  1.67 ms  AS3216  Russian Federation, Moscow, beeline.ru
 4  79.104.235.70  18.37 ms  *  Russian Federation, beeline.ru
 5  195.89.102.45  36.31 ms  AS1273  vodafone.com
 6  195.2.9.241  119.00 ms  AS1273  vodafone.com
 7  195.2.31.13  51.75 ms  AS1273  United Kingdom, London, vodafone.com
 8  195.2.24.245  118.18 ms  AS1273  United States, Virginia, Ashburn, vodafone.com
 9  195.2.14.70  130.46 ms  AS1273  United States, Virginia, Ashburn, vodafone.com
10  202.97.49.110  194.59 ms  AS4134  United States, California, San Jose, ChinaTelecom
11  202.97.58.129  317.20 ms  AS4134  China, Guangdong, Guangzhou, ChinaTelecom
12  *
13  *
14  113.108.209.1  312.92 ms  AS58466  China, Guangdong, Guangzhou, ChinaTelecom


Traceroute to China, Guangzhou CM (TCP Mode, Max 30 Hop)
============================================================
traceroute to 211.139.129.5 (211.139.129.5), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.53 ms  *  Russian Federation, Moscow, ntx.ru
 3  31.28.19.100  1.97 ms  AS29076  Russian Federation, Moscow, cloud-ix.net
 4  195.34.38.133  1.65 ms  AS8359  Russian Federation, Moscow, mts.ru
 5  195.34.53.205  19.46 ms  AS8359  Russian Federation, Moscow, mts.ru
 6  212.188.28.149  36.53 ms  AS8359  Russian Federation, Moscow, mts.ru
 7  195.34.59.50  34.45 ms  AS8359  Russian Federation, Moscow, mts.ru
 8  *
 9  223.120.10.41  41.63 ms  AS58453  Germany, Hesse, Frankfurt, ChinaMobile
10  *
11  221.183.55.66  236.12 ms  AS9808  China, Guangdong, Guangzhou, ChinaMobile
12  221.176.24.141  304.73 ms  AS9808  China, Guangdong, Guangzhou, ChinaMobile
13  221.183.68.146  290.05 ms  AS9808  China, Guangdong, Guangzhou, ChinaMobile
14  111.24.5.1  289.60 ms  AS9808  China, Guangdong, Guangzhou, ChinaMobile
15  111.24.14.82  232.39 ms  AS9808  China, Guangdong, Guangzhou, ChinaMobile
16  211.136.204.65  290.95 ms  AS56040  China, Guangdong, Guangzhou, ChinaMobile
17  211.136.249.129  291.34 ms  AS56040  China, Guangdong, Guangzhou, ChinaMobile
18  211.139.129.5  246.03 ms  AS56040  China, Guangdong, Guangzhou, ChinaMobile


Traceroute to China, Shanghai CU AS9929 (TCP Mode, Max 30 Hop)
============================================================
traceroute to 210.13.66.238 (210.13.66.238), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.53 ms  *  Russian Federation, Moscow, ntx.ru
 3  109.239.134.45  2.49 ms  AS31500  Russian Federation, Moscow, gblnet.ru
 4  91.108.51.6  22.51 ms  *  Russian Federation, Saint Petersburg, gblnet.ru
 5  213.242.69.189  32.66 ms  AS3356  Sweden, Stockholm County, Stockholm, level3.com
 6  4.68.106.130  43.11 ms  AS3356  Sweden, Stockholm County, Stockholm, level3.com
 7  154.54.36.89  45.57 ms  AS174  Sweden, Stockholm County, Stockholm, cogentco.com
 8  154.54.61.241  42.92 ms  AS174  Denmark, Capital Region of Denmark, Copenhagen, cogentco.com
 9  154.54.61.221  42.91 ms  AS174  Germany, Hamburg, cogentco.com
10  154.54.58.229  48.13 ms  AS174  cogentco.com
11  154.54.56.190  49.89 ms  http: 403  http: 403
12  154.25.12.77  49.76 ms  http: 403  http: 403
13  149.11.84.106  172.89 ms  http: 403  http: 403
14  *
15  *
16  218.105.2.210  193.91 ms  http: 403  http: 403
17  210.13.116.86  197.07 ms  http: 403  http: 403
18  210.13.64.109  195.01 ms  http: 403  http: 403
19  210.13.64.110  196.04 ms  http: 403  http: 403
20  210.13.66.237  238.00 ms  http: 403  http: 403
21  210.13.66.238  196.15 ms  http: 403  http: 403


Traceroute to China, Shanghai CT CN2 (TCP Mode, Max 30 Hop)
============================================================
traceroute to 58.32.0.1 (58.32.0.1), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.53 ms  http: 403  http: 403
 3  31.28.19.184  11.17 ms  http: 403  http: 403
 4  62.115.135.108  11.37 ms  http: 403  http: 403
 5  62.115.141.22  19.82 ms  http: 403  http: 403
 6  62.115.115.58  30.73 ms  http: 403  http: 403
 7  80.91.249.10  44.28 ms  http: 403  http: 403
 8  62.115.120.239  42.36 ms  http: 403  http: 403
 9  80.239.193.226  49.25 ms  http: 403  http: 403
10  59.43.187.185  256.90 ms  http: 403  http: 403
11  *
12  59.43.138.69  260.78 ms  http: 403  http: 403
13  101.95.88.230  248.65 ms  http: 403  http: 403
14  101.95.95.90  219.08 ms  http: 403  http: 403
15  58.32.0.1  282.40 ms  http: 403  http: 403


Traceroute to China, Guangzhou CT CN2 Gaming Broadband (TCP Mode, Max 30 Hop)
============================================================
traceroute to 119.121.0.1 (119.121.0.1), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.53 ms  http: 403  http: 403
 3  31.28.19.184  11.12 ms  http: 403  http: 403
 4  62.115.135.108  11.42 ms  http: 403  http: 403
 5  62.115.143.24  19.47 ms  http: 403  http: 403
 6  62.115.115.58  32.01 ms  http: 403  http: 403
 7  80.91.249.10  46.05 ms  http: 403  http: 403
 8  62.115.122.189  44.23 ms  http: 403  http: 403
 9  80.239.193.226  49.17 ms  http: 403  http: 403
10  59.43.184.125  301.52 ms  http: 403  http: 403
11  *
12  59.43.130.101  271.53 ms  http: 403  http: 403
13  183.57.161.14  242.77 ms  http: 403  http: 403
14  119.121.0.1  279.00 ms  http: 403  http: 403


Traceroute to China, Beijing Dr.Peng Home Network (TCP Mode, Max 30 Hop)
============================================================
traceroute to 14.131.128.1 (14.131.128.1), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.77 ms  http: 403  http: 403
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
 1  *
 2  185.188.180.89  0.58 ms  http: 403  http: 403
 3  31.28.19.184  10.91 ms  http: 403  http: 403
 4  62.115.135.95  11.02 ms  http: 403  http: 403
 5  62.115.141.22  20.28 ms  http: 403  http: 403
 6  62.115.138.105  38.94 ms  http: 403  http: 403
 7  *
 8  *
 9  219.158.14.189  222.29 ms  http: 403  http: 403
10  219.158.9.226  286.56 ms  http: 403  http: 403
11  219.158.4.173  252.67 ms  http: 403  http: 403
12  *
13  219.158.16.89  342.12 ms  http: 403  http: 403
14  *
15  218.241.244.2  267.76 ms  http: 403  http: 403
16  218.241.252.14  276.03 ms  http: 403  http: 403
17  218.241.244.14  289.19 ms  http: 403  http: 403
18  218.241.245.158  315.32 ms  http: 403  http: 403
19  218.241.254.234  306.09 ms  http: 403  http: 403
20  218.241.245.54  312.17 ms  http: 403  http: 403
21  *
22  211.167.230.100  247.29 ms  http: 403  http: 403


Traceroute to China, Beijing CERNET (TCP Mode, Max 30 Hop)
============================================================
traceroute to 202.205.109.205 (202.205.109.205), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.42 ms  http: 403  http: 403
 3  194.186.66.33  2.38 ms  http: 403  http: 403
 4  79.104.225.148  44.17 ms  http: 403  http: 403
 5  80.249.212.88  82.03 ms  http: 403  http: 403
 6  202.84.178.53  58.01 ms  http: 403  http: 403
 7  202.84.141.230  127.93 ms  http: 403  http: 403
 8  202.84.141.229  134.93 ms  http: 403  http: 403
 9  202.40.148.97  192.92 ms  http: 403  http: 403
10  202.84.140.1  334.10 ms  http: 403  http: 403
11  202.84.140.1  332.53 ms  http: 403  http: 403
12  202.84.140.1  331.14 ms  http: 403  http: 403
13  202.84.153.26  334.13 ms  http: 403  http: 403
14  61.8.59.38  364.57 ms  http: 403  http: 403
15  *
16  *
17  101.4.118.213  406.78 ms  http: 403  http: 403
18  *
19  101.4.113.110  405.55 ms  http: 403  http: 403
20  *
21  *
22  202.205.109.205  408.80 ms  http: 403  http: 403


Traceroute to China, Beijing CSTNET (TCP Mode, Max 30 Hop)
============================================================
traceroute to 159.226.254.1 (159.226.254.1), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.63 ms  http: 403  http: 403
 3  212.8.232.225  2.18 ms  http: 403  http: 403
 4  62.76.88.188  1.52 ms  http: 403  http: 403
 5  178.176.152.166  20.35 ms  http: 403  http: 403
 6  83.169.204.116  36.06 ms  http: 403  http: 403
 7  83.169.204.126  36.58 ms  http: 403  http: 403
 8  *
 9  *
10  154.54.58.238  48.99 ms  http: 403  http: 403
11  154.54.58.238  49.14 ms  http: 403  http: 403
12  154.54.6.26  242.33 ms  http: 403  http: 403
13  154.18.4.2  294.36 ms  http: 403  http: 403
14  159.226.254.61  338.23 ms  http: 403  http: 403
15  159.226.254.1  328.54 ms  http: 403  http: 403


Traceroute to China, Beijing GCable (TCP Mode, Max 30 Hop)
============================================================
traceroute to 211.156.140.17 (211.156.140.17), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.50 ms  http: 403  http: 403
 3  31.28.19.184  11.18 ms  http: 403  http: 403
 4  62.115.135.108  10.71 ms  http: 403  http: 403
 5  62.115.141.22  26.92 ms  http: 403  http: 403
 6  62.115.138.105  38.49 ms  http: 403  http: 403
 7  62.115.114.89  39.22 ms  http: 403  http: 403
 8  118.85.205.81  44.85 ms  http: 403  http: 403
 9  202.97.43.33  208.62 ms  http: 403  http: 403
10  202.97.53.61  199.03 ms  http: 403  http: 403
11  *
12  219.141.142.121  197.58 ms  http: 403  http: 403
13  *
14  106.120.252.154  188.92 ms  http: 403  http: 403
15  211.156.131.93  189.74 ms  http: 403  http: 403
16  211.156.131.93  189.27 ms  http: 403  http: 403
17  211.156.140.17  216.84 ms  http: 403  http: 403


Traceroute to China, Hongkong CU (TCP Mode, Max 30 Hop)
============================================================
traceroute to 203.160.95.218 (203.160.95.218), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.88 ms  http: 403  http: 403
 3  194.186.66.33  4.00 ms  http: 403  http: 403
 4  79.104.225.57  3.93 ms  http: 403  http: 403
 5  217.150.48.182  16.26 ms  http: 403  http: 403
 6  *
 7  *
 8  *
 9  *
10  202.77.22.89  195.59 ms  http: 403  http: 403
11  203.160.95.218  182.54 ms  http: 403  http: 403


Traceroute to China, Hongkong CT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 203.215.232.173 (203.215.232.173), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.61 ms  http: 403  http: 403
 3  212.8.232.225  1.65 ms  http: 403  http: 403
 4  62.76.88.188  1.44 ms  http: 403  http: 403
 5  188.170.162.66  20.38 ms  http: 403  http: 403
 6  83.169.204.112  35.67 ms  http: 403  http: 403
 7  83.169.204.126  35.38 ms  http: 403  http: 403
 8  37.29.109.98  42.26 ms  http: 403  http: 403
 9  37.29.109.98  42.37 ms  http: 403  http: 403
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
 1  *
 2  185.188.180.89  0.80 ms  http: 403  http: 403
 3  212.8.232.225  1.86 ms  http: 403  http: 403
 4  62.76.88.188  1.47 ms  http: 403  http: 403
 5  188.170.162.66  16.67 ms  http: 403  http: 403
 6  83.169.204.130  21.27 ms  http: 403  http: 403
 7  83.169.204.70  19.85 ms  http: 403  http: 403
 8  195.12.255.204  32.29 ms  http: 403  http: 403
 9  195.12.255.204  32.02 ms  http: 403  http: 403
10  62.115.120.68  44.33 ms  http: 403  http: 403
11  62.115.122.161  43.35 ms  http: 403  http: 403
12  80.239.193.226  48.28 ms  http: 403  http: 403
13  59.43.183.141  275.01 ms  http: 403  http: 403
14  59.43.183.141  274.32 ms  http: 403  http: 403
15  203.8.25.187  274.00 ms  http: 403  http: 403


Traceroute to China, Hongkong CM (TCP Mode, Max 30 Hop)
============================================================
traceroute to 203.142.105.9 (203.142.105.9), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.53 ms  http: 403  http: 403
 3  212.8.232.225  1.65 ms  http: 403  http: 403
 4  62.76.88.188  1.67 ms  http: 403  http: 403
 5  178.176.152.166  1.75 ms  http: 403  http: 403
 6  83.169.204.180  55.40 ms  http: 403  http: 403
 7  83.169.204.126  41.36 ms  http: 403  http: 403
 8  83.169.204.126  41.52 ms  http: 403  http: 403
 9  *
10  223.118.18.185  50.75 ms  http: 403  http: 403
11  223.118.18.97  50.81 ms  http: 403  http: 403
12  223.118.2.122  303.65 ms  http: 403  http: 403
13  223.119.17.1  289.56 ms  http: 403  http: 403
14  *
15  203.142.126.6  287.03 ms  http: 403  http: 403
16  203.142.126.18  306.35 ms  http: 403  http: 403
17  203.142.126.18  308.88 ms  http: 403  http: 403
18  203.142.105.9  305.62 ms  http: 403  http: 403


Traceroute to China, Hongkong HGC (TCP Mode, Max 30 Hop)
============================================================
traceroute to 218.188.104.30 (218.188.104.30), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.61 ms  http: 403  http: 403
 3  92.63.203.78  0.94 ms  http: 403  http: 403
 4  92.63.203.110  1.14 ms  http: 403  http: 403
 5  193.106.112.5  17.07 ms  http: 403  http: 403
 6  80.249.210.31  53.19 ms  http: 403  http: 403
 7  118.143.225.53  57.41 ms  http: 403  http: 403
 8  118.143.225.41  178.20 ms  http: 403  http: 403
 9  118.143.224.201  186.38 ms  http: 403  http: 403
10  218.189.5.24  174.36 ms  http: 403  http: 403
11  218.188.104.30  177.14 ms  http: 403  http: 403


Traceroute to China, Hongkong HKBN (TCP Mode, Max 30 Hop)
============================================================
traceroute to 210.6.23.239 (210.6.23.239), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.58 ms  http: 403  http: 403
 3  213.219.206.145  1.49 ms  http: 403  http: 403
 4  213.248.3.239  1.95 ms  http: 403  http: 403
 5  195.208.209.30  201.91 ms  http: 403  http: 403
 6  61.244.225.96  193.51 ms  http: 403  http: 403
 7  203.186.235.137  199.69 ms  http: 403  http: 403
 8  *
 9  210.6.23.239  193.86 ms  http: 403  http: 403


Traceroute to China, Hongkong PCCW (TCP Mode, Max 30 Hop)
============================================================
traceroute to 202.85.125.60 (202.85.125.60), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  1.24 ms  http: 403  http: 403
 3  31.28.19.184  11.05 ms  http: 403  http: 403
 4  62.115.135.108  15.50 ms  http: 403  http: 403
 5  62.115.143.24  19.14 ms  http: 403  http: 403
 6  62.115.143.29  39.18 ms  http: 403  http: 403
 7  62.115.114.89  39.40 ms  http: 403  http: 403
 8  80.239.193.95  38.21 ms  http: 403  http: 403
 9  63.223.20.37  354.13 ms  http: 403  http: 403
10  63.222.45.38  352.55 ms  http: 403  http: 403
11  202.153.103.69  373.25 ms  http: 403  http: 403
12  202.153.99.203  360.35 ms  http: 403  http: 403
13  203.215.244.33  360.32 ms  http: 403  http: 403
14  202.85.125.60  360.75 ms  http: 403  http: 403


Traceroute to China, Hongkong TGT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 202.123.76.239 (202.123.76.239), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  7.62 ms  http: 403  http: 403
 3  31.28.19.100  1.14 ms  http: 403  http: 403
 4  195.34.38.133  2.92 ms  http: 403  http: 403
 5  195.34.53.205  20.27 ms  http: 403  http: 403
 6  212.188.28.149  158.82 ms  http: 403  http: 403
 7  212.188.29.26  158.08 ms  http: 403  http: 403
 8  212.188.42.130  37.42 ms  http: 403  http: 403
 9  195.34.50.154  51.29 ms  http: 403  http: 403
10  212.188.2.2  158.43 ms  http: 403  http: 403
11  212.188.29.138  159.85 ms  http: 403  http: 403
12  212.188.28.213  157.98 ms  http: 403  http: 403
13  212.188.2.106  100.31 ms  http: 403  http: 403
14  195.34.59.248  157.56 ms  http: 403  http: 403
15  123.255.91.116  227.61 ms  http: 403  http: 403
16  203.78.72.192  229.38 ms  http: 403  http: 403
17  203.78.73.75  229.94 ms  http: 403  http: 403
18  *
19  202.123.76.239  227.63 ms  http: 403  http: 403


Traceroute to China, Hongkong WTT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 59.152.252.242 (59.152.252.242), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.76 ms  http: 403  http: 403
 3  213.219.206.145  11.36 ms  http: 403  http: 403
 4  213.248.3.239  1.41 ms  http: 403  http: 403
 5  213.248.7.91  1.28 ms  http: 403  http: 403
 6  80.81.195.39  178.66 ms  http: 403  http: 403
 7  115.160.187.54  178.64 ms  http: 403  http: 403
 8  10.104.131.158  178.34 ms  http: 403  http: 403
 9  59.152.252.196  182.87 ms  http: 403  http: 403
10  59.152.252.242  183.22 ms  http: 403  http: 403


Traceroute to Singapore, China CT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 203.215.233.1 (203.215.233.1), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.70 ms  http: 403  http: 403
 3  212.8.232.225  1.67 ms  http: 403  http: 403
 4  62.76.88.188  1.31 ms  http: 403  http: 403
 5  178.176.152.166  20.47 ms  http: 403  http: 403
 6  83.169.204.130  37.18 ms  http: 403  http: 403
 7  83.169.204.126  35.43 ms  http: 403  http: 403
 8  37.29.109.98  42.73 ms  http: 403  http: 403
 9  37.29.109.98  43.28 ms  http: 403  http: 403
10  203.215.233.1  193.44 ms  http: 403  http: 403


Traceroute to Singapore, China CT CN2 (TCP Mode, Max 30 Hop)
============================================================
traceroute to 183.91.61.1 (183.91.61.1), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.57 ms  http: 403  http: 403
 3  212.8.232.225  1.76 ms  http: 403  http: 403
 4  62.76.88.188  2.68 ms  http: 403  http: 403
 5  212.188.44.138  11.08 ms  http: 403  http: 403
 6  195.34.59.106  158.76 ms  http: 403  http: 403
 7  212.188.28.149  157.24 ms  http: 403  http: 403
 8  212.188.42.130  35.17 ms  http: 403  http: 403
 9  212.188.42.130  33.77 ms  http: 403  http: 403
10  212.188.2.2  162.62 ms  http: 403  http: 403
11  212.188.29.138  157.50 ms  http: 403  http: 403
12  212.188.29.138  158.24 ms  http: 403  http: 403
13  212.188.28.213  157.51 ms  http: 403  http: 403
14  212.188.2.106  100.24 ms  http: 403  http: 403
15  195.34.59.248  157.98 ms  http: 403  http: 403
16  123.255.91.41  142.05 ms  http: 403  http: 403
17  218.188.104.54  245.26 ms  http: 403  http: 403
18  59.43.249.241  294.44 ms  http: 403  http: 403
19  183.91.61.1  278.89 ms  http: 403  http: 403


Traceroute to Singapore, Singtel (TCP Mode, Max 30 Hop)
============================================================
traceroute to 118.201.1.11 (118.201.1.11), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.82 ms  http: 403  http: 403
 3  31.28.19.100  1.17 ms  http: 403  http: 403
 4  80.81.194.26  43.63 ms  http: 403  http: 403
 5  *
 6  64.125.29.54  50.46 ms  http: 403  http: 403
 7  *
 8  *
 9  *
10  64.125.27.241  50.71 ms  http: 403  http: 403
11  213.161.72.106  193.03 ms  http: 403  http: 403
12  203.208.166.249  206.68 ms  http: 403  http: 403
13  203.208.153.246  186.20 ms  http: 403  http: 403
14  203.208.182.254  186.20 ms  http: 403  http: 403
15  203.208.177.214  185.89 ms  http: 403  http: 403
16  203.208.172.214  190.09 ms  http: 403  http: 403
17  165.21.138.86  187.11 ms  http: 403  http: 403
18  165.21.138.86  190.80 ms  http: 403  http: 403
19  165.21.138.70  209.19 ms  http: 403  http: 403
20  165.21.49.126  207.22 ms  http: 403  http: 403
21  165.21.49.126  209.87 ms  http: 403  http: 403
22  203.125.232.130  190.68 ms  http: 403  http: 403
23  118.201.1.11  198.85 ms  http: 403  http: 403


Traceroute to Singapore, StarHub (TCP Mode, Max 30 Hop)
============================================================
traceroute to 203.116.46.33 (203.116.46.33), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.52 ms  http: 403  http: 403
 3  212.8.232.225  1.51 ms  http: 403  http: 403
 4  178.18.224.229  22.53 ms  http: 403  http: 403
 5  184.104.192.81  22.32 ms  http: 403  http: 403
 6  184.105.65.13  189.33 ms  http: 403  http: 403
 7  *
 8  27.50.36.182  171.60 ms  http: 403  http: 403
 9  61.8.243.1  172.16 ms  http: 403  http: 403
10  61.8.243.1  174.04 ms  http: 403  http: 403
11  203.116.46.33  172.61 ms  http: 403  http: 403


Traceroute to Singapore, M1 (TCP Mode, Max 30 Hop)
============================================================
traceroute to 118.189.184.1 (118.189.184.1), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.43 ms  http: 403  http: 403
 3  194.186.66.33  2.91 ms  http: 403  http: 403
 4  79.104.235.74  41.84 ms  http: 403  http: 403
 5  217.161.65.145  54.85 ms  http: 403  http: 403
 6  195.2.8.202  207.91 ms  http: 403  http: 403
 7  195.2.25.189  53.65 ms  http: 403  http: 403
 8  203.169.57.182  189.86 ms  http: 403  http: 403
 9  203.169.57.182  189.11 ms  http: 403  http: 403
10  202.65.246.186  202.80 ms  http: 403  http: 403
11  202.65.246.186  211.92 ms  http: 403  http: 403
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
 1  *
 2  185.188.180.89  15.55 ms  http: 403  http: 403
 3  87.245.253.26  0.80 ms  http: 403  http: 403
 4  87.245.234.154  161.44 ms  http: 403  http: 403
 5  87.245.240.221  189.79 ms  http: 403  http: 403
 6  203.211.159.149  191.65 ms  http: 403  http: 403
 7  129.126.64.122  175.88 ms  http: 403  http: 403
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


Traceroute to Singapore, AWS (TCP Mode, Max 30 Hop)
============================================================
traceroute to 13.228.0.251 (13.228.0.251), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.57 ms  http: 403  http: 403
 3  92.63.203.78  0.84 ms  http: 403  http: 403
 4  92.63.203.104  1.09 ms  http: 403  http: 403
 5  193.106.112.103  18.97 ms  http: 403  http: 403
 6  188.43.228.198  28.61 ms  http: 403  http: 403
 7  *
 8  *
 9  *
10  *
11  217.150.55.235  139.45 ms  http: 403  http: 403
12  218.100.6.207  196.25 ms  http: 403  http: 403
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  52.93.8.62  193.92 ms  http: 403  http: 403
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  13.228.0.251  200.03 ms  http: 403  http: 403


Traceroute to Japan, NTT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 61.213.155.84 (61.213.155.84), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.66 ms  http: 403  http: 403
 3  213.219.206.145  1.34 ms  http: 403  http: 403
 4  213.248.1.208  1.74 ms  http: 403  http: 403
 5  81.211.5.145  12.39 ms  http: 403  http: 403
 6  79.104.225.38  19.82 ms  http: 403  http: 403
 7  *
 8  *
 9  129.250.9.49  20.79 ms  http: 403  http: 403
10  129.250.3.68  40.12 ms  http: 403  http: 403
11  129.250.7.37  44.10 ms  http: 403  http: 403
12  129.250.4.138  58.44 ms  http: 403  http: 403
13  129.250.6.177  169.51 ms  http: 403  http: 403
14  129.250.6.16  119.79 ms  http: 403  http: 403
15  129.250.6.177  177.17 ms  http: 403  http: 403
16  129.250.5.77  311.87 ms  http: 403  http: 403
17  129.250.3.22  312.35 ms  http: 403  http: 403
18  61.213.179.34  303.71 ms  http: 403  http: 403
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
 1  *
 2  185.188.180.89  0.61 ms  http: 403  http: 403
 3  109.239.134.45  1.76 ms  http: 403  http: 403
 4  91.108.51.6  22.72 ms  http: 403  http: 403
 5  213.242.69.189  41.64 ms  http: 403  http: 403
 6  *
 7  210.130.133.37  241.88 ms  http: 403  http: 403
 8  58.138.98.133  235.83 ms  http: 403  http: 403
 9  58.138.101.10  213.43 ms  http: 403  http: 403
10  210.130.142.114  236.53 ms  http: 403  http: 403
11  202.232.15.70  213.54 ms  http: 403  http: 403


Traceroute to Japan, SoftBank (TCP Mode, Max 30 Hop)
============================================================
traceroute to 210.175.32.26 (210.175.32.26), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.63 ms  http: 403  http: 403
 3  194.186.66.33  2.93 ms  http: 403  http: 403
 4  79.104.235.78  24.81 ms  http: 403  http: 403
 5  195.89.102.45  19.77 ms  http: 403  http: 403
 6  195.2.16.34  39.43 ms  http: 403  http: 403
 7  195.2.28.178  232.99 ms  http: 403  http: 403
 8  195.2.28.178  233.00 ms  http: 403  http: 403
 9  221.111.202.165  229.90 ms  http: 403  http: 403
10  *
11  *
12  143.90.232.241  204.72 ms  http: 403  http: 403
13  143.90.47.9  231.08 ms  http: 403  http: 403
14  143.90.161.50  235.52 ms  http: 403  http: 403
15  143.90.54.30  207.48 ms  http: 403  http: 403
16  143.90.54.30  204.29 ms  http: 403  http: 403
17  210.175.32.123  205.58 ms  http: 403  http: 403
18  210.175.32.26  206.05 ms  http: 403  http: 403


Traceroute to Japan, KDDI (TCP Mode, Max 30 Hop)
============================================================
traceroute to 106.162.242.108 (106.162.242.108), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  11.90 ms  http: 403  http: 403
 3  109.239.134.45  3.08 ms  http: 403  http: 403
 4  91.108.51.6  22.64 ms  http: 403  http: 403
 5  213.242.69.189  31.55 ms  http: 403  http: 403
 6  *
 7  4.7.26.70  183.77 ms  http: 403  http: 403
 8  203.181.106.181  182.10 ms  http: 403  http: 403
 9  106.187.12.13  296.52 ms  http: 403  http: 403
10  27.85.133.226  283.90 ms  http: 403  http: 403
11  111.87.220.242  285.16 ms  http: 403  http: 403
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
 1  *
 2  185.188.180.89  0.50 ms  http: 403  http: 403
 3  212.8.232.225  3.84 ms  http: 403  http: 403
 4  62.76.88.188  2.40 ms  http: 403  http: 403
 5  178.176.152.166  16.15 ms  http: 403  http: 403
 6  83.169.204.112  36.39 ms  http: 403  http: 403
 7  *
 8  37.29.109.98  44.00 ms  http: 403  http: 403
 9  37.29.109.98  44.13 ms  http: 403  http: 403
10  202.97.24.34  283.59 ms  http: 403  http: 403
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
 1  *
 2  185.188.180.89  0.72 ms  http: 403  http: 403
 3  31.28.19.184  11.73 ms  http: 403  http: 403
 4  62.115.135.108  11.31 ms  http: 403  http: 403
 5  62.115.141.22  34.14 ms  http: 403  http: 403
 6  62.115.134.94  44.11 ms  http: 403  http: 403
 7  80.91.249.10  44.56 ms  http: 403  http: 403
 8  62.115.120.239  42.37 ms  http: 403  http: 403
 9  80.239.193.226  49.52 ms  http: 403  http: 403
10  59.43.246.205  262.63 ms  http: 403  http: 403
11  59.43.183.54  270.04 ms  http: 403  http: 403
12  202.55.27.4  269.59 ms  http: 403  http: 403


Traceroute to Japan, Amazon AWS (TCP Mode, Max 30 Hop)
============================================================
traceroute to 13.112.63.251 (13.112.63.251), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.47 ms  http: 403  http: 403
 3  213.219.206.145  1.41 ms  http: 403  http: 403
 4  213.248.3.239  1.55 ms  http: 403  http: 403
 5  212.188.44.169  15.15 ms  http: 403  http: 403
 6  212.188.42.126  3.25 ms  http: 403  http: 403
 7  212.188.28.149  158.66 ms  http: 403  http: 403
 8  212.188.29.26  157.63 ms  http: 403  http: 403
 9  212.188.42.130  32.33 ms  http: 403  http: 403
10  195.34.50.154  54.00 ms  http: 403  http: 403
11  212.188.2.2  182.26 ms  http: 403  http: 403
12  212.188.29.138  157.09 ms  http: 403  http: 403
13  212.188.28.213  158.06 ms  http: 403  http: 403
14  212.188.2.106  102.03 ms  http: 403  http: 403
15  195.34.59.248  157.67 ms  http: 403  http: 403
16  123.255.91.218  145.88 ms  http: 403  http: 403
17  52.93.35.70  147.54 ms  http: 403  http: 403
18  52.93.35.147  147.57 ms  http: 403  http: 403
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  54.240.229.211  240.33 ms  http: 403  http: 403
27  *
28  *
29  *
30  52.95.31.196  265.65 ms  http: 403  http: 403


Traceroute to South Korea, KT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 210.114.41.101 (210.114.41.101), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.95 ms  http: 403  http: 403
 3  194.186.66.33  1.96 ms  http: 403  http: 403
 4  79.104.235.120  125.87 ms  http: 403  http: 403
 5  36.255.57.8  183.79 ms  http: 403  http: 403
 6  112.174.88.114  220.44 ms  http: 403  http: 403
 7  112.174.86.9  252.98 ms  http: 403  http: 403
 8  *
 9  112.174.60.38  252.48 ms  http: 403  http: 403
10  112.188.245.242  250.48 ms  http: 403  http: 403
11  220.90.203.10  246.31 ms  http: 403  http: 403
12  211.37.130.73  249.36 ms  http: 403  http: 403
13  211.37.137.22  257.56 ms  http: 403  http: 403
14  210.114.41.101  248.30 ms  http: 403  http: 403


Traceroute to South Korea, SK (TCP Mode, Max 30 Hop)
============================================================
traceroute to 175.122.253.62 (175.122.253.62), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.52 ms  http: 403  http: 403
 3  194.186.66.33  14.89 ms  http: 403  http: 403
 4  79.104.235.74  66.28 ms  http: 403  http: 403
 5  80.81.197.60  195.70 ms  http: 403  http: 403
 6  1.255.74.194  262.56 ms  http: 403  http: 403
 7  1.255.76.110  278.16 ms  http: 403  http: 403
 8  *
 9  *
10  *
11  175.122.253.62  289.07 ms  http: 403  http: 403


Traceroute to South Korea, LG (TCP Mode, Max 30 Hop)
============================================================
traceroute to 211.174.62.44 (211.174.62.44), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.59 ms  http: 403  http: 403
 3  194.186.66.33  6.67 ms  http: 403  http: 403
 4  *
 5  *
 6  4.69.219.45  177.92 ms  http: 403  http: 403
 7  4.68.111.74  183.96 ms  http: 403  http: 403
 8  1.208.112.145  176.43 ms  http: 403  http: 403
 9  1.208.164.181  234.98 ms  http: 403  http: 403
10  1.208.112.166  243.19 ms  http: 403  http: 403
11  61.42.202.130  241.03 ms  http: 403  http: 403
12  1.208.164.94  229.36 ms  http: 403  http: 403
13  *
14  *
15  *
16  211.174.62.44  240.74 ms  http: 403  http: 403


Traceroute to South Korea, China CT CN2 (TCP Mode, Max 30 Hop)
============================================================
traceroute to 218.185.246.3 (218.185.246.3), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.72 ms  http: 403  http: 403
 3  109.239.134.45  1.53 ms  http: 403  http: 403
 4  91.108.51.7  55.46 ms  http: 403  http: 403
 5  80.81.193.79  73.42 ms  http: 403  http: 403
 6  202.84.178.65  59.19 ms  http: 403  http: 403
 7  202.84.143.158  211.54 ms  http: 403  http: 403
 8  202.84.140.141  226.73 ms  http: 403  http: 403
 9  202.84.224.197  216.42 ms  http: 403  http: 403
10  202.84.224.190  213.34 ms  http: 403  http: 403
11  59.43.249.194  295.80 ms  http: 403  http: 403
12  59.43.184.25  318.49 ms  http: 403  http: 403
13  218.185.246.3  314.61 ms  http: 403  http: 403


Traceroute to South Korea, Amazon AWS (TCP Mode, Max 30 Hop)
============================================================
traceroute to 13.124.63.251 (13.124.63.251), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.71 ms  http: 403  http: 403
 3  212.8.232.225  2.11 ms  http: 403  http: 403
 4  62.76.88.188  1.65 ms  http: 403  http: 403
 5  212.188.44.32  19.85 ms  http: 403  http: 403
 6  195.34.59.106  20.03 ms  http: 403  http: 403
 7  212.188.2.53  14.17 ms  http: 403  http: 403
 8  212.188.29.109  19.82 ms  http: 403  http: 403
 9  62.67.19.237  23.47 ms  http: 403  http: 403
10  *
11  130.117.50.225  44.52 ms  http: 403  http: 403
12  129.250.3.68  43.61 ms  http: 403  http: 403
13  154.54.61.221  44.38 ms  http: 403  http: 403
14  129.250.4.182  301.56 ms  http: 403  http: 403
15  129.250.4.134  280.06 ms  http: 403  http: 403
16  *
17  *
18  154.18.19.162  202.05 ms  http: 403  http: 403
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


Traceroute to China, Taiwan Chief (TCP Mode, Max 30 Hop)
============================================================
traceroute to 202.133.242.116 (202.133.242.116), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.70 ms  http: 403  http: 403
 3  194.186.66.33  1.96 ms  http: 403  http: 403
 4  79.104.235.66  42.02 ms  http: 403  http: 403
 5  80.81.196.65  204.00 ms  http: 403  http: 403
 6  220.128.6.202  240.04 ms  http: 403  http: 403
 7  220.128.7.70  252.57 ms  http: 403  http: 403
 8  220.128.1.69  248.27 ms  http: 403  http: 403
 9  203.75.228.153  254.16 ms  http: 403  http: 403
10  103.123.252.9  253.30 ms  http: 403  http: 403
11  113.21.95.72  245.37 ms  http: 403  http: 403
12  103.123.254.38  245.37 ms  http: 403  http: 403
13  202.133.242.114  241.01 ms  http: 403  http: 403
14  202.133.242.116  245.33 ms  http: 403  http: 403


Traceroute to China, Taiwan APTG (TCP Mode, Max 30 Hop)
============================================================
traceroute to 210.200.69.90 (210.200.69.90), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.57 ms  http: 403  http: 403
 3  109.239.134.45  1.24 ms  http: 403  http: 403
 4  91.108.51.7  55.41 ms  http: 403  http: 403
 5  80.81.193.79  84.33 ms  http: 403  http: 403
 6  202.84.178.65  59.79 ms  http: 403  http: 403
 7  202.84.249.174  133.46 ms  http: 403  http: 403
 8  202.84.141.229  129.67 ms  http: 403  http: 403
 9  202.40.148.106  289.25 ms  http: 403  http: 403
10  202.84.140.225  293.80 ms  http: 403  http: 403
11  202.84.141.2  333.15 ms  http: 403  http: 403
12  202.84.143.6  331.51 ms  http: 403  http: 403
13  202.84.137.253  322.47 ms  http: 403  http: 403
14  210.176.44.14  332.11 ms  http: 403  http: 403
15  210.176.44.78  336.93 ms  http: 403  http: 403
16  211.76.100.61  328.90 ms  http: 403  http: 403
17  211.76.100.53  329.37 ms  http: 403  http: 403
18  210.200.69.90  335.81 ms  http: 403  http: 403


Traceroute to China, Taiwan CHT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 203.75.129.162 (203.75.129.162), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.52 ms  http: 403  http: 403
 3  212.8.232.225  1.68 ms  http: 403  http: 403
 4  62.76.88.188  1.60 ms  http: 403  http: 403
 5  178.176.152.166  20.90 ms  http: 403  http: 403
 6  83.169.204.112  35.89 ms  http: 403  http: 403
 7  83.169.204.124  35.78 ms  http: 403  http: 403
 8  80.81.196.65  197.08 ms  http: 403  http: 403
 9  220.128.6.202  264.94 ms  http: 403  http: 403
10  220.128.6.202  235.14 ms  http: 403  http: 403
11  220.128.1.225  246.99 ms  http: 403  http: 403
12  211.22.229.45  238.60 ms  http: 403  http: 403
13  1.1.1.2  239.48 ms  http: 403  http: 403
14  *
15  *
16  203.75.129.162  241.15 ms  http: 403  http: 403


Traceroute to China, Taiwan TFN (TCP Mode, Max 30 Hop)
============================================================
traceroute to 219.87.66.3 (219.87.66.3), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.57 ms  http: 403  http: 403
 3  194.186.66.33  3.78 ms  http: 403  http: 403
 4  79.104.235.78  18.93 ms  http: 403  http: 403
 5  *
 6  *
 7  4.79.238.26  185.36 ms  http: 403  http: 403
 8  60.199.20.33  318.61 ms  http: 403  http: 403
 9  60.199.18.10  323.72 ms  http: 403  http: 403
10  60.199.28.6  335.70 ms  http: 403  http: 403
11  60.199.28.6  337.88 ms  http: 403  http: 403
12  219.87.66.3  337.03 ms  http: 403  http: 403


Traceroute to China,Taiwan FET (TCP Mode, Max 30 Hop)
============================================================
traceroute to 211.73.144.38 (211.73.144.38), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.63 ms  http: 403  http: 403
 3  87.245.253.26  24.38 ms  http: 403  http: 403
 4  87.245.232.78  145.05 ms  http: 403  http: 403
 5  87.245.240.49  145.62 ms  http: 403  http: 403
 6  192.72.155.209  233.43 ms  http: 403  http: 403
 7  192.72.155.98  234.28 ms  http: 403  http: 403
 8  *
 9  *
10  *
11  211.73.144.38  249.39 ms  http: 403  http: 403


Traceroute to China, Taiwan KBT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 61.63.0.102 (61.63.0.102), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  5.80 ms  http: 403  http: 403
 3  194.186.66.33  7.11 ms  http: 403  http: 403
 4  79.104.235.70  18.81 ms  http: 403  http: 403
 5  *
 6  4.69.209.157  222.05 ms  http: 403  http: 403
 7  4.28.172.138  182.36 ms  http: 403  http: 403
 8  175.41.58.49  308.06 ms  http: 403  http: 403
 9  175.41.61.174  307.97 ms  http: 403  http: 403
10  203.160.226.150  309.77 ms  http: 403  http: 403
11  *
12  203.187.9.226  305.21 ms  http: 403  http: 403
13  58.86.1.174  306.14 ms  http: 403  http: 403
14  61.63.63.6  361.40 ms  http: 403  http: 403
15  58.86.0.206  308.14 ms  http: 403  http: 403
16  61.63.0.123  307.12 ms  http: 403  http: 403
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


Traceroute to China, Taiwan TAIFO (TCP Mode, Max 30 Hop)
============================================================
traceroute to 103.31.196.203 (103.31.196.203), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.62 ms  http: 403  http: 403
 3  213.219.206.145  2.08 ms  http: 403  http: 403
 4  213.248.3.239  1.46 ms  http: 403  http: 403
 5  213.248.7.91  18.45 ms  http: 403  http: 403
 6  80.81.196.65  199.61 ms  http: 403  http: 403
 7  220.128.6.202  239.89 ms  http: 403  http: 403
 8  220.128.7.70  250.93 ms  http: 403  http: 403
 9  220.128.2.69  241.45 ms  http: 403  http: 403
10  210.242.214.5  239.13 ms  http: 403  http: 403
11  *
12  103.31.197.66  241.71 ms  http: 403  http: 403
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


Traceroute to United States, Los Angeles China CT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 218.30.33.17 (218.30.33.17), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.58 ms  http: 403  http: 403
 3  92.63.203.78  1.06 ms  http: 403  http: 403
 4  92.63.203.104  1.25 ms  http: 403  http: 403
 5  193.106.112.103  2.31 ms  http: 403  http: 403
 6  188.43.228.198  17.56 ms  http: 403  http: 403
 7  *
 8  *
 9  218.30.33.17  129.14 ms  http: 403  http: 403


Traceroute to United States, Los Angeles China CT CN2 (TCP Mode, Max 30 Hop)
============================================================
traceroute to 66.102.252.100 (66.102.252.100), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.70 ms  http: 403  http: 403
 3  212.8.232.225  1.53 ms  http: 403  http: 403
 4  62.76.88.188  1.47 ms  http: 403  http: 403
 5  212.188.44.138  19.96 ms  http: 403  http: 403
 6  212.188.42.126  1.64 ms  http: 403  http: 403
 7  212.188.28.149  188.29 ms  http: 403  http: 403
 8  212.188.2.189  36.75 ms  http: 403  http: 403
 9  195.34.53.226  182.19 ms  http: 403  http: 403
10  212.188.28.130  180.50 ms  http: 403  http: 403
11  206.72.211.165  170.66 ms  http: 403  http: 403
12  66.102.252.100  170.63 ms  http: 403  http: 403


Traceroute to United States, Los Angeles PCCW (TCP Mode, Max 30 Hop)
============================================================
traceroute to 63.218.42.81 (63.218.42.81), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.59 ms  http: 403  http: 403
 3  194.186.66.33  6.76 ms  http: 403  http: 403
 4  *
 5  *
 6  *
 7  63.222.68.1  49.48 ms  http: 403  http: 403
 8  63.218.42.81  190.13 ms  http: 403  http: 403


Traceroute to United States, Los Angeles HE (TCP Mode, Max 30 Hop)
============================================================
traceroute to 66.220.18.42 (66.220.18.42), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.48 ms  http: 403  http: 403
 3  185.1.160.117  17.01 ms  http: 403  http: 403
 4  184.104.192.93  17.94 ms  http: 403  http: 403
 5  184.104.192.81  24.45 ms  http: 403  http: 403
 6  184.104.194.222  31.67 ms  http: 403  http: 403
 7  *
 8  184.104.195.161  113.89 ms  http: 403  http: 403
 9  72.52.92.225  114.02 ms  http: 403  http: 403
10  184.105.80.202  168.68 ms  http: 403  http: 403
11  66.220.18.42  193.44 ms  http: 403  http: 403


Traceroute to United States, Los Angeles GTT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 173.205.77.98 (173.205.77.98), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  1.25 ms  http: 403  http: 403
 3  92.63.203.78  0.71 ms  http: 403  http: 403
 4  92.63.203.110  3.28 ms  http: 403  http: 403
 5  188.234.76.196  1.39 ms  http: 403  http: 403
 6  62.115.12.109  9.87 ms  http: 403  http: 403
 7  62.115.142.176  13.22 ms  http: 403  http: 403
 8  62.115.141.22  19.82 ms  http: 403  http: 403
 9  62.115.141.22  20.04 ms  http: 403  http: 403
10  80.91.254.91  167.19 ms  http: 403  http: 403
11  62.115.136.201  109.42 ms  http: 403  http: 403
12  62.115.137.39  167.65 ms  http: 403  http: 403
13  62.115.137.39  165.18 ms  http: 403  http: 403
14  23.203.155.191  192.82 ms  http: 403  http: 403
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
 1  *
 2  185.188.180.89  1.32 ms  http: 403  http: 403
 3  194.186.66.33  2.10 ms  http: 403  http: 403
 4  79.104.235.70  20.55 ms  http: 403  http: 403
 5  *
 6  *
 7  4.68.62.34  121.44 ms  http: 403  http: 403
 8  12.122.131.102  183.14 ms  http: 403  http: 403
 9  12.122.2.237  185.40 ms  http: 403  http: 403
10  12.122.2.53  184.59 ms  http: 403  http: 403
11  12.122.1.174  188.33 ms  http: 403  http: 403
12  12.122.110.13  188.89 ms  http: 403  http: 403
13  12.244.156.30  188.42 ms  http: 403  http: 403
14  12.169.215.33  186.76 ms  http: 403  http: 403


Traceroute to United States, New York TATA (TCP Mode, Max 30 Hop)
============================================================
traceroute to 66.198.181.100 (66.198.181.100), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.82 ms  http: 403  http: 403
 3  31.28.19.184  11.32 ms  http: 403  http: 403
 4  62.115.135.108  11.23 ms  http: 403  http: 403
 5  62.115.143.24  20.81 ms  http: 403  http: 403
 6  62.115.143.29  39.29 ms  http: 403  http: 403
 7  62.115.124.117  39.06 ms  http: 403  http: 403
 8  213.248.82.41  37.80 ms  http: 403  http: 403
 9  195.219.87.2  113.91 ms  http: 403  http: 403
10  195.219.194.149  113.66 ms  http: 403  http: 403
11  195.219.194.6  118.76 ms  http: 403  http: 403
12  80.231.131.160  113.90 ms  http: 403  http: 403
13  80.231.131.2  113.52 ms  http: 403  http: 403
14  80.231.130.26  117.60 ms  http: 403  http: 403
15  216.6.57.6  120.55 ms  http: 403  http: 403
16  64.86.62.25  115.66 ms  http: 403  http: 403
17  209.58.75.217  120.22 ms  http: 403  http: 403
18  209.58.75.198  118.69 ms  http: 403  http: 403
19  *
20  66.198.181.100  118.86 ms  http: 403  http: 403


Traceroute to United States, San Jose China CT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 218.30.33.17 (218.30.33.17), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.56 ms  http: 403  http: 403
 3  92.63.203.78  0.68 ms  http: 403  http: 403
 4  92.63.203.104  0.88 ms  http: 403  http: 403
 5  193.106.112.103  16.22 ms  http: 403  http: 403
 6  188.43.228.198  32.23 ms  http: 403  http: 403
 7  *
 8  *
 9  218.30.33.17  125.40 ms  http: 403  http: 403


Traceroute to United States, San Jose NTT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 23.11.26.62 (23.11.26.62), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.82 ms  http: 403  http: 403
 3  194.186.66.33  2.36 ms  http: 403  http: 403
 4  79.104.235.74  45.58 ms  http: 403  http: 403
 5  212.162.40.253  71.30 ms  http: 403  http: 403
 6  4.69.162.181  45.14 ms  http: 403  http: 403
 7  212.72.47.190  39.72 ms  http: 403  http: 403
 8  23.210.55.36  50.33 ms  http: 403  http: 403
 9  95.100.192.136  53.62 ms  http: 403  http: 403
10  *
11  23.32.63.18  150.87 ms  http: 403  http: 403
12  23.32.63.45  143.85 ms  http: 403  http: 403
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


Traceroute to United States, Fremont HE (TCP Mode, Max 30 Hop)
============================================================
traceroute to 72.52.104.74 (72.52.104.74), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.45 ms  http: 403  http: 403
 3  185.1.160.117  17.48 ms  http: 403  http: 403
 4  184.104.192.93  17.21 ms  http: 403  http: 403
 5  184.104.192.81  28.26 ms  http: 403  http: 403
 6  184.104.194.222  32.02 ms  http: 403  http: 403
 7  184.104.196.98  107.55 ms  http: 403  http: 403
 8  184.104.195.165  109.03 ms  http: 403  http: 403
 9  184.105.213.217  109.12 ms  http: 403  http: 403
10  184.104.195.170  109.28 ms  http: 403  http: 403
11  184.105.81.61  173.90 ms  http: 403  http: 403
12  72.52.104.74  173.74 ms  http: 403  http: 403


Traceroute to United States, Las Vegas Level3 (TCP Mode, Max 30 Hop)
============================================================
traceroute to 205.216.62.38 (205.216.62.38), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.66 ms  http: 403  http: 403
 3  92.63.203.78  0.70 ms  http: 403  http: 403
 4  92.63.203.96  0.86 ms  http: 403  http: 403
 5  109.239.138.169  19.08 ms  http: 403  http: 403
 6  91.108.51.6  22.10 ms  http: 403  http: 403
 7  213.242.69.189  20.40 ms  http: 403  http: 403
 8  4.69.209.78  119.48 ms  http: 403  http: 403
 9  4.68.110.154  116.59 ms  http: 403  http: 403
10  67.14.54.174  154.63 ms  http: 403  http: 403
11  216.34.172.42  155.03 ms  http: 403  http: 403
12  216.39.66.4  158.76 ms  http: 403  http: 403
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
 1  *
 2  185.188.180.89  0.77 ms  http: 403  http: 403
 3  92.63.203.78  0.76 ms  http: 403  http: 403
 4  92.63.203.110  1.71 ms  http: 403  http: 403
 5  193.106.112.103  19.35 ms  http: 403  http: 403
 6  188.43.228.198  1.84 ms  http: 403  http: 403
 7  *
 8  *
 9  *
10  64.125.29.54  118.16 ms  http: 403  http: 403
11  *
12  *
13  *
14  *
15  64.125.29.126  121.06 ms  http: 403  http: 403
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
 1  *
 2  185.188.180.89  0.53 ms  http: 403  http: 403
 3  212.8.232.225  1.70 ms  http: 403  http: 403
 4  62.76.88.188  1.58 ms  http: 403  http: 403
 5  178.176.152.166  2.23 ms  http: 403  http: 403
 6  83.169.204.128  47.56 ms  http: 403  http: 403
 7  83.169.204.126  35.28 ms  http: 403  http: 403
 8  *
 9  154.54.37.29  43.49 ms  http: 403  http: 403
10  154.54.58.234  75.55 ms  http: 403  http: 403
11  154.54.58.234  50.14 ms  http: 403  http: 403
12  154.54.85.245  125.32 ms  http: 403  http: 403
13  154.54.46.194  126.97 ms  http: 403  http: 403
14  38.140.164.58  125.80 ms  http: 403  http: 403
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
 1  *
 2  185.188.180.89  0.47 ms  http: 403  http: 403
 3  87.245.228.33  2.11 ms  http: 403  http: 403
 4  87.245.232.244  34.47 ms  http: 403  http: 403
 5  80.156.160.125  48.87 ms  http: 403  http: 403
 6  80.156.162.165  36.93 ms  http: 403  http: 403
 7  87.137.218.29  41.64 ms  http: 403  http: 403
 8  80.146.191.1  46.15 ms  http: 403  http: 403


Traceroute to German, Frankfurt O2 (TCP Mode, Max 30 Hop)
============================================================
traceroute to 82.113.108.25 (82.113.108.25), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.53 ms  http: 403  http: 403
 3  194.186.66.33  5.65 ms  http: 403  http: 403
 4  79.104.235.74  42.15 ms  http: 403  http: 403
 5  80.81.192.89  64.53 ms  http: 403  http: 403
 6  62.53.10.50  39.89 ms  http: 403  http: 403
 7  62.53.28.150  40.06 ms  http: 403  http: 403
 8  62.53.2.51  39.85 ms  http: 403  http: 403
 9  62.53.236.53  45.97 ms  http: 403  http: 403
10  82.113.108.25  43.27 ms  http: 403  http: 403


Traceroute to German, Frankfurt Vodafone (TCP Mode, Max 30 Hop)
============================================================
traceroute to 139.7.146.11 (139.7.146.11), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  1.99 ms  http: 403  http: 403
 3  109.239.134.45  1.61 ms  http: 403  http: 403
 4  91.108.51.8  46.98 ms  http: 403  http: 403
 5  80.249.209.123  59.86 ms  http: 403  http: 403
 6  *
 7  145.253.5.57  47.64 ms  http: 403  http: 403
 8  92.79.230.2  46.24 ms  http: 403  http: 403
 9  139.7.148.84  49.10 ms  http: 403  http: 403
10  *
11  *
12  *
13  *
14  139.7.146.11  49.30 ms  http: 403  http: 403


Traceroute to German, Frankfurt China CT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 118.85.205.101 (118.85.205.101), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.50 ms  http: 403  http: 403
 3  92.63.203.78  0.61 ms  http: 403  http: 403
 4  92.63.203.110  0.85 ms  http: 403  http: 403
 5  193.106.112.103  19.26 ms  http: 403  http: 403
 6  188.43.228.198  28.89 ms  http: 403  http: 403
 7  *
 8  *
 9  118.85.205.101  46.98 ms  http: 403  http: 403


Traceroute to German, Frankfurt China CT CN2 (TCP Mode, Max 30 Hop)
============================================================
traceroute to 5.10.138.33 (5.10.138.33), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.71 ms  http: 403  http: 403
 3  212.8.232.225  1.68 ms  http: 403  http: 403
 4  62.76.88.188  1.57 ms  http: 403  http: 403
 5  212.188.44.138  20.50 ms  http: 403  http: 403
 6  212.188.42.126  1.96 ms  http: 403  http: 403
 7  212.188.2.53  14.36 ms  http: 403  http: 403
 8  212.188.2.53  14.73 ms  http: 403  http: 403
 9  62.115.151.194  27.25 ms  http: 403  http: 403
10  62.115.123.30  22.25 ms  http: 403  http: 403
11  62.115.123.30  22.57 ms  http: 403  http: 403
12  62.115.122.161  44.77 ms  http: 403  http: 403
13  62.115.120.239  44.68 ms  http: 403  http: 403
14  80.239.193.226  49.47 ms  http: 403  http: 403
15  *
16  5.10.138.33  49.37 ms  http: 403  http: 403


Traceroute to German, Frankfurt GTT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 213.200.65.70 (213.200.65.70), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.53 ms  http: 403  http: 403
 3  92.63.203.78  0.84 ms  http: 403  http: 403
 4  92.63.203.110  0.92 ms  http: 403  http: 403
 5  87.245.229.68  15.40 ms  http: 403  http: 403
 6  87.245.232.244  35.83 ms  http: 403  http: 403
 7  154.14.40.233  43.02 ms  http: 403  http: 403
 8  213.200.115.161  42.56 ms  http: 403  http: 403
 9  213.200.65.70  40.65 ms  http: 403  http: 403


Traceroute to German, FrankfurtCogentco (TCP Mode, Max 30 Hop)
============================================================
traceroute to 212.20.150.5 (212.20.150.5), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.68 ms  http: 403  http: 403
 3  194.186.66.33  1.81 ms  http: 403  http: 403
 4  79.104.225.62  68.28 ms  http: 403  http: 403
 5  149.11.202.57  60.96 ms  http: 403  http: 403
 6  154.54.61.41  41.69 ms  http: 403  http: 403
 7  130.117.0.142  51.02 ms  http: 403  http: 403
 8  154.54.56.34  50.00 ms  http: 403  http: 403
 9  212.20.150.5  51.42 ms  http: 403  http: 403


Traceroute to United Kingdom, Vodafone (TCP Mode, Max 30 Hop)
============================================================
traceroute to 194.62.232.211 (194.62.232.211), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.54 ms  http: 403  http: 403
 3  212.8.232.225  1.58 ms  http: 403  http: 403
 4  62.76.88.188  1.83 ms  http: 403  http: 403
 5  178.176.152.166  2.29 ms  http: 403  http: 403
 6  83.169.204.116  31.10 ms  http: 403  http: 403
 7  83.169.204.74  20.25 ms  http: 403  http: 403
 8  195.12.255.204  31.66 ms  http: 403  http: 403
 9  62.115.118.40  39.50 ms  http: 403  http: 403
10  *
11  80.239.193.101  40.09 ms  http: 403  http: 403
12  195.2.22.246  44.70 ms  http: 403  http: 403
13  195.2.22.246  47.36 ms  http: 403  http: 403
14  *
15  *
16  194.62.232.211  56.20 ms  http: 403  http: 403


Traceroute to United Kingdom? BT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 213.121.43.24 (213.121.43.24), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.73 ms  http: 403  http: 403
 3  213.219.206.145  1.52 ms  http: 403  http: 403
 4  213.248.1.208  1.37 ms  http: 403  http: 403
 5  213.248.7.90  1.55 ms  http: 403  http: 403
 6  212.188.44.169  1.28 ms  http: 403  http: 403
 7  *
 8  212.188.28.149  50.29 ms  http: 403  http: 403
 9  212.188.2.189  34.28 ms  http: 403  http: 403
10  195.34.53.226  48.39 ms  http: 403  http: 403
11  195.34.53.82  49.61 ms  http: 403  http: 403
12  195.66.224.10  50.65 ms  http: 403  http: 403
13  194.72.16.217  47.55 ms  http: 403  http: 403
14  217.32.170.148  56.25 ms  http: 403  http: 403
15  194.72.7.101  53.73 ms  http: 403  http: 403
16  *
17  *
18  *
19  *
20  *
21  213.121.43.24  68.15 ms  http: 403  http: 403


Traceroute to United Kingdom, London TATA (TCP Mode, Max 30 Hop)
============================================================
traceroute to 80.231.131.34 (80.231.131.34), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.50 ms  http: 403  http: 403
 3  *
 4  91.108.51.6  22.49 ms  http: 403  http: 403
 5  213.242.69.189  44.48 ms  http: 403  http: 403
 6  4.69.162.181  49.38 ms  http: 403  http: 403
 7  4.68.111.170  44.25 ms  http: 403  http: 403
 8  80.231.152.50  43.43 ms  http: 403  http: 403
 9  80.231.131.160  50.70 ms  http: 403  http: 403
10  80.231.131.34  183.46 ms  http: 403  http: 403


Traceroute to Russia, China CT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 118.85.205.181 (118.85.205.181), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.58 ms  http: 403  http: 403
 3  92.63.203.78  0.66 ms  http: 403  http: 403
 4  92.63.203.110  0.92 ms  http: 403  http: 403
 5  193.106.112.103  2.00 ms  http: 403  http: 403
 6  188.43.228.198  10.54 ms  http: 403  http: 403
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


Traceroute to Russia, China CT CN2 (TCP Mode, Max 30 Hop)
============================================================
traceroute to 185.75.173.17 (185.75.173.17), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.45 ms  http: 403  http: 403
 3  212.8.232.225  1.67 ms  http: 403  http: 403
 4  62.76.88.188  1.66 ms  http: 403  http: 403
 5  212.188.44.32  18.67 ms  http: 403  http: 403
 6  195.34.59.106  22.01 ms  http: 403  http: 403
 7  212.188.2.53  17.64 ms  http: 403  http: 403
 8  212.188.2.53  14.81 ms  http: 403  http: 403
 9  212.188.29.109  20.05 ms  http: 403  http: 403
10  62.115.123.30  21.97 ms  http: 403  http: 403
11  62.115.115.58  33.99 ms  http: 403  http: 403
12  62.115.122.161  45.79 ms  http: 403  http: 403
13  *
14  62.115.120.239  46.05 ms  http: 403  http: 403
15  *
16  185.75.173.17  48.83 ms  http: 403  http: 403


Traceroute to Russia, Moscow RT (TCP Mode, Max 30 Hop)
============================================================
traceroute to 87.226.162.77 (87.226.162.77), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.48 ms  http: 403  http: 403
 3  31.28.19.100  1.06 ms  http: 403  http: 403
 4  *
 5  185.140.151.245  3.75 ms  http: 403  http: 403
 6  87.226.140.2  1.53 ms  http: 403  http: 403
 7  10.30.254.57  2.17 ms  http: 403  http: 403
 8  87.226.162.77  1.80 ms  http: 403  http: 403


Traceroute to Russia, Moscow TTK (TCP Mode, Max 30 Hop)
============================================================
traceroute to 217.150.32.2 (217.150.32.2), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  0.73 ms  http: 403  http: 403
 3  194.186.66.33  3.58 ms  http: 403  http: 403
 4  79.104.225.57  2.11 ms  http: 403  http: 403
 5  87.229.217.102  18.97 ms  http: 403  http: 403
 6  *
 7  188.43.202.233  164.73 ms  http: 403  http: 403
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


Traceroute to Russia, Moscow MTS (TCP Mode, Max 30 Hop)
============================================================
traceroute to 195.34.32.71 (195.34.32.71), 30 hops max, 32 byte packets
 1  *
 2  185.188.180.89  8.96 ms  http: 403  http: 403
 3  31.28.19.100  1.96 ms  http: 403  http: 403
 4  195.34.38.133  1.21 ms  http: 403  http: 403
 5  195.34.53.205  16.72 ms  http: 403  http: 403
 6  212.188.28.149  3.45 ms  http: 403  http: 403
 7  212.188.56.14  2.10 ms  http: 403  http: 403
 8  195.34.53.5  2.23 ms  http: 403  http: 403
 9  195.34.32.71  2.83 ms  http: 403  http: 403


 -> Traceroute Test (IPV6)

Traceroute to China, Beijing CU IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2408:80f0:4100:2005::3 (2408:80f0:4100:2005::3), 30 hops max, 32 byte packets
 1  2a04:5200::1  1.94 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  0.94 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e0a1  36.51 ms  http: 403  http: 403
 4  2001:1900:5:2:2::5be1  45.54 ms  http: 403  http: 403
 5  2001:1900:2::3:72  35.66 ms  http: 403  http: 403
 6  *
 7  *
 8  *
 9  2001:978:2:7::196:2  284.18 ms  http: 403  http: 403
10  *
11  2408:8000:2:66d::  292.22 ms  http: 403  http: 403
12  2408:8000:2:8047::  281.50 ms  http: 403  http: 403
13  2408:8000:1100:304::3  284.75 ms  http: 403  http: 403
14  *
15  2408:8000:1f10:3d01::3  286.31 ms  http: 403  http: 403
16  2408:80f0:4100:2006::1  282.99 ms  http: 403  http: 403
17  2408:80f0:4100:2006::b  279.55 ms  http: 403  http: 403
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

Traceroute to China, Beijing CT IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2400:da00:2::29 (2400:da00:2::29), 30 hops max, 32 byte packets
 1  2a04:5200::1  0.67 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  1.63 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e0a1  35.43 ms  http: 403  http: 403
 4  2a02:2d8:1:7007:232a::1  191.40 ms  http: 403  http: 403
 5  240e:0:a::cc:5f9d  246.60 ms  http: 403  http: 403
 6  240e:0:a::c9:5e5c  246.09 ms  http: 403  http: 403
 7  *
 8  240e:1f:5000:51::3  256.63 ms  http: 403  http: 403
 9  240e:1f:5800:1c::2  248.67 ms  http: 403  http: 403
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

Traceroute to China, Beijing CM IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2409:8089:1020:50ff:1000::fd01 (2409:8089:1020:50ff:1000::fd01), 30 hops max, 32 byte packets
 1  2a04:5200::1  0.60 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  3.22 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e0a2  42.77 ms  http: 403  http: 403
 4  2001:7f8::e455:0:2  40.19 ms  http: 403  http: 403
 5  2402:4f00:2000:100::f5  38.03 ms  http: 403  http: 403
 6  2402:4f00:2000:100::20e  254.04 ms  http: 403  http: 403
 7  2409:8080:0:4:2f1:292::  253.92 ms  http: 403  http: 403
 8  2409:8080:0:1:2c1:2f1:4:0  257.00 ms  http: 403  http: 403
 9  2409:8080:0:1:203:2c1::  257.80 ms  http: 403  http: 403
10  2409:8080:1:2:203:203:2:0  256.91 ms  http: 403  http: 403
11  2409:8080:1:2:103:203::  281.68 ms  http: 403  http: 403
12  2409:8080:1:2:103:103:0:1  281.40 ms  http: 403  http: 403
13  2409:8080:0:2:103:1b1:0:1  281.59 ms  http: 403  http: 403
14  2409:8089:1020:50ff:1000::fd01  280.99 ms  http: 403  http: 403

Traceroute to China, Shanghai CU IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2408:8000:9000:20e6::b7 (2408:8000:9000:20e6::b7), 30 hops max, 32 byte packets
 1  2a04:5200::1  1.58 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  0.95 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e0a1  35.62 ms  http: 403  http: 403
 4  2001:1900:5:2:2::5be1  36.53 ms  http: 403  http: 403
 5  2001:1900:2::3:72  34.43 ms  http: 403  http: 403
 6  *
 7  2001:550:0:1000::9a19:c4d  40.56 ms  http: 403  http: 403
 8  *
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  2408:8000:9000:20e6::b7  286.24 ms  http: 403  http: 403

Traceroute to China, Shanghai CT IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 240e:18:10:a01::1 (240e:18:10:a01::1), 30 hops max, 32 byte packets
 1  2a04:5200::1  0.52 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  0.95 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e0a1  36.49 ms  http: 403  http: 403
 4  2a02:2d8:1:7007:232a::1  185.01 ms  http: 403  http: 403
 5  240e:0:a::cc:5fcc  200.42 ms  http: 403  http: 403
 6  *
 7  240e:0:a::c9:5301  207.26 ms  http: 403  http: 403
 8  240e:18:10:430e::89  207.30 ms  http: 403  http: 403
 9  240e:18:10:a01::1  207.18 ms  http: 403  http: 403

Traceroute to China, Shanghai CM IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2409:801e:5c03:2000::207 (2409:801e:5c03:2000::207), 30 hops max, 32 byte packets
 1  2a04:5200::1  0.49 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  1.12 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e0a2  42.26 ms  http: 403  http: 403
 4  2001:7f8::e455:0:2  66.76 ms  http: 403  http: 403
 5  2402:4f00:2000:100::71e  35.85 ms  http: 403  http: 403
 6  2402:4f00:2000:100::696  254.43 ms  http: 403  http: 403
 7  2409:8080:0:4:2f5:293:1:1  256.07 ms  http: 403  http: 403
 8  2409:8080:0:4:2c5:2f5:2:1  255.51 ms  http: 403  http: 403
 9  2409:8080:0:1:205:2c5::  256.02 ms  http: 403  http: 403
10  2409:8080:0:2:205:275:0:1  261.80 ms  http: 403  http: 403
11  2409:801e:f0:1::559  256.61 ms  http: 403  http: 403
12  2409:801e:5c01:2000::31  260.18 ms  http: 403  http: 403
13  *
14  2409:801e:5c03:2000::207  258.77 ms  http: 403  http: 403

Traceroute to China, Guangzhou CU IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2408:8001:3011:310::3 (2408:8001:3011:310::3), 30 hops max, 32 byte packets
 1  2a04:5200::1  0.53 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  3.74 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e0a1  35.40 ms  http: 403  http: 403
 4  2001:1900:5:2:2::5be1  40.29 ms  http: 403  http: 403
 5  2001:1900:2::3:72  34.47 ms  http: 403  http: 403
 6  *
 7  2001:550:0:1000::9a19:c4d  40.78 ms  http: 403  http: 403
 8  2001:978:2:42::11c:2  252.60 ms  http: 403  http: 403
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
 1  2a04:5200::1  0.61 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  0.86 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e0a1  36.56 ms  http: 403  http: 403
 4  2a02:2d8:1:7007:232a::1  184.65 ms  http: 403  http: 403
 5  *
 6  240e:0:a::c9:5e58  247.38 ms  http: 403  http: 403
 7  *
 8  240e:1f:5000:6d::3  250.54 ms  http: 403  http: 403
 9  240e:1f:5000:f006::2  248.60 ms  http: 403  http: 403
10  240e:1f:5807:26::3  266.56 ms  http: 403  http: 403
11  240e:ff:e02c::1  246.49 ms  http: 403  http: 403
12  240e:ff:e02c:1:21::  244.89 ms  http: 403  http: 403

Traceroute to China, Guangzhou CM IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2409:8057:5c00:30::6 (2409:8057:5c00:30::6), 30 hops max, 32 byte packets
 1  2a04:5200::1  0.54 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  34.07 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e0a2  58.15 ms  http: 403  http: 403
 4  2001:7f8::e455:0:2  40.23 ms  http: 403  http: 403
 5  2402:4f00:2000:100::f5  36.18 ms  http: 403  http: 403
 6  2402:4f00:2000:100::212  251.00 ms  http: 403  http: 403
 7  2409:8080:0:4:2f1:292::  252.46 ms  http: 403  http: 403
 8  2409:8080:0:1:2c1:2f1:3:0  255.87 ms  http: 403  http: 403
 9  2409:8080:0:1:203:2c1::  256.65 ms  http: 403  http: 403
10  2409:8080:1:2:203:203::  255.30 ms  http: 403  http: 403
11  *
12  2409:8080:1:2:301:375:1:1  287.38 ms  http: 403  http: 403
13  2409:8055:0:1309::  287.25 ms  http: 403  http: 403
14  2409:8055:1:b301::  288.64 ms  http: 403  http: 403
15  2409:8055:5c00:0:4c30::1  295.14 ms  http: 403  http: 403
16  2409:8055:5c00:0:4c00::5  296.34 ms  http: 403  http: 403
17  *
18  *
19  *
20  2409:8057:5c00:30::6  296.81 ms  http: 403  http: 403

Traceroute to China, Beijing Dr.Peng IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2403:8880:400f::2 (2403:8880:400f::2), 30 hops max, 32 byte packets
 1  2a04:5200::1  0.82 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  14.67 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e09b  20.78 ms  http: 403  http: 403
 4  2001:7f8:d:ff::187  39.58 ms  http: 403  http: 403
 5  *
 6  *
 7  2001:470:0:5cc::1  186.58 ms  http: 403  http: 403
 8  2001:470:0:2ea::1  218.29 ms  http: 403  http: 403
 9  2001:7fa:0:1::ca28:a1be  267.25 ms  http: 403  http: 403
10  2001:252:0:106::1  258.88 ms  http: 403  http: 403
11  2001:252:0:100::1  260.27 ms  http: 403  http: 403
12  2001:252:0:2::1  261.34 ms  http: 403  http: 403
13  2001:da8:2:801::2  257.24 ms  http: 403  http: 403
14  2400:a980:ff:29::2  260.64 ms  http: 403  http: 403
15  2403:8880:400f::2  261.69 ms  http: 403  http: 403

Traceroute to China, Beijing CERNET2 IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:da8:a0:1001::1 (2001:da8:a0:1001::1), 30 hops max, 32 byte packets
 1  2a04:5200::1  0.51 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  28.13 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e09b  19.74 ms  http: 403  http: 403
 4  2001:7f8:d:fe::187  40.09 ms  http: 403  http: 403
 5  *
 6  *
 7  2001:470:0:5cc::1  184.09 ms  http: 403  http: 403
 8  2001:470:0:2ea::1  217.76 ms  http: 403  http: 403
 9  2001:7fa:0:1::ca28:a1be  258.89 ms  http: 403  http: 403
10  2001:252:0:108::1  254.99 ms  http: 403  http: 403
11  2001:252:0:2::1  263.40 ms  http: 403  http: 403
12  2001:da8:a0:1001::1  254.65 ms  http: 403  http: 403

Traceroute to China, Beijing CSTNET IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2400:dd00:0:37::213 (2400:dd00:0:37::213), 30 hops max, 32 byte packets
 1  2a04:5200::1  0.60 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  1.33 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e09b  22.53 ms  http: 403  http: 403
 4  2001:7f8:d:fe::187  34.32 ms  http: 403  http: 403
 5  *
 6  *
 7  2001:470:0:5cc::1  198.63 ms  http: 403  http: 403
 8  2001:470:0:2ea::1  217.90 ms  http: 403  http: 403
 9  2001:7fa:0:1::ca28:a1be  268.53 ms  http: 403  http: 403
10  2001:252:0:109::1  259.38 ms  http: 403  http: 403
11  2001:252:0:1::2001  260.20 ms  http: 403  http: 403
12  2400:dd00:0:4::200  323.55 ms  http: 403  http: 403
13  2400:dd00:0:37::213  313.52 ms  http: 403  http: 403

Traceroute to China, Hongkong HKIX IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:7fa:0:1::ca28:a1a9 (2001:7fa:0:1::ca28:a1a9), 30 hops max, 32 byte packets
 1  2a04:5200::1  1.04 ms  http: 403  http: 403
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

Traceroute to China, Hongkong HE IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:470:0:490::2 (2001:470:0:490::2), 30 hops max, 32 byte packets
 1  2a04:5200::1  1.98 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  42.05 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e09b  19.90 ms  http: 403  http: 403
 4  2001:7f8:d:ff::187  40.26 ms  http: 403  http: 403
 5  *
 6  *
 7  2001:470:0:5cc::1  182.94 ms  http: 403  http: 403
 8  2001:470:0:2ea::1  217.25 ms  http: 403  http: 403
 9  2001:470:0:490::2  226.88 ms  http: 403  http: 403

Traceroute to United States, San Jose HE IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:470:1:ff::1 (2001:470:1:ff::1), 30 hops max, 32 byte packets
 1  2a04:5200::1  11.93 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  12.23 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e09b  19.91 ms  http: 403  http: 403
 4  2001:7f8:d:fe::187  26.88 ms  http: 403  http: 403
 5  2001:470:0:4da::2  33.32 ms  http: 403  http: 403
 6  *
 7  2001:470:0:559::1  109.19 ms  http: 403  http: 403
 8  2001:470:0:20a::1  109.51 ms  http: 403  http: 403
 9  2001:470:0:296::2  171.65 ms  http: 403  http: 403
10  2001:470:1:ff::1  186.78 ms  http: 403  http: 403

Traceroute to United States, Chicago NTT IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:418:0:5000::1026 (2001:418:0:5000::1026), 30 hops max, 32 byte packets
 1  2a04:5200::1  0.55 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  1.21 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e0a1  35.40 ms  http: 403  http: 403
 4  2001:1900:5:2:2::5be1  40.35 ms  http: 403  http: 403
 5  2001:1900:2::3:157  39.67 ms  http: 403  http: 403
 6  2001:728:0:4000::1d  36.21 ms  http: 403  http: 403
 7  2001:728:0:2000::245  37.18 ms  http: 403  http: 403
 8  *
 9  2001:728:0:2000::1e  54.70 ms  http: 403  http: 403
10  *
11  2001:418:0:2000::75  131.92 ms  http: 403  http: 403
12  2001:418:0:2000::235  131.17 ms  http: 403  http: 403
13  2001:418:0:5000::1026  134.18 ms  http: 403  http: 403

Traceroute to United States, Los Angeles Telia IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:2000:3080:1e96::2 (2001:2000:3080:1e96::2), 30 hops max, 32 byte packets
 1  2a04:5200::1  0.67 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  1.32 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e002  1.76 ms  http: 403  http: 403
 4  2a02:2d8:0:1029:232a::1  30.97 ms  http: 403  http: 403
 5  2001:2034:0:220::1  175.41 ms  http: 403  http: 403
 6  2001:2034:0:d2::1  30.89 ms  http: 403  http: 403
 7  2001:2034:1:c5::1  177.56 ms  http: 403  http: 403
 8  2001:2034:1:78::1  181.51 ms  http: 403  http: 403
 9  2001:2034:1:b8::1  175.07 ms  http: 403  http: 403
10  *
11  *
12  2001:2000:3080:1e96::2  168.58 ms  http: 403  http: 403

Traceroute to United States, Los Angeles GTT IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:668:0:3:ffff:0:d8dd:9d5a (2001:668:0:3:ffff:0:d8dd:9d5a), 30 hops max, 32 byte packets
 1  2a04:5200::1  0.65 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  1.51 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e0a1  37.01 ms  http: 403  http: 403
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
 1  2a04:5200::1  0.55 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  3.33 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e0a2  36.97 ms  http: 403  http: 403
 4  2001:7f8::4d7:0:1  40.19 ms  http: 403  http: 403
 5  2600:0:2:1239:213:206:129:27  40.61 ms  http: 403  http: 403
 6  2600:0:2:1239:213:206:129:9  50.83 ms  http: 403  http: 403
 7  2600:0:2:1239:217:118:224:40  50.26 ms  http: 403  http: 403
 8  2600:0:2:1239:144:232:9:111  128.42 ms  http: 403  http: 403
 9  2600:0:2:1239:144:232:0:245  128.30 ms  http: 403  http: 403
10  2600:0:2:1239:144:232:15:19  150.75 ms  http: 403  http: 403
11  2600:0:1:1239:144:228:241:71  161.32 ms  http: 403  http: 403

Traceroute to United States, Los Angeles Verizon IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2600:80a:2::15 (2600:80a:2::15), 30 hops max, 32 byte packets
 1  2a04:5200::1  0.42 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  5.25 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e0c9  106.13 ms  http: 403  http: 403
 4  2001:1900:2100::305d  117.17 ms  http: 403  http: 403
 5  2001:1900::3:212  110.60 ms  http: 403  http: 403
 6  2600:802:2::61  112.55 ms  http: 403  http: 403
 7  2600:80a:2::15  170.20 ms  http: 403  http: 403

Traceroute to United Status, Ashburn Cogentco IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:550:0:1000::9a36:4215 (2001:550:0:1000::9a36:4215), 30 hops max, 32 byte packets
 1  2a04:5200::1  2.32 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  0.97 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e0a1  36.57 ms  http: 403  http: 403
 4  2001:1900:5:2:2::5be1  47.65 ms  http: 403  http: 403
 5  *
 6  2001:1900:5:3::3de  41.19 ms  http: 403  http: 403
 7  *
 8  *
 9  *
10  *
11  2001:550:0:1000::9a36:4215  127.69 ms  http: 403  http: 403

Traceroute to United States, San Jose Level3 IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:1900:2100::2eb5 (2001:1900:2100::2eb5), 30 hops max, 32 byte packets
 1  2a04:5200::1  0.42 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  7.95 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e0a1  47.35 ms  http: 403  http: 403
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
 1  2a04:5200::1  1.20 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  6.26 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e0a2  35.70 ms  http: 403  http: 403
 4  2001:7f8::193d:0:1  45.59 ms  http: 403  http: 403
 5  2001:438:ffff::407d:1ae9  35.73 ms  http: 403  http: 403
 6  2001:438:ffff::407d:1fd8  171.49 ms  http: 403  http: 403
 7  *
 8  *
 9  *
10  *
11  2001:438:ffff::407d:1d7e  170.21 ms  http: 403  http: 403
12  *
13  2001:438:ffff::407d:1d1a  171.44 ms  http: 403  http: 403
14  2001:438:ffff::407d:1d01  166.07 ms  http: 403  http: 403
15  2001:438:ffff::407d:d6a  172.09 ms  http: 403  http: 403

Traceroute to France, Paris HE IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:470:0:349::1 (2001:470:0:349::1), 30 hops max, 32 byte packets
 1  2a04:5200::1  0.49 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  1.19 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e09b  20.79 ms  http: 403  http: 403
 4  2001:7f8:d:ff::187  40.13 ms  http: 403  http: 403
 5  2001:470:0:4da::2  30.79 ms  http: 403  http: 403
 6  2001:470:0:592::2  42.30 ms  http: 403  http: 403
 7  *
 8  2001:470:0:349::1  52.43 ms  http: 403  http: 403

Traceroute to German, Frankfurt NTT IPV6 (ICMP Mode, Max 30 Hop)
============================================================
traceroute to 2001:728:0:5000::6f6 (2001:728:0:5000::6f6), 30 hops max, 32 byte packets
 1  2a04:5200::1  0.63 ms  http: 403  http: 403
 2  2a02:2d8:0:82a:232a::  0.89 ms  http: 403  http: 403
 3  2a02:2d8::57f5:e0a1  44.89 ms  http: 403  http: 403
 4  2001:1900:5:2:2::5be1  53.41 ms  http: 403  http: 403
 5  2001:1900:2::3:157  35.91 ms  http: 403  http: 403
 6  2001:728:0:4000::1d  36.48 ms  http: 403  http: 403
 7  2001:728:0:2000::245  39.68 ms  http: 403  http: 403
 8  2001:728:0:2000::32  35.19 ms  http: 403  http: 403
 9  2001:728:0:5000::6f6  38.86 ms  http: 403  http: 403


Generated by LemonBench on 2021-10-25T12:06:51Z Version 20201005 Intl BetaVersion, Hosted by DMIT.IO
```
