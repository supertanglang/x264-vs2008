1.install vc6
2.install vc6sp5
3.install vc6 process pack 5.0 (it only support vc6sp5 not vc6sp6)
4.find version 0.98 nasm( nasmw.exe rename to nasm.exe ) and 
  put it into C:\Program Files\Microsoft Visual Studio\VC98\Bin
5.unzip x264-060730 to c:\
6.run C:\x264-060730\build\win32\x264.dsw
7.in menu project->setting->debug->arguments set
  --no-cabac -o test.264 out.yuv 720x480
8.source = out.yuv, encode file = test.264 (By jesse stone taiwan)