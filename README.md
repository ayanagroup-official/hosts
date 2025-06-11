# AdGuard Home
  Mode pemblokiran yang direkomendasi adalah <b>|| atau 127.0.0.1 maupun REGEX</b>

# MikroTik
  Mode pemblokiran yang direkomendasi adalah <b>0.0.0.0</b> minimal v7.15

<pre>
/ip/dns/set cache-size=40960
/ip dns adlist
add ssl-verify=no url=https://raw.githubusercontent.com/ayanagroup-official/hosts/main/mikrotik/ads
add ssl-verify=no url=https://raw.githubusercontent.com/ayanagroup-official/hosts/main/mikrotik/analytics
add ssl-verify=no url=https://raw.githubusercontent.com/ayanagroup-official/hosts/main/mikrotik/general
add ssl-verify=no url=https://raw.githubusercontent.com/ayanagroup-official/hosts/main/mikrotik/log
add ssl-verify=no url=https://raw.githubusercontent.com/ayanagroup-official/hosts/main/mikrotik/malware
add ssl-verify=no url=https://raw.githubusercontent.com/ayanagroup-official/hosts/main/mikrotik/porn
add ssl-verify=no url=https://raw.githubusercontent.com/ayanagroup-official/hosts/main/mikrotik/smartphone
add ssl-verify=no url=https://raw.githubusercontent.com/ayanagroup-official/hosts/main/mikrotik/tracker</pre>

<details>
<summary>By : Steven Black</summary>
<pre>
/ip dns adlist
add ssl-verify=no url=https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts
  
"Tunggu setelah data yang diatas sudah terbaca, bisa dilanjutkan step berikutnya"

/ip dns adlist
add ssl-verify=no url=https://raw.githubusercontent.com/StevenBlack/hosts/master/data/Badd-Boyz-Hosts/hosts
add ssl-verify=no url=https://raw.githubusercontent.com/StevenBlack/hosts/master/data/KADhosts/hosts
add ssl-verify=no url=https://raw.githubusercontent.com/StevenBlack/hosts/master/data/mvps.org/hosts
add ssl-verify=no url=https://raw.githubusercontent.com/StevenBlack/hosts/master/data/someonewhocares.org/hosts
add ssl-verify=no url=https://raw.githubusercontent.com/StevenBlack/hosts/master/data/yoyo.org/hosts</pre>
</details>

<details>
<summary>By : GoodbyeAds</summary>
<pre>
/ip dns adlist
add ssl-verify=no url=https://raw.githubusercontent.com/jerryn70/GoodbyeAds/master/Hosts/GoodbyeAds.txt</pre>
</details>
<details>
<summary>By : HaGeZi</summary>
<pre>
/ip dns adlist
add ssl-verify=no url=https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/light.txt</pre>
</details>
<details>
<summary>By : CrazyMax</summary>
<pre>
/ip dns adlist
add ssl-verify=no url=https://raw.githubusercontent.com/crazy-max/WindowsSpyBlocker/master/data/hosts/spy.txt</pre>
</details>
Note : Sesuaikan "Chace Size" dari seberapa banyak "Name Count" sumber yang anda gunakan

<hr>
<center><h1>Filter host ini hanya untuk tujuan pengembangan/eksperimental internal dan tidak dimaksudkan untuk penggunaan umum. Kami dapat mengubah layanan ini kapan saja tanpa pemberitahuan apa pun. Untuk sistem produksi, Anda perlu menyiapkan layanan filter host di server Anda sendiri.</h1></center>
