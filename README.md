# Selamat datang pengunjung

DONASI : Support via BI (Bank Indonesia) atau E-Wallet (Dana, Gopay, Linkaja, Ovo & ShopeePay)

<img src="https://user-images.githubusercontent.com/94752371/166851078-7768997c-42dd-4cdf-b094-8fb590107a47.png" height="500" style="max-width: 100%;">

# Daftar semua varian file host
<table>
<thead>
<tr>
<th align="center">Judul</th>
<th align="center">Mode 0.0.0.0</th>
<th align="center">Mode 127.0.0.1</th>
<th align="center">Mode Domain</th>
</tr>
</thead>
<tbody>
<tr>
<td>Reguler</td>
<td align="center"><a href="https://raw.githubusercontent.com/fandagroupofficial/hosts/main/pihole/reguler" rel="nofollow">Link</a></td>
<td align="center"><a href="https://raw.githubusercontent.com/fandagroupofficial/hosts/main/adaway/reguler" rel="nofollow">Link</a></td>
<td align="center"><a href="/index" rel="nofollow">-</a></td>
</tr>
<tr>
<td>Advertising</td>
<td align="center"><a href="https://raw.githubusercontent.com/fandagroupofficial/hosts/main/pihole/ads" rel="nofollow">Link</a></td>
<td align="center"><a href="https://raw.githubusercontent.com/fandagroupofficial/hosts/main/adaway/ads" rel="nofollow">Link</a></td>
<td align="center"><a href="/index" rel="nofollow">-</a></td>
</tr>
<tr>
<td>Analytics</td>
<td align="center"><a href="https://raw.githubusercontent.com/fandagroupofficial/hosts/main/pihole/analytics" rel="nofollow">Link</a></td>
<td align="center"><a href="https://raw.githubusercontent.com/fandagroupofficial/hosts/main/adaway/analytics" rel="nofollow">Link</a></td>
<td align="center"><a href="/index" rel="nofollow">-</a></td>
</tr>
<tr>
<td>Log</td>
<td align="center"><a href="https://raw.githubusercontent.com/fandagroupofficial/hosts/main/pihole/log" rel="nofollow">Link</a></td>
<td align="center"><a href="https://raw.githubusercontent.com/fandagroupofficial/hosts/main/adaway/log" rel="nofollow">Link</a></td>
<td align="center"><a href="/index" rel="nofollow">-</a></td>
</tr>
<tr>
<td>Malware</td>
<td align="center"><a href="https://raw.githubusercontent.com/fandagroupofficial/hosts/main/pihole/malware" rel="nofollow">Link</a></td>
<td align="center"><a href="https://raw.githubusercontent.com/fandagroupofficial/hosts/main/adaway/malware" rel="nofollow">Link</a></td>
<td align="center"><a href="/index" rel="nofollow">-</a></td>
</tr>
<tr>
<td>Trackers</td>
<td align="center"><a href="https://raw.githubusercontent.com/fandagroupofficial/hosts/main/pihole/trackers" rel="nofollow">Link</a></td>
<td align="center"><a href="https://raw.githubusercontent.com/fandagroupofficial/hosts/main/adaway/trackers" rel="nofollow">Link</a></td>
<td align="center"><a href="/index" rel="nofollow">-</a></td>
</tr>
<tr>
<td>Ublock</td>
<td align="center"><a href="https://raw.githubusercontent.com/fandagroupofficial/hosts/main/pihole/ublock" rel="nofollow">Link</a></td>
<td align="center"><a href="https://raw.githubusercontent.com/fandagroupofficial/hosts/main/adaway/ublock" rel="nofollow">Link</a></td>
<td align="center"><a href="/index" rel="nofollow">-</a></td>
</tr>
<tr>
<td>Porn</td>
<td align="center"><a href="/index" rel="nofollow">-</a></td>
<td align="center"><a href="/index" rel="nofollow">-</a></td>
<td align="center"><a href="https://raw.githubusercontent.com/fandagroupofficial/hosts/main/domain/porn" rel="nofollow">Link</a></td>
</tr>
<tr>
<td>Push</td>
<td align="center"><a href="https://raw.githubusercontent.com/fandagroupofficial/hosts/main/pihole/push" rel="nofollow">Link</a></td>
<td align="center"><a href="https://raw.githubusercontent.com/fandagroupofficial/hosts/main/adaway/push" rel="nofollow">Link</a></td>
<td align="center"><a href="/index" rel="nofollow">-</a></td>
</tr>
</tbody>
</table>

# AdAway
Mode pemblokiran yang direkomendasi pengembang AdAway adalah <b>127.0.0.1</b>

Download aplikasi AdAway untuk android : 
<p dir="auto"><a href="https://app.adaway.org/adaway.apk" rel="nofollow"><img src="https://raw.githubusercontent.com/AdAway/AdAway/master/Resources/get-it-on-fdroid.png" alt="Get it on official AdAway website" height="80" style="max-width: 100%;"></a>

# Pi-Hole

  Mode pemblokiran yang direkomendasi pengembang Pi-hole adalah <b>0.0.0.0</b>
<p><blockquote>Following <a href="https://tools.ietf.org/html/rfc3513#section-2.5.2">RFC 3513, Internet Protocol Version 6 (<abbr title="Internet Protocol version 6 (addresses like 2001:db8::ff00:42:8329)">IPv6</abbr>) Addressing Architecture, section 2.5.2</a>, the address <code>0:0:0:0:0:0:0:0</code> (or <code>::</code> for short) is the unspecified address. It must never be assigned to any node and indicates the absence of an address. Following <a href="https://tools.ietf.org/html/rfc1122#section-3.2">RFC1122, section 3.2</a>, the address <code>0.0.0.0</code> can be understood as the <abbr title="Internet Protocol version 4 (addresses like 192.168.0.1)">IPv4</abbr> equivalent of <code>::</code>.</blockquote></p>
  
Berikut sistem operasi secara resmi didukung oleh pi-hole :

<table>
<thead>
<tr>
<th>Distribution</th>
<th>Release</th>
<th>Architecture</th>
</tr>
</thead>
<tbody>
<tr>
<td>Raspberry Pi <abbr title="Operating system">OS</abbr> <br>(formerly Raspbian)</td>
<td>Stretch / Buster / Bullseye</td>
<td>ARM</td>
</tr>
<tr>
<td>Ubuntu</td>
<td>16.x / 18.x / 20.x /21.x</td>
<td>ARM / x86_64</td>
</tr>
<tr>
<td>Debian</td>
<td>9 / 10 /11</td>
<td>ARM / x86_64 / i386</td>
</tr>
<tr>
<td>Fedora</td>
<td>33 / 34</td>
<td>ARM / x86_64</td>
</tr>
<tr>
<td>CentOS</td>
<td>7</td>
<td>x86_64</td>
</tr>
<tr>
<td>CentOS Stream</td>
<td>8</td>
<td>x86_64</td>
</tr>
</tbody>
</table>
  
# Hubungi Kami : <a href="https://linktr.ee/fandagroup" target="_blank" class="text-bold">Disini</a>
