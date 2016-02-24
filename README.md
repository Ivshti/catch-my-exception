# catch-my-exception

## Catch node.js exceptions and send a detailed trace to a Slack webhook

### ``var catchMyException = require('catch-my-exception')``

### ``catchMyException(webbookUri, opts)``

**Call catchMyException with your Slack webhookUri and the appropriate options at the initialization of your app.**

##### Opts:

**quitOnException** - default **``true``** - whether to ``process.exit(1)`` upon an exception

**slackChannel** - default **``#bugs``**

**slackUsername** - default **``webhookbot``**

