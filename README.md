# Adlist for mikrotik

<b>DONASI</b> : Support via BI (Bank Indonesia) atau E-Wallet (Dana, Gopay, Linkaja, Ovo & ShopeePay)

<img src="https://user-images.githubusercontent.com/94752371/166851078-7768997c-42dd-4cdf-b094-8fb590107a47.png" height="500" style="max-width: 100%;">

Terima kasih yang telah berkontribusi untuk uang kopi + rokoknya para juragan. *:-)

# Halaman ini berisi address list untuk mikrotik
Dengan adlist berikut anda bisa gunakan berbagai macam fungsi, Misalnya :
   * Filter rule 
   * Packet
   * Routing
   * Dan lain-lain

Untuk penggunaan routing memang tidak di alokasikan secara spesifik ke arah tujuan dikarnakan untuk kelancaran koneksi seperti Facebook, instagram, Youtube, Dll
Terlebih lagi dari platform google biasanya PlayStore atau yang lainnya akan terganggu. Maka dari itu tidak kita sertakan karna ada tambahan config (Premium Only)

Khusus routing game ada tambahan config add address list mode by port (Kecuali port <b>TCP : 80,443,8080 & UDP : 80,443</b> saat pisah <b>packet</b> maupun <b>traffic</b>)

<table>
<thead>
<tr>
<th align="center">Title</th>
<th align="center">Script</th>
<th align="center">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>DNS over HTTPS</td>
<td align="center"><a href="https://github.com/fandagroupofficial/mikrotik/raw/main/adlist-doh" rel="nofollow">Link</a></td>
<th align="center">Domain Name System</th>
</tr>
<tr>
<td>Games</td>
<td align="center"><a href="https://raw.githubusercontent.com/fandagroupofficial/mikrotik/main/adlist-games" rel="nofollow">Link</a></td>
<th align="center">Garena, Tencent, Zenlayer (Official)</th>
</tr>
<tr>
<td>Facebook</td>
<td align="center"><a href="https://github.com/fandagroupofficial/mikrotik/raw/main/adlist-facebook" rel="nofollow">Link</a></td>
<th align="center">Facebook (Official)</th>
</tr>
<tr>
<td>WhatsApp</td>
<td align="center"><a href="https://github.com/fandagroupofficial/mikrotik/raw/main/adlist-whatsapp" rel="nofollow">Link</a></td>
<th align="center">WhatsApp (Official)</th>
</tr>
<tr>
<td>Ketengan</td>
<td align="center"><a href="https://github.com/fandagroupofficial/mikrotik/raw/main/adlist-ketengan" rel="nofollow">Link</a></td>
<th align="center">Youtube, Tiktok (Official)</th>
</tr>
<tr>
<td>XL Unlimited</td>
<td align="center"><a href="https://github.com/fandagroupofficial/mikrotik/raw/main/adlist-xl-unlimited" rel="nofollow">Link</a></td>
<th align="center">Facebook, Instagram, Gojek</th>
</tr>
<tr>
<td>Tsel Unlimited</td>
<td align="center"><a href="https://github.com/fandagroupofficial/mikrotik/raw/main/adlist-tsel-unlimited" rel="nofollow">Link</a></td>
<th align="center">Youtube, Tiktok, Snackvideo, Dll</th>
</tr>
</tbody>
</table>

<p><blockquote>Notice : Jika ingin address list <b>Ketengan, Tsel Unlimited, Dll</b> versi premium silahkan PM (Bukan berrti semua paket yang di dapat dalam SC dimasukkan dalam adlist melainkan yang sudah <b>DIUJI</b> sesuai paket setiap provider, Seperti yang sudah dijelaskan diatas.)</blockquote></p>
<p><blockquote>Premium Only : Next Update 29 Mei 2022 (Tsel Unlimited = Apps Viu, Apps Vidio, Dll)</blockquote></p>
  
Contoh kecil perbedaan tujuan :

<b>"Facebook"</b>
1. XL-Axiata = video.fsub2-1.fna.fbcdn.net
2. Telkomsel = video.fsub4-1.fna.fbcdn.net

<b>"Youtube"</b>
1. XL-Axiata = r1---sn-xmjxajvh-jb3s.googlevideo.com
2. Telkomsel = r1---sn-uxa3vhnxa-n0c6.googlevideo.com

Meski sama-sama dari sub domain yang sama tetapi beda ASN ( Bisa anda check dengan converter <a href="https://whatismyipaddress.com/hostname-ip" rel="nofollow">Hostname to IP Address</a> )

# Huawei Manager
Aplikasi untuk cek kualitas sinyal modem GSM merk huawei (v.7 Android)
<p dir="auto"><a href="https://www.mediafire.com/file/p8symlayaelcrl9/Huawei_Manager_7_English.apk/file" rel="nofollow"><img src="https://user-images.githubusercontent.com/94752371/169036676-13f98de5-c789-4ebc-a4e9-2423690d008e.png" alt="Get it on official AdAway website" height="80" style="max-width: 100%;"></a>

# Quick script command line

Berikut adalah daftar list script cepat via terminal / telnet yang bisa untuk membuat "system -> scheduler" maupun "system -> scripts"

Hapus semua menu "firewall -> connections"
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" data-snippet-clipboard-copy-content="/ip firewall connection remove [find]"><pre>/ip firewall connection remove [find]</pre></div>
  
# Hubungi Kami : <a href="https://linktr.ee/fandagroup" target="_blank" class="text-bold">Disini</a>
