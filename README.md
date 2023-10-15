# how to fix bootmgr is missing
<h3>TLDR;</h3>
<p>sudah du testing dan bisa solved ketika ada kasus seperti ini di OS Windows 7, mungkin bisa juga di versi Windows yang lainnya.</p>
<pre>sfc /scannow /offbootdir=c:\ /offwindir=c:\windows</pre>
<p><b>note :</b> perlu di cek drive letter seperti <code>c:</code> tergantung windows terinstall dengan drive letter huruf apa</p>
