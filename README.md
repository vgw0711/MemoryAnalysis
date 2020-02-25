# MemoryAnalysis

This project consists of detailed analysis of memory usage of Lastpass password manager on windows and linux platforms. Memory usage here means, how securely does Lastpass stores and retrieves data from memory during runtime.

Security in out-of-extension processes is also analysed by studying the processes spawned by Keeper, Dashlane and Lastpass password managers.

Complete work is described in the report file and the other folder consists of references and other study materials that were used to generate this project report.

Tools Used : IDA, strace, gdb, cat(To display the process structure by viewing the file /proc/$pid/maps)

Platforms : Windows, Linux
