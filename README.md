# manage-hyperv-switch
change hyperv switch for all virtual machines

Get-VM –computername ‘hypervhostname’ | ForEach-Object {Connect-VMNetworkAdapter -VMName($_.Name) -SwitchName "netname"}

have a look on 
http://blog.it-koehler.com/Archive/952
