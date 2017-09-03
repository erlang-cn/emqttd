EMQ 2.1.2
=========

Features
--------

* Clean EMQ emqttd server 2.1.2
* Persistent Routes: [mqtt_topic, mqtt_router]
* Persistent Subscriptions: [mqtt_subproperty, mqtt_subscription, mqtt_subscriber]
* KVS database: [redis, mnesia, aerospike, mongodb]
* MAD compatible

Try
---

```shell
$ git clone git://synrc.com/synrc/emqttd && cd emqttd
$ rebar get-deps compile ct
$ mad rep
```

Credits
-------

* Maxim Sokhatsky (maintainer)
* Feng Lee (author)

OM A HUM
