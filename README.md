# etcd-presence
fleet service to set srv record in etcd for skydns2

- since the default domain is skydns2 is cluster.duffqiu.org, etcd srv records are under `_etcd._tcp.cluster.duffqiu.org` and the corresponding directory in etcd is `/skydns/org/duffqiu/cluster/_tcp/_etcd`
- the hostname will be the key to story the host ip and port
