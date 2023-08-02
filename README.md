# command v5
<pre><code>sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/Bringas-tunnel/v5/main/bringas.sh && chmod +x bringas.sh && sed -i -e 's/\r$//' bringas && screen -S bringas ./bringas.sh</code></pre>
