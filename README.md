# Deployment template for autoscaled custom image vmss

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2signiant%2Fazure-vmss-linux-custom%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a><a  target="_blank">

This template allows you to deploy an autoscaled VM Scale Set of Linux VMs based of an existing custom image.  The load balancers and vms should be assigned public IPs 

PARAMETER RESTRICTIONS
======================

VM and VMSS names must be 9 characters in length or shorter. It should also be globally unique across all of Azure.
