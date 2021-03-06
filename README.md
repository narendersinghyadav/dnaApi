# dna
**Module Overview:**

This module will interact with Tor to get real time statistical and analytical information.

|-is_alive - check tor process is alive or killed.<br/>
|-is_valid_ipv4_address-check for valid ip address.<br/>
|-authenticate- cookie authentication of control port.<br/>
|-get_version- get version of tor. <br/>
|-get_pid- find pid of tor service.<br/>
|-get_info- get information like version,exit policy,network status etc.<br/>
|-set_conf- change the value of one or more configurable variable.<br/>
|-reset_conf-set the configurable variable to default values.<br/>
|-get_conf- Request the value of zero or more configuration variable.<br/>
|-get_ports- retreive informations about listeners of different ports.<br/>
|-get_network_statuses- Router status info (v3 directory style) for all ORs.<br/>
|-get_exit_policy-The default exit policy lines that Tor will *append* to the ExitPolicy config option.<br/>
|-prt_check-check validity of ports.<br/>
|-can_exit_to- check whether one can exit through a particular port.<br/>
|-get_circuit- get information about circuits present for use.<br/>
|-port_usage-Usage of particular port.<br/>
|-get_info_relay- retrieve information from database about a particular relay.<br/>
|-status-tell status of a circuit BUILT or not.<br/>
|-build_flag- build flag on circuit and relays.<br/>
|-path- return path of circuit.<br/>
|-created- circuit created info.<br/>
|-signal-signal control port like NEWNYM,RELOAD etc.<br/>
|-get_fingerprint-the contents of the fingerprint file that Tor writes as a relay, or a 551 if we're not a relay currently.<br/>
|-get_network_status-network status of a relay with given fingerprint.<br/>
