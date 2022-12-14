## Objectives

This repo will be used to deliver FastTrack for Azure sessions to Hybrid customers in Asia. Technologies include Azure Stack HCI and Azure Arc.

## Resources by engagement

- Building an Azure Stack HCI lab for PoC or Readiness purposes. Two options:
  - [Evaluate Azure Stack HCI using an Azure VM](https://docs.microsoft.com/en-us/azure-stack/hci/guided-quick-deploy-eval?tabs=cloud-app-admin)
    - No hardware required
    - An Azure VM is used as a Hyper-V Host with guest VMs:
      - 1x VM as the Windows Admin Center
      - 2x VMs as HCI Cluster Nodes
  - [VM-based ](https://docs.microsoft.com/en-us/azure-stack/hci/deploy/tutorial-private-forest)
    - Non-Azure Hyper-V Host
- Azure Stack HCI architecture review
  - Delivery outline
    - Review Architecture
    - Review Hardware configuration
      - [Azure Stack HCI Hardware Catalogue](https://hcicatalog.azurewebsites.net/#/)
      - [Azure Stack HCI Hardware Sizing](https://azurestackhcisolutions.azure.microsoft.com/#/sizer)
      - [System requirements](https://docs.microsoft.com/en-us/azure-stack/hci/concepts/system-requirements)
      - [Physical Network Requirements](https://docs.microsoft.com/en-us/azure-stack/hci/concepts/physical-network-requirements)
    - Discuss Architecture changes
  - References
- HCI Datacenter Integration
  - Delivery outline
    - Discuss Network and Active Directory Integration
    - Deployment Best Practice 
    - Windows Admin Center for Azure Stack HCI
    - Discuss Storage Best Practices
  - References
- Azure Stack HCI governance
  - Delivery outline
    - CAF & Hybrid
    - Windows Admin Center and Azure Portal
      - [Get started with Azure Stack HCI and Windows Admin Center](https://docs.microsoft.com/en-us/azure-stack/hci/get-started)
    - Naming / Tagging / RBAC & Policy
    - Cost Management
  - References
- Cluster Config and Azure integration Review
  - Delivery outline
    - [HCI Cluster Create](https://docs.microsoft.com/en-us/azure-stack/hci/deploy/deployment-quickstart)
    - Review deployed cluster config and cluster health
    - Review Azure AD integration HCI
    - Review Azure AD integration Admin Center
  - References
 - Azure Stack Migration
    - [Migrate to Azure Stack HCI on same hardware](https://docs.microsoft.com/en-us/azure-stack/hci/deploy/migrate-cluster-same-hardware)
    - [Migrate to Azure Stack HCI on new hardware - Azure Stack HCI](https://docs.microsoft.com/en-us/azure-stack/hci/deploy/migrate-cluster-new-hardware)

## To check if work is already under way, and recommend/develop if not

- [Azure review-checklist](https://github.com/Azure/review-checklists) package for HCI
- [Cloud Roles and Operations Management](https://github.com/Azure/cloud-rolesandops) package for HCI

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.

## Security

Microsoft takes the security of our software products and services seriously, which includes all source code repositories managed through our GitHub organizations, which include [Microsoft](https://github.com/Microsoft), [Azure](https://github.com/Azure), [DotNet](https://github.com/dotnet), [AspNet](https://github.com/aspnet), [Xamarin](https://github.com/xamarin), and [our GitHub organizations](https://opensource.microsoft.com/).

If you believe you have found a security vulnerability in any Microsoft-owned repository that meets [Microsoft's definition of a security vulnerability](https://docs.microsoft.com/en-us/previous-versions/tn-archive/cc751383(v=technet.10)), please report it to us as described below.

## Reporting Security Issues

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, please report them to the Microsoft Security Response Center (MSRC) at [https://msrc.microsoft.com/create-report](https://msrc.microsoft.com/create-report).

If you prefer to submit without logging in, send email to [secure@microsoft.com](mailto:secure@microsoft.com).  If possible, encrypt your message with our PGP key; please download it from the [Microsoft Security Response Center PGP Key page](https://www.microsoft.com/en-us/msrc/pgp-key-msrc).

You should receive a response within 24 hours. If for some reason you do not, please follow up via email to ensure we received your original message. Additional information can be found at [microsoft.com/msrc](https://www.microsoft.com/msrc).

Please include the requested information listed below (as much as you can provide) to help us better understand the nature and scope of the possible issue:

  * Type of issue (e.g. buffer overflow, SQL injection, cross-site scripting, etc.)
  * Full paths of source file(s) related to the manifestation of the issue
  * The location of the affected source code (tag/branch/commit or direct URL)
  * Any special configuration required to reproduce the issue
  * Step-by-step instructions to reproduce the issue
  * Proof-of-concept or exploit code (if possible)
  * Impact of the issue, including how an attacker might exploit the issue

This information will help us triage your report more quickly.

If you are reporting for a bug bounty, more complete reports can contribute to a higher bounty award. Please visit our [Microsoft Bug Bounty Program](https://microsoft.com/msrc/bounty) page for more details about our active programs.

## Preferred Languages

We prefer all communications to be in English.

## Policy

Microsoft follows the principle of [Coordinated Vulnerability Disclosure](https://www.microsoft.com/en-us/msrc/cvd).
