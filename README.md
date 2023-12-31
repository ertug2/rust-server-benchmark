This is a basic harmony-mod based performance benchmark for the Rust game server. This includes the Windows and Linux version and is made for the staging build (13005895) of the Rust dedicated server files. That build of the server files are included.

This harmony-mod plugin is made by [@bmgjet](https://github.com/bmgjet), it also includes documentation on how to use below.

Steps to run benchmark:

1.) Get a dedicated server, VPS or computer that's running either Windows or Linux.

2.) Download latest 7z release archive of this for your operating system, ([Windows](https://github.com/ertug2/rust-server-benchmark/releases/download/v1.0.0/benchmark2023_windows.7z), [Linux](https://github.com/ertug2/rust-server-benchmark/releases/download/v1.0.0/benchmark2023_linux.7z))

3.) Extract the 7z archive into a folder

You may do this on Debian via:

```
apt-get install p7zip-full
7z x benchmark2023_linux.7z
```

4.) If you already ran the benchmark then delete the .sav and .map folders generated in ./server/BenchMark/

5.) Go into the extracted folder and run the benchmark with 8192 map world size. You may do so via either running [Bench]4_Extreme-14GB-230.bat (Windows) or bench_4_Extreme-14GB-230.sh (Linux) via the commands below:


```
chmod +x bench_4_Extreme-14GB-230.sh;chmod +x RustDedicated;
./bench_4_Extreme-14GB-230.sh
```

   -  This will generate a bench log file in the same folder once finished running which will have your results in it. Give it to [@bmgjet](https://github.com/bmgjet) or somebody to graph it out so that you can compare your results with others.

6.) Profit.
