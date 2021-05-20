# Clone-AzVM
Clones azure VM including availability sets, disks, ips, supports cross-region and cross-subscription without requiring vnet move

Sample:
.\clone-azvm.ps1 -sourceResourceGroupName movetest -sourceSubscriptionId xxx -sourceVmName movetest-av1 -destinationVNetName movetest -destinationVNetResourceGroupName movetestpayg -destinationResourceGroupName movetestpayg -destinationSubnetName vms -destinationSubscriptionId yyy
