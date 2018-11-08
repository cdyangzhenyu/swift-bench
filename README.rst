Swift Benchmarking tool.

git clone https://github.com/cdyangzhenyu/swift-bench

pip install ./swift-bench

swift-bench -V 3 -A http://192.168.247.227:5000/v3 -U admin:admin -K admin

-A: keystone endpoint

-V: api version

-U: tenant:username

-K: password

You also can use the config:

=====

[bench]

auth = http://192.168.247.227:5000/v3

user = admin:admin

key = admin

auth_version = 3.0

log-level = INFO

=====

swift-bench /etc/swift-bench/swift-bench.conf 
