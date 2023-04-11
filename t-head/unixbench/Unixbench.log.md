# Unixbench.log

```

   #    #  #    #  #  #    #          #####   ######  #    #   ####   #    #
   #    #  ##   #  #   #  #           #    #  #       ##   #  #    #  #    #
   #    #  # #  #  #    ##            #####   #####   # #  #  #       ######
   #    #  #  # #  #    ##            #    #  #       #  # #  #       #    #
   #    #  #   ##  #   #  #           #    #  #       #   ##  #    #  #    #
    ####   #    #  #  #    #          #####   ######  #    #   ####   #    #

   Version 5.1.2                      Based on the Byte Magazine Unix Benchmark

   Multi-CPU version                  Version 5 revisions by Ian Smith,
                                      Sunnyvale, CA, USA
   December 22, 2007                  johantheghost at yahoo period com


1 x Dhrystone 2 using register variables  1 2 3 4 5 6 7 8 9 10

1 x Double-Precision Whetstone  1 2 3 4 5 6 7 8 9 10

1 x Execl Throughput  1 2 3

1 x File Copy 1024 bufsize 2000 maxblocks  1 2 3

1 x File Copy 256 bufsize 500 maxblocks  1 2 3

1 x File Copy 4096 bufsize 8000 maxblocks  1 2 3

1 x Pipe Throughput  1 2 3 4 5 6 7 8 9 10

1 x Pipe-based Context Switching  1 2 3 4 5 6 7 8 9 10

1 x Process Creation  1 2 3

1 x System Call Overhead  1 2 3 4 5 6 7 8 9 10

1 x Shell Scripts (1 concurrent)  1 2 3

1 x Shell Scripts (8 concurrent)  1 2 3

========================================================================
   BYTE UNIX Benchmarks (Version 5.1.2)

   System: lpi4a: GNU/Linux
   OS: GNU/Linux -- 5.10.113-yocto-standard -- #1 SMP PREEMPT Sun Mar 5 14:36:24 UTC 2023
   Machine: riscv64 (unknown)
   Language: en_US.utf8 (charmap="ANSI_X3.4-1968", collate="ANSI_X3.4-1968")
   08:14:22 up 5 min,  1 user,  load average: 0.31, 0.26, 0.12; runlevel 

------------------------------------------------------------------------
Benchmark Run: Tue Apr 11 2023 08:14:22 - 08:42:42
0 CPUs in system; running 1 parallel copy of tests

Dhrystone 2 using register variables       10640007.5 lps   (10.0 s, 7 samples)
Double-Precision Whetstone                     2630.4 MWIPS (10.0 s, 7 samples)
Execl Throughput                               1212.7 lps   (29.9 s, 2 samples)
File Copy 1024 bufsize 2000 maxblocks        134103.0 KBps  (30.0 s, 2 samples)
File Copy 256 bufsize 500 maxblocks           35479.3 KBps  (30.0 s, 2 samples)
File Copy 4096 bufsize 8000 maxblocks        468458.2 KBps  (30.0 s, 2 samples)
Pipe Throughput                              314451.0 lps   (10.0 s, 7 samples)
Pipe-based Context Switching                  48919.2 lps   (10.0 s, 7 samples)
Process Creation                               1811.3 lps   (30.0 s, 2 samples)
Shell Scripts (1 concurrent)                   2384.1 lpm   (60.0 s, 2 samples)
Shell Scripts (8 concurrent)                    930.0 lpm   (60.0 s, 2 samples)
System Call Overhead                         432819.4 lps   (10.0 s, 7 samples)

System Benchmarks Index Values               BASELINE       RESULT    INDEX
Dhrystone 2 using register variables         116700.0   10640007.5    911.7
Double-Precision Whetstone                       55.0       2630.4    478.3
Execl Throughput                                 43.0       1212.7    282.0
File Copy 1024 bufsize 2000 maxblocks          3960.0     134103.0    338.6
File Copy 256 bufsize 500 maxblocks            1655.0      35479.3    214.4
File Copy 4096 bufsize 8000 maxblocks          5800.0     468458.2    807.7
Pipe Throughput                               12440.0     314451.0    252.8
Pipe-based Context Switching                   4000.0      48919.2    122.3
Process Creation                                126.0       1811.3    143.8
Shell Scripts (1 concurrent)                     42.4       2384.1    562.3
Shell Scripts (8 concurrent)                      6.0        930.0   1549.9
System Call Overhead                          15000.0     432819.4    288.5
                                                                   ========
System Benchmarks Index Score                                         376.3

```

