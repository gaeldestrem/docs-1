## Summary

* [Introduction](README.md)
* [Architecture](Architecture/Architecture.md)
  * [System Architecture](Architecture/SystemArchitecture.md)
  * [Network](Architecture/Network/Network.md)
    * [Physical Network](Architecture/Network/PhysicalNetwork.md)
    * [Logical Network](Architecture/Network/LogicalNetwork.md)
    * [Internal Node Network](Architecture/Network/InternalNodeNetwork.md)
* [Cloud Broker Portal](CloudBrokerPortal/CloudBrokerPortal.md)
  * [Home](CloudBrokerPortal/Home/Home.md)
  * [Accounts](CloudBrokerPortal/Accounts/Accounts.md)
  * [Cloud Spaces](CloudBrokerPortal/CloudSpaces/CloudSpaces.md)
  * [Groups](CloudBrokerPortal/Groups/Groups.md)
  * [Locations](CloudBrokerPortal/Locations/Locations.md)
  * [Images](CloudBrokerPortal/Images/Images.md)
  * [Private Networks](CloudBrokerPortal/PrivateNetworks/PrivateNetworks.md)
  * [External Networks](CloudBrokerPortal/ExternalNetworks/ExternalNetworks.md)
  * [Stacks](CloudBrokerPortal/Stacks/Stacks.md)
  * [Users](CloudBrokerPortal/Users/Users.md)
  * [Virtual Machines](CloudBrokerPortal/VirtualMachines/VirtualMachines.md)
    * [Move to another CPU node](CloudBrokerPortal/VirtualMachines/Actions/MoveVM2AnotherCPUNode.md)
* [Statistics](Statistics/Statistics.md)
* [Grid Portal](GridPortal/GridPortal.md)
  * [Home](GridPortal/Home/Home.md)
  * [Audits](GridPortal/Audits/Audits.md)
  * [Error Conditions](GridPortal/ErrorConditions/ErrorConditions.md)
  * [Jobs](GridPortal/Jobs/Jobs.md)
  * [Job Queues](GridPortal/JobQueues/JobQueues.md)
  * [JumpScripts](GridPortal/JumpScripts/JumpScripts.md)
  * [Logs](GridPortal/Logs/Logs.md)
  * [Grid Nodes](GridPortal/GridNodes/GridNodes.md)
  * [Status Overview](GridPortal/StatusOverview/StatusOverview.md)
  * [Virtual Machines](GridPortal/VirtualMachines/VirtualMachines.md)
* [End User Portal](EndUserPortal/EndUserPortal.md)
  * [Home](EndUserPortal/Home/Home.md)
  * [Authorization Model](EndUserPortal/Authorization/AuthorizationModel.md)
  * [Cloud Space Settings](EndUserPortal/CloudSpaceSettings/CloudSpaceSettings.md)
  * [Machines](EndUserPortal/Machines/Machines.md)
  * [Defense Shield](EndUserPortal/DefenseShield/DefenseShield.md)
  * [Getting Started](EndUserPortal/GettingStarted/GettingStarted.md)
  * [Machine API](EndUserPortal/MachineAPI/MachineAPI.md)
  * [Knowledge Base](EndUserPortal/KnowledgeBase/KnowledgeBase.md)
* [Installation of an OpenvCloud Environment](Installation/README.md)
  * [System configuration](Installation/System-config.md)
  * [Installation](Installation/Installation.md)
    * [Installer script manual](Installation/Installer-script.md)
  * [Pre 2.3.0 upgrade](Installation/Migration.md)
    * [Upgrade script manual](Installation/Migration-script.md)
* [Adding, Replacing & Removing Hardware](Installation/Hardware/Hardware.md)
  * [Nodes](Hardware/Nodes/Nodes.md)
    * [OVS Node](Hardware/Nodes/OVS-Node.md)
    * [CPU Node](Hardware/Nodes/CPU-Node.md)
    * [Storage Node](Hardware/Nodes/Storage-Node.md)
  * [Hardware Components](Hardware/Components/Components.md)
    * [SSD](Hardware/Components/SSD.md)
    * [NVMe](Hardware/Components/NVME.md)
    * [Backend Disk](Hardware/Components/Backend-Disk.md)
  * [Network Devices](Hardware/Network-Devices/Network-Devices.md)
    * [Mellanox](Hardware/Network-Devices/Mellanox.md)
* [Update an OpenvCloud Environment](Upgrade/Upgrade.md)
  * [Update the Master Cloud Space](Upgrade/MasterCloudSpace/update_master_cloud_space.md)
  * [Update All CPU Nodes](Upgrade/CPUNodes/update_cpu_nodes.md)
  * [Commit Changes and Report Back](Upgrade/CommitChanges/CommitChanges.md)
  * [Update Open vStorage](Upgrade/OVS/update_ovs.md)
* [Monitoring](Monitoring/README.md)
  * [System Health](Monitoring/Health/Health.md)
  * [Gathering of Statistics](Monitoring/Statistics/Statistics.md)
  * [Create Custom Dashboards](Monitoring/Dashboards/create_custom_dashboards.md)
  * [External Network Addresses](Monitoring/Network/Network.md)
  * [Storage Utilization](Monitoring/Storage/Storage.md)
  * [Resource Consumption Tracking](Monitoring/ResourceTracking/README.md)
  * [Review Logs for User Operations & Automated Tasks](Monitoring/Logs/Logs.md)
  * [Review Audit Logs for Security Alerts](Monitoring/Audits/Audits.md)
* [System Administration](Sysadmin/sysadmin.md)
  * [User Management](Sysadmin/UserManagement/user_management.md)
  * [Connect to an Environment](Sysadmin/Connect/connect.md)
    * [Teleport](Sysadmin/Connect/teleport.md)
    * [0-Accesst](Sysadmin/Connect/0access.md)
  * [Preparing Before Connection](Sysadmin/Connect/preparing_before_connecting.md)
  * [Create a New Windows Image](Sysadmin/Images/Creating_new_Windows_Image.md)
  * [Deploy a New Image](Sysadmin/Images/deploy_new_image.md)
  * [Making Images Private](Sysadmin/Images/private_images.md)
  * [Putting a Node in Maintenance Mode](Sysadmin/Maintenance/putting_node_in_maintenance_mode.md)
  * [Decommission a Node](Sysadmin/Decommission/decommission_node.md)
  * [Moving Virtual Machines to Another CPU Node](Sysadmin/MovingVM/moving_vms.md)
  * [Configure Network Devices](Sysadmin/ConfigureNetworkDevices/configure_network_devices.md)
  * [Backend Encryption](Sysadmin/BackendEncryption/backend_encryption.md)
  * [Advanced Configuration](Sysadmin/AdvancedConfiguration/AdvancedConfiguration.md)
* [Testing](Testing/Testing.md)
* [Branding](Branding/Branding.md)
  * [How to Change Logo on Portals](Branding/change_logo.md)
* [API](API/README.md)
  * [Getting started with the OpenvCloud Cloud API](API/GettingStarted.md)
  * [Create Static API Documentation Site](API/GettingStarted.md)