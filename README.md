DumpFrameworks.pl

class-dump+dumpframeworks.pl

一.安装class-dump
 1.下载dump项目运行并把 class-dump 拷贝到 /Users/Ethan/bin/class-dump 目录下（下载地址https://github.com/EthanGHub/class-dump-master.git）;
2.修改class-dump 权限  
Ethans-MacBook-Air:~ Ethan$ chmod 777 /Users/Ethan/bin/class-dump 
Ethans-MacBook-Air:~ Ethan$  

二.DumpFrameworks.pl
 1.下载文件放到任意目录即可
 2.修改DumpFrameworks.pl 权限
 3.修改dumpframeworks路径地址为所需的路径
dump_frameworks('/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneSimulator.platform/Developer/SDKs/iPhoneSimulator9.3.sdk/System/Library/Frameworks',
                'Frameworks');
                
                
dump_frameworks('/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneSimulator.platform/Developer/SDKs/iPhoneSimulator9.3.sdk/System/Library/PrivateFrameworks',
                'PrivateFrameworks');

 4.cd到DumpFrameworks.pl目录文件下运行 ./DumpFrameworks.pl
 5./Users/Ethan/Headers 就是你想要的内容
