=========================
Eschalot Docker Container
=========================

Clone this and then cd into the directory and run `docker build -t eschalot-runner .`

Then to run it, simply do `docker run eschalot-runner -s fucker`

and the result will be like this:

```
Verbose, continuous, no digits, 5 threads, prefixes 6-6 characters long.
Thread #1 started.
Thread #2 started.
Thread #3 started.
Thread #4 started.
Thread #5 started.
Running, collecting performance data...
Total hashes: 60667592, running time: 10 seconds, hashes per second: 6066759
Total hashes: 186904841, running time: 30 seconds, hashes per second: 6230161
Total hashes: 437479575, running time: 70 seconds, hashes per second: 6249708
Found a key for fucker (6) - fuckerw4fgjg6au5.onion
----------------------------------------------------------------
fuckerw4fgjg6au5.onion
-----BEGIN RSA PRIVATE KEY-----
MIICXwIBAAKBgQDI9f6nKMGMbgt7XC6InrCHYBcQrx+ECsubZ73R3FUMfwtm1Fgo
BtpaZKBDsQ/xMsyQgjMyG0gDDFJXcVCPHqprNZzerMzTiA2mXV0temx2JKgGBVAa
8DS077DbKcyN2UPO3viLrAibI6//1U+x5KyshFQXjpz0Omx8yHMOk8dTKwIEDF90
KQKBgEiBZ42V2cZvSnt0hp6clln93wWOmXJnMryjOG3FTYtpFZ1+ChxjlRgDLpq8
UT8KPPhK80UjtQwqThcD0R0p6eabVOSvmHRXCj9rOPMt0+lo05ZzZ8Oxtk66pa0u
8TJHk65Zc8vIeQTBZXNQ/pANiVvSn+XK6gxrTxABhnU4s18JAkEA70GUgpvJ5pEY
zv77Jc5iIzs0HEmdZOhFyLaXklh8BRO1nz+QtnvyPi6TNZY5LKRtj6X7OG/Px2q3
LY/WlyK7SQJBANcGVPJRdg9A4vyEEAnKr1oW/FvutwfSCzaE+nTMTWCqkw8V3xfG
2dCy2vKfCITllr+tPz734+siY3ShziJpRtMCQQCKn8U1/Ok/XCWhCJr2a7QzbBX1
3CiudBfVJKoM0wBPE1BZZp+VaQ+R22G5iUQBwAg0I/4pZgyljW1U/7BGPOspAkEA
iV3pgWc+3pRMnWQt5TEEmF9CXybkHjf3LHLfBPHxU/shg7oIUL7oSEPcqIbR46KK
+pOUqxH9ZS/mcjad8ryheQJBAJj0qxyfhVGDuDr8lWNuC++z6+H0MRQ53Rg6cZOW
PGCqWqYr/5DNF0HuULqrS9OThMKSmn49sBVCEqwEGbslZks=
-----END RSA PRIVATE KEY-----
```
you could even run it like this:   
`docker run eschalot-runner -s fucker >> fucker.txt` to append to a local text file the results for safe keeping.

don't forget to kill it by running `docker stop` once you get enough generated.

