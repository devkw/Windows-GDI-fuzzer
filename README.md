# Windows Graphics Device Interface (GDI+) fuzzer

this project including
- harness to fuzz GDI+ via transform emf to wmf
- test corpus with good coverage
- vulnerability POC & report generated by <a href="https://github.com/SkyLined/BugId">BugId</a>

![result](https://raw.githubusercontent.com/math1as/Windows-GDI-fuzzer/master/result.txt)

## Note

Since the bottleneck of fuzzer is the IO performance of the disk, the use of RAMDISK can effectively speed up this process.

But remember to make a snapshot for your vm-machine or you may lost all of your files.

some of my vulnerability which could be triggered in Microsoft Powerpoint get lost in this way ,will attach them if recovered.

happy bug hunting!

## CVE-ID?

At that time I go on holiday ,left the fuzzer just running day after night.
so I forget to report these vulnerabilities at all ,most of them get patched in Microsoft July patch tuesday.

## credit

Personal project created by Wenxu Wu(<a href="https://twitter.com/ma7h1as">@ma7h1as</a>)
