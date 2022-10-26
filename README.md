# SuperMicro_Redfish
Golang wrote Supermicro Redfish app.  Easy, no dependence in Ubuntu, CentOS and Windows

$ sudo ./smc_sysinfoMAC 10.100.200.300 root root system | jq

Available query function are [system | sel | chassis | processor | memory | nic | psu | power | thermal | bmc | all]
