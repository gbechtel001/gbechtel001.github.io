---
layout: post
title: Bandit Level 10
---
<h3>Bandit level 10</h3>
<p>userName: bandit10</p>
<p>Password: truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk</p>
<p>addess  : bandit.labs.overthewire.org</p>
<p>port    : 2220</p>
<h4>Commands of lab</h4>
<p>Connect to bandit.labs.overthewire.org using bandit10.</p>
<p>I Ran "ls" found data.txt</p>
<p>I can "cat data.txt" I found that the password was encrypted by base 64</p>
<p>I found out the Linux has a built in decode tool for base 64</p>
<p>https://linuxhint.com/bash_base64_encode_decode/</p>
<p>I ran "cat data.txt | base64 -d"</p>
<p>It returned: The password is IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR</p>
<p>level 11 password: IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR</p>
