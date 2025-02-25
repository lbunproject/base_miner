**BASE Miner Dashboard**

https://base-mining-leaderboard.streamlit.app

---

**BASE Miner Instructions**

1)      Download the miner from: https://github.com/lbunproject/base_miner

-   For Linux: base_miner_v01

-   For Windows: base_miner_v01.exe

-   For MacOS: base_miner_mac_arm64_v01 
     - (Must place in a folder called BASE_MINER)

2)       Change permissions to executable via commandline:

-   For Linux, chmod +x ./base_miner_v01
-   For Windows, N/A
-   For MacOS, chmod +x /path_to_folder/BASE_MINER/base_miner_mac_arm64_v01

3)      Start miner from the commandline (in same directory as file):

-   For Linux: ./base_miner_v01

-   For Windows: base_miner_v01.exe

-   For MacOS: ./base_miner_mac_arm64_v01

4)      Add wallet address with option 2

![](/images/add.jpg)

5)      Select the wallet with option 1

![](/images/select.jpg)

6)      Select number of CPU treads to use:  

![](/images/threads.jpg)

---
---

**Warning:** <font color="red">**DO NOT**</font> use the same wallet address for multiple miners. Doing so may activate the anti-cheat system (due to exceeding the rate limit) and you will  <font color="red">**NOT**</font> earn rewards!

![](/images/exceeded.jpg)

---
---

**Command line options:**

<font color="red">**Not all CPUs support all options**</font>

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

---
---

Credit goes to Bill for providing the instructions on the MacOS version
