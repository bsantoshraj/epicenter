epicenter
=========

epicenter - a centralized infrastructure management suite


The following pieces need to be glued together:

1. chef for provisioning/deployment. need to also factor alternates such as ansible and puppet
2. IPMI for baremetal access on sideband and out of band control
2. pxe with dhcp and dns for installation on undercloud
3. openstack for public/private/hybrid cloud autoscale
4. aws for private cloud autoscale
5. WebUI for dynamic transition of roles/scheduling of roles
6. glue code for integration with NMS
7. web metrics via highcharts
8. prototyping on vagrant for all other modules other than IPMI since IPMI is based on physical boxes.
