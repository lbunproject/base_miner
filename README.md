**BASE Miner Dashboard**

https://base-mining-leaderboard.streamlit.app

---

**BASE Miner Instructions**

1)      Download the miner from: https://github.com/lbunproject/base_miner

-   For Linux: base\_miner\_v01

-   For Windows: base\_miner\_v01.exe

2)      For Linux, change permissions to executable:

-   chmod 755 ./base\_miner\_v01

3)      Start miner from the commandline:

-   For Linux: ./base\_miner\_v01

-   For windows: base\_miner\_v01.exe

4)      Add wallet address with option 2

![](/images/add.jpg)

5)      Select the wallet with option 1

![](/images/select.jpg)

6)      Select number of CPU treads to use:  

![](/images/threads.jpg)

---

**Command line options:** 

AES hashing

-   \-aes\_hashes hw (default)

-   \-aes\_hashes sw (slower)

Execution mode

-   \-exec\_mode vm (default)

-   \-exec\_mode jit (faster)

Pages Size

-   \- mem\_pages small (default)

-   \-mem\_pages large (faster)

Memory Size

-   \- mem\_size full (default)

- \- mem\_size lite (slower)

**\*\*\* Not all CPUs support all options**