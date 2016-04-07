## Environment Variables

Gru uses the following environment variables which you could set.

### GRU_ENDPOINT

The [etcd](https://github.com/coreos/etcd) cluster endpoint to which
client and minions connect.

Default value: http://127.0.0.1:2379,http://localhost:4001

### GRU_USERNAME

Username to use when authenticating against etcd.

Default: <blank>

### GRU_PASSWORD

Password to use when when authenticating against etcd.

Default: <blank>

### GRU_MODULEPATH

Path where modules can be discovered and loaded.

### GRU_TIMEOUT

Specifies the connection timeout per request