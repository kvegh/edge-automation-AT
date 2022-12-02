# edge-automation-AT
edge-automation-AT

# Goal of the project: 

## Provide a self-installing RHEL image to Edge usecases. 

The image should be registering itself after installation by the first boot at a cerntral single source of truth instance, that is accessible by AAP (Ansible Automation Platform's Automation Controller) as an inventory. 

## Milestones defined: 

1. Have a RHEL Image Bilder Template, that can be used to build different image formats (done and tested for x86). 
2. Build it in rpm-ostree format (rhel-edge) too. 
3. Create the bootscript, assume Public IP at this stage for registration/connection. 
4. Push updates and/or workload (containers) to the device. 
5. Port the template to ARM (still VM!) too 
6. Create a HW-bootable ISO image (both HW platforms) and optional: Azure/AWS VM images too. 
7. Consider options for Ansible communication in case the Edge device doesn't have a public IP. 
