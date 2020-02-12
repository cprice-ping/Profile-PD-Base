# Profile-PD-Base
 Designed to layer onto GET Baseline to correct the following:

* ACIs moved to DIR root -- allows AuthN \ DelAdmin to work outside of `o=People`
* ACIs modified to enable PingFed SSPR to work correctly
* ACIs modified to enable DelAdmin \ Delegator to work correctly
* `proxied-auth` rights granted to the `cn=pingfederate` service account