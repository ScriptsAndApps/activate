# activate
wind activation



HowTo
DISM /online /Get-TargetEditions DISM /online /Set-Edition:ServerStandard /ProductKey:xxxxx-xxxxx-xxxxx-xxxxx-xxxxx /AcceptEula (reboot)

slmgr /ipk ххххх- ххххх – ххххх – ххххх – ххххх

slmgr /skms [serverhere]:1688

slmgr /ato

Test if a KMS server is online or not
http://technet.microsoft.com/en-us/library/ff793433.aspx

/skms Name[:Port] | : port [Activation ID] [Activation ID] 
slmgr.vbs /skms KMSServer2
slmgr.vbs /ato
Example: nslookup -type=srv _vlmcs._tcp.kms.digiboy.ir

Online KMS host address:
kms.srv.crsoo.com
cy2617.jios.org
kms.digiboy.ir
kms.cangshui.net
kms.library.hk
hq1.chinancce.com
kms.loli.beer
kms.v0v.bid
54.223.212.31
kms.jm33.me
nb.shenqw.win
kms.izetn.cn
kms.cin.ink
222.184.9.98
kms.ijio.net
fourdeltaone.net:1688
kms.iaini.net
kms.cnlic.com
kms.51it.wang
key.17108.com
kms.chinancce.com
kms.ddns.net
windows.kms.app
kms.ddz.red
franklv.ddns.net
kms.mogeko.me
k.zpale.com
amrice.top
m.zpale.com
mvg.zpale.com
kms.shuax.com
kensol263.imwork.net:1688
xykz.f3322.org
kms789.com
dimanyakms.sytes.net:1688
kms8.MSGuides.com
kms.03k.org:1688
kms.ymgblog.com
kms.bige0.com
kms9.MSGuides.com
kms.cz9.cn
kms.lolico.moe
kms.ddddg.cn
kms.zhuxiaole.org
kms.moeclub.org
kms.lotro.cc
zh.us.to
noair.strangled.net:1688
Offline kms host address:
mhd.kmdns.net110
noip.me
45.78.3.223
kms.didichuxing.coms
140.133.45.107
toxykz.f3322.org
cckms.nccu.edu.tw
192.168.2.81.2.7.0
vhk.3322.org
uitsckms.uit.tufts.edu
kms.isu.edu.tw
kms.crackmywpa.com
58.173.212.51
lsu-kms.lsu.edu
win81.no-ip.org
whwebsolution.no-ip.org
kms.guowaifuli.com
106.186.25.2393
rss.vicp.net:20439
122.226.152.230
222.76.251.188
98.212.2.163
annychen.pw
heu168.6655.la
kms.aglc.cc
kms.landiannews.com
kms.xspace.in
147.134.1.42
winkms.tk
kms7.MSGuides.com
Last updated:
13.01.2020
Change log:
Dups removed
Added some online KMS server provided by WindowsAddict
KMS_office.cmd
@echo off
title Microsoft Office 2019 versions are supported!&cls&echo
============================================================================&echo
#Project: Activating Microsoft software products for FREE without software&echo
============================================================================&echo.&echo
#Supported products:&echo - Microsoft Office Standard 2019&echo - Microsoft Office Professional Plus 2019&echo.&echo.&(if exist
"%ProgramFiles%\Microsoft Office\Office16\ospp.vbs" cd /d "%ProgramFiles%\Microsoft Office\Office16")&(if exist
"%ProgramFiles(x86)%\Microsoft Office\Office16\ospp.vbs" cd /d "%ProgramFiles(x86)%\Microsoft Office\Office16")&(for /f %%x in ('dir /b
..\root\Licenses16\ProPlus2019VL*.xrm-ms') do cscript ospp.vbs /inslic:"..\root\Licenses16\%%x" >nul)&(for /f %%x in ('dir /b
..\root\Licenses16\ProPlus2019VL*.xrm-ms') do cscript ospp.vbs /inslic:"..\root\Licenses16\%%x" >nul)&echo.&echo
============================================================================&echo
Activating your Office...&cscript //nologo ospp.vbs /unpkey:6MWKP >nul&cscript //nologo ospp.vbs /inpkey:NMMKJ-6RK4F-KMJVX-8D9MJ-
6MWKP >nul&set i=1
:server
if %i%==1 set KMS_Sev=kms7.MSGuides.com
if %i%==2 set KMS_Sev=kms8.MSGuides.com
if %i%==3 set KMS_Sev=kms9.MSGuides.com
if %i%==4 goto notsupported
cscript //nologo ospp.vbs /sethst:%KMS_Sev% >nul&echo
============================================================================&echo.&echo.
cscript //nologo ospp.vbs /act | find /i "successful" && (echo.&echo
============================================================================&echo.&echo
============================================================================&echo
Sorry! Your version is not supported.&echo Please try installing the latest version here: bit.ly/aiomsp
:halt
pause >nul
kmsoffice.txt
slmgr /ipk NPPR9-FWDCX-D2C8J-H872K-2YT43
slmgr /skms kms.digiboy.ir
slmgr /ato
Office_kms
cd\Program Files\Microsoft Office\Office16


cd\Program Files (x86)\Microsoft Office\Office16

cscript OSPP.VBS /sethst:kms.digiboy.ir
cscript OSPP.VBS /actcscript OSPP.VBS /dstatus


slmgr.vbs /ckms
