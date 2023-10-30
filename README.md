# vswitch-api
Virtual Switch API to configure k8s secondary network datapaths


## Network service API
 - Defines the set of flows an application will process
   - 5 tuples (local/remote IP, local/remote port, protocol)
 - What kind of networking backend does the application need
   - DPDK (VFIO), Kernel
   - Vswitch type: OVS, VPP, custom vswitch implementation
 - Opaque set of capabilities specific to the vswitch used
