influx-php
============

PHP library for developing Influx applications.

```
require('influx.php');

$influx = new influxClient("http", "influxrpc", "password", "localhost");
$can_connect = $influx->can_connect();

if($can_connect>0) {
      $difficulty = $influx->getdifficulty();
      $influx_address = $influx->getnewaddress();
}
```
