# igmpproxy
igmpproxy for OpenWRT. 

Now some default parameters could be modified :<br>
DEFAULT_ROBUSTNESS<br>
DEFAULT_INTERVAL_QUERY<br>
DEFAULT_INTERVAL_QUERY_RESPONSE<br>

## Usage:
Replace package/network/services/igmpproxy before compiling<br><br>

### Modify:
At /etc/config/igmpproxy :<br>
option robustness xx<br>
option interval_query xx<br>
option interval_query_response xx<br>
