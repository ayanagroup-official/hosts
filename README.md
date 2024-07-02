# AdGuard Home
  Mode pemblokiran yang direkomendasi adalah <b>|| atau 127.0.0.1 maupun REGEX</b>

# MikroTik
  Mode pemblokiran yang direkomendasi adalah <b>0.0.0.0</b> minimal v7.15

<pre>
/ip/dns/set cache-size=10240
/ip dns adlist
add ssl-verify=no url=https://raw.githubusercontent.com/ayanagroup-official/hosts/main/mikrotik/ads
add ssl-verify=no url=https://raw.githubusercontent.com/ayanagroup-official/hosts/main/mikrotik/analytics
add ssl-verify=no url=https://raw.githubusercontent.com/ayanagroup-official/hosts/main/mikrotik/general
add ssl-verify=no url=https://raw.githubusercontent.com/ayanagroup-official/hosts/main/mikrotik/judol
add ssl-verify=no url=https://raw.githubusercontent.com/ayanagroup-official/hosts/main/mikrotik/log
add ssl-verify=no url=https://raw.githubusercontent.com/ayanagroup-official/hosts/main/mikrotik/malware
add ssl-verify=no url=https://raw.githubusercontent.com/ayanagroup-official/hosts/main/mikrotik/porn
add ssl-verify=no url=https://raw.githubusercontent.com/ayanagroup-official/hosts/main/mikrotik/smartphone
add ssl-verify=no url=https://raw.githubusercontent.com/ayanagroup-official/hosts/main/mikrotik/tracker</pre>

<details>
<summary>By : Steven Black</summary>
<pre>
/ip dns adlist
add ssl-verify=no url=https://raw.githubusercontent.com/StevenBlack/hosts/master/data/Badd-Boyz-Hosts/hosts
add ssl-verify=no url=https://raw.githubusercontent.com/StevenBlack/hosts/master/data/KADhosts/hosts
add ssl-verify=no url=https://raw.githubusercontent.com/StevenBlack/hosts/master/data/MetaMask/hosts
add ssl-verify=no url=https://raw.githubusercontent.com/StevenBlack/hosts/master/data/StevenBlack/hosts
add ssl-verify=no url=https://raw.githubusercontent.com/StevenBlack/hosts/master/data/URLHaus/hosts
add ssl-verify=no url=https://raw.githubusercontent.com/StevenBlack/hosts/master/data/UncheckyAds/hosts
add ssl-verify=no url=https://raw.githubusercontent.com/StevenBlack/hosts/master/data/add.2o7Net/hosts
add ssl-verify=no url=https://raw.githubusercontent.com/StevenBlack/hosts/master/data/add.Dead/hosts
add ssl-verify=no url=https://raw.githubusercontent.com/StevenBlack/hosts/master/data/add.Risk/hosts
add ssl-verify=no url=https://raw.githubusercontent.com/StevenBlack/hosts/master/data/add.Spam/hosts
add ssl-verify=no url=https://raw.githubusercontent.com/StevenBlack/hosts/master/data/hostsVN/hosts
add ssl-verify=no url=https://raw.githubusercontent.com/StevenBlack/hosts/master/data/mvps.org/hosts
add ssl-verify=no url=https://raw.githubusercontent.com/StevenBlack/hosts/master/data/someonewhocares.org/hosts
add ssl-verify=no url=https://raw.githubusercontent.com/StevenBlack/hosts/master/data/tiuxo/hosts
add ssl-verify=no url=https://raw.githubusercontent.com/StevenBlack/hosts/master/data/yoyo.org/hosts</pre>
</details>

<details>
<summary>By : GoodbyeAds</summary>
<pre>
/ip dns adlist
add ssl-verify=no url=https://raw.githubusercontent.com/jerryn70/GoodbyeAds/master/Hosts/GoodbyeAds.txt</pre>
</details>
Note : Sesuaikan "Chace Size" dari seberapa banyak "Name Count" sumber yang anda gunakan

<hr>
<center><h1>This host filter is for internal development/experimental purposes only and not intended for public use. We may change this service anytime without any notice. For production system, you need to setup host filter service on your own server.</h1></center>
