10k MYCN reward for who is pulling first the source code for MyCoin with gif pictures for each installation level.
- the reward will be for each language so for eaxample if you will pull for eng and spanish and will be validated you will be rewarded with 20K MYCN on the provided MYCN address for donations.


This is the MyCoin Address from where the coins will be paid!

bc1qzye2gs3mja20n3jcew07udlq9g4rklue2wyzrp

=====================================
<b>Instalation on:</b>

[Dependencies](http://utgqnthifz425xaprmzpcorvzshpecnkmbl5iqhpyh7wvcrfdhsdq7id.onion/mycoin/core/src/branch/master/doc/dependencies.md)

[Android](http://utgqnthifz425xaprmzpcorvzshpecnkmbl5iqhpyh7wvcrfdhsdq7id.onion/mycoin/core/src/branch/master/doc/build-android.md)<br>
[FreeBSD](http://utgqnthifz425xaprmzpcorvzshpecnkmbl5iqhpyh7wvcrfdhsdq7id.onion/mycoin/core/src/branch/master/doc/build-freebsd.md)<br>
[NetBSD](http://utgqnthifz425xaprmzpcorvzshpecnkmbl5iqhpyh7wvcrfdhsdq7id.onion/mycoin/core/src/branch/master/doc/build-netbsd.md)<br>
[OpenBSD](http://utgqnthifz425xaprmzpcorvzshpecnkmbl5iqhpyh7wvcrfdhsdq7id.onion/mycoin/core/src/branch/master/doc/build-openbsd.md)<br>
[OSX](http://utgqnthifz425xaprmzpcorvzshpecnkmbl5iqhpyh7wvcrfdhsdq7id.onion/mycoin/core/src/branch/master/doc/build-osx.md)<br>
[Windows](http://utgqnthifz425xaprmzpcorvzshpecnkmbl5iqhpyh7wvcrfdhsdq7id.onion/mycoin/core/src/branch/master/doc/build-windows.md)<br>
[Unix](http://utgqnthifz425xaprmzpcorvzshpecnkmbl5iqhpyh7wvcrfdhsdq7id.onion/mycoin/core/src/branch/master/doc/build-unix.md)<br>

<b>Main Node: sp54l6svddwizrgq.onion</b>
<hr>
<b>For Node</b>

<p>mycoin.conf file will contain:</p>

<pre>
onlynet=onion<br>
txindex=1<br>
proxy=127.0.0.1:9050<br>
listen=1<br>
bind=127.0.0.1<br>
proxy=""""your onion address"""<br>
discover=1<br>
maxconnections=20<br>
server=1<br>
daemon=1<br>
testnet=0<br>
rpcuser="""your username"""<br>
rpcpassword="""your password"""<br>
# this is the main node as well you could add more if you know others or from our Draw Page<br>
addnode=sp54l6svddwizrgq.onion<br>
rpcport=9332
</pre>
<br>
<b>For Wallet</b><br>

<p>mycoin.conf file will contain:</p>

<pre>
onlynet=onion<br>
assumevalid=0<br>
server=1<br>
daemon=1<br>
listen=1<br>
testnet=0<br>
rpcuser="""your username"""<br>
rpcpassword="""your password"""<br>
addnode=""" your node address in this format 192.168.0.193 """<br>
rpcport=9332<br>
rpcallowip=127.0.0.1<br>
</pre>

<b>How to use the included Miner?</b>

<p>After the installation is done go to miner folder in terminal and paste this with your MyCoin address generated by your MyCoin Wallet:</p>

<pre>cd miner</pre>

<pre>
./minerd -o http://127.0.0.1:9332 -u """add your rpc username"""  -p """add your rpc password""" -a sha256d --no-longpoll --no-getwork --no-stratum --coinbase-addr=""" add your MyCoin Address generated by your Wallet"""
</pre>
