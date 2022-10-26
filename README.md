# SMC or Insyde BMC software stack golang build Redfish tool
Golang wrote Supermicro or Insyde SuperVise Redfish app.  Easy, no dependence in Ubuntu, CentOS and Windows

$ sudo ./smc_sysinfoMAC 10.100.200.300 root root system | jq

Available query function are [system | sel | chassis | processor | memory | nic | psu | power | thermal | bmc | all]
