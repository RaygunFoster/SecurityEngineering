# Azure Secure Lab

## Objective

Build a secure Azure environment applying networking, IAM and monitoring best practices.

## Architecture

- Resource Group
- VNet segmented
- Web subnet
- Admin subnet
- Linux VM
- NSG restricted by IP
- Logging enabled

## Security Controls

- SSH limited to my IP
- Least privilege RBAC
- Activity logs enabled
- Public exposure minimized

## Screenshots

(agregar imágenes)

## Lessons Learned

- Difference between NSG and subnet segmentation
- Azure IAM inheritance model
- Cost control importance

## Future Improvements

- Terraform deployment
- Defender for Cloud
- Sentinel integration
