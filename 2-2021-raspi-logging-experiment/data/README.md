# 2/2021 Raspi Logging Experiment Data
This folder contains data associated with the raspberry pi vs. CPC logging
experiment conducted in February 2021. [217CPCDATA.txt](https://github.com/airpartners/logger-data-analysis/blob/main/2-2021-raspi-logging-experiment/data/217CPCDATA.TXT)
and [218CPCDATA.txt](https://github.com/airpartners/logger-data-analysis/blob/main/2-2021-raspi-logging-experiment/data/218CPCDATA.TXT)
contain the raw data from the CPC, and [cpc-logged-data.txt](https://github.com/airpartners/logger-data-analysis/blob/main/2-2021-raspi-logging-experiment/data/raspi-logged-data.csv)
contains both days worth of data with a single consolidated header as follows:
```
#YY/MM/DD	HR:MN:SC	aveconc	concent	rawconc	cnt_sec	condtmp	satttmp	satbtmp	optctmp	inlttmp	smpflow	satflow	pressur	condpwr	sattpwr	satbpwr	optcpwr	satfpwr	exhfpwr	fillcnt	err_num	mcpcpmp	mcpcpwr
```

Meanwhile, [raspi-logged-data](https://github.com/airpartners/logger-data-analysis/blob/main/2-2021-raspi-logging-experiment/data/raspi-logged-data.csv)
contains the raw raspberry pi header with a manually added header as follows:
```
#YY/MM/DD:HR:MN:SC,valve_state,concent,rawconc,cnt_sec,condtmp,satttmp,satbtmp,optctmp,inlttmp,smpflow,satflow,pressur,condpwr,sattpwr,satbpwr,optcpwr,satfpwr,exhfpwr,fillcnt,err_num,mcpcpmp,mcpcpwr
```
