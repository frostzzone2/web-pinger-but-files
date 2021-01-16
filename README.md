# simple-website-pinger

Simple website pinger, you can use it to keep your repl.it or similiar projects online for 24/7!

[![NPM](https://nodei.co/npm/simple-website-pinger.png)](https://nodei.co/npm/simple-website-pinger/)


# Example code:

```js
const pinger = require("simple-website-pinger")

pinger.webserver(3000) // Create webserver on port 3000

pinger.ping("Your project url") //default interval is 1m, or you can specify own interval in ms
```

# Documantion:


| Methods       | Type           | Required      | Default    | Description |
| ------------- |:-------------:|:-------------:|:-------------:| :--------------:|
| ping("Your url", your interval in ms)     | String, Object | true, false | *None,  60000* | Start to ping the provided url every provided time |
| webserver(your port)     | Object | false | 3000 | Create simple websever for your project, to make it pingable |

