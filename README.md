# Mediawiki-FlowdockNotify
A Mediawiki Extension for notifying Flowdock team inboxes on article creation, revision and deletion.

# Author
Tim Noise <tim@drkns.net>
https://github.com/dnoiz1/Mediawiki-FlowdockNotify

# Installation
- ```cd /path/to/mediawiki```
- ```git clone https://github.com/dnoiz1/Mediawiki-FlowdockNotify.git extensions/FlowdockNotify```
- get your flowdock API inbox token from inbox settings of the flow you wish to integrate
- add to LocalSettings.php ```php
$flowdock_token = "YourFlowdockInboxToken";
require_once("$IP/extensions/FlowdockNotify/FlowdockNotify.php");
```

# Uninstalling
- remove or comment out ```php
require_once("$IP/extensions/FlowdockNotify/FlowdockNotify.php");
``` from LocalSettings.php
