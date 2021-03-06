# Stacks

The **Stacks** page lists all compute nodes:

![](../../.gitbook/assets/stacks%20%282%29.png)

Clicking the **ID** of a compute node brings you to the **Stack Details** page for that node:

![](../../.gitbook/assets/stackdetails.png)

From the **Actions** dropdown menu you can:

* [Put the node in Maintenance Mode](../sysadmin/putting_node_in_maintenance_mode.md)
* [Decommission the node](../sysadmin/decommission_node.md)

The **Status** of a node is one of the following:

* **Enabled**
* **Maintenance**
* **Decommissioned**
* **Error** with a hyperlink to an error condition

> **Note**: a node will only show to be in **Error** state as a result of a failing action or when a virtual machine deployment fails on that node. Any other problem with the compute node, such as for example when the network got disconnected, will not change the status to **Error**. For the actual state of the node always check the [Status Overview](../gridportal/statusoverview.md) page for that node in the **Grid Portal**, since the **Cloud Broker Portal** rather shows the desired state, not the actual condition \(reality\) as the **Grid Portal** does.

Under **Images** all OS images available on the compute node are listed:

![](../../.gitbook/assets/images.png)

From there you can navigate to the **Image Details** page for a specific OS image.

Next all virtual firewalls running on that compute node are listed:

![](../../.gitbook/assets/virtualfirewalls.png)

Clicking the **ID** of a virtual firewall will navigate you to **Private Network Details** page for that virtual firewall, and clicking the **Cloud Space ID** links to the **Cloud Space Details** page of the associated cloud space.

Under **Virtual Machines** all virtual machines running on the compute node are listed:

![](../../.gitbook/assets/virtualmachines%20%284%29.png)

By clicking on the **Name** of the virtual machine you navigate to the **Virtual Machines Details** page of that virtual machine.

