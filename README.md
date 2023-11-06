 # ACI - Ansible reference 

### bd-create.yaml
Creates a bridge domain object under an existing tenant and VRF. Variables specified in the yaml: **Tenant** name, **VRF** name and the name of the **BD** 

### tn-vrf-bd-create.yaml
Creates Tenant, VRF and BD. Variables specified in the yaml: **Tenant** name, **VRF** name and the name of the **BD** 

### bd-creare-from-file.yaml
BDs created form bd.txt csv file


### epg-query.yaml
Gets the list of configured EPGs and exports to a file: fvAEPg.list. 
Parsing json variable with jamesquery

### epg-query-nati.yaml
parsing json variable native ansible nested variable reference


### app-service-create
Creates a complete DC network service for a two tier application. Creates Frontend and Backend EPG both EPGs added to vmware DVS. Input parameers stored in the ext_vars vile: App Name or **App ID**, **Tenant**, **Bridge domain** name and the name of the **DVS** in VMware
