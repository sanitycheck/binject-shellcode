# shellcode
Shellcode library as a Go package

$ go build github.com/awgh/shellcode/shellcode
$ ./shellcode -a arm -b 32 -o linux
2019/01/08 03:15:40 {Os:linux Arch:arm Bit:32 Name:reverse_tcp_shell Function:0x4a7720}
2019/01/08 03:15:40 {Os:linux Arch:arm Bit:32 Name:reverse_tcp_stager Function:0x4a7bd0}
2019/01/08 03:15:40 {Os:linux Arch:arm Bit:32 Name:user_shellcode Function:0x4a8080}
