# gcp_oci_vm_start
HHA 504 Module 1 Assignment - Intro to Cloud GCP and OCI

# VM Lifecycle on GCP and OCI — Tutorial

## Video
Loom/Zoom: (https://www.loom.com/share/654bef0cf26547828b2a73d22ecbca25?sid=85b7a010-767f-4238-af58-b876d359b40d)

## Prereqs
- Cloud access to GCP and OCI
- No PHI/PII; smallest/free-tier shapes

---

## Google Cloud (GCP)
### Create
1. Console → Compute Engine → Create instance
2. Region/zone: <your choice>
3. Machine type: <smallest available/free-eligible>
4. Image: Ubuntu LTS
5. Boot disk: default minimal
6. Network: default VPC; ephemeral public IP


### Delete
- Delete instance and verify no disks/IPs remain

---

## Oracle Cloud (OCI)
### Create
1. Compartment: <name>
2. Networking: VCN with Internet Connectivity (defaults)
3. Shape: <smallest/free-eligible>
4. Image: Ubuntu (or Oracle Linux)
5. Public IP: ephemeral
6. Boot volume: default minimal

### Terminate
- Terminate and delete boot volume; verify cleanup

---

## Reflections
### Similarities
- Fairly easy plug and play setup
- Affordable pricing

### Differences
- Google UI was easier to navigate in my opinion
- Oracle had a cheaper bottomline price
- Google had slower processing navigating tabs
- Oracle had a slower time creating VM 

### Preference (OCI vs GCP) and Why
- I prefer using Google Cloud over Oracle because the interface is much more user-friendly and intuitive. Navigating through the dashboard feels straightforward, and I can quickly find the tools and services I need without confusion. The overall setup and configuration process also seemed easier to understand, making it less overwhelming compared to Oracle’s platform. This simplicity helps me focus more on building and running my VM rather than figuring out the platform itself.