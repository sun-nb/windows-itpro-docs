---
title: Windows 10 Pro in S mode
description: Overview of Windows 10 Pro/Enterprise in S mode. What is S mode for Enterprise customers? 
keywords: Windows 10 S, S mode, Windows S mode, Windows 10 S mode, S-mode, system requirements, Overview, Windows 10 Pro in S mode, Windows 10 Enterprise in S mode, Windows 10 Pro/Enterprise in S mode
ms.mktglfcycl: deploy
ms.localizationpriority: medium
ms.prod: w10
ms.sitesec: library
ms.pagetype: deploy
ms.date: 10/02/2018
author: Mikeblodge
---

# Windows 10 in S mode - What is it?
S mode is an evolution of the S SKU introduced with Windows 10 April 2018 Update. It's a configuration that's available on all Windows Editions when enabled at the time of manufacturing. The edition of Windows can be upgrade at any time as shown below. However, the switch from S mode is a onetime switch and can only be undone by a wipe and reload of the OS. 

![Configuration and features of S mode](images/smodeconfig.png)

## S mode key features
**Microsoft-verified security**

With Windows 10 in S mode, you’ll find your favorite applications, such as Office, Evernote, and Spotify in the Microsoft Store where they’re Microsoft-verified for security. You can also feel secure when you’re online. Microsoft Edge, your default browser, gives you protection against phishing and socially-engineered malware. 

**Performance that lasts**

Start-ups are quick, and S mode is built to keep them that way. With Microsoft Edge as your browser, your online experience is fast and secure. Plus, you’ll enjoy a smooth, responsive experience, whether you’re streaming HD video, opening apps, or being productive on the go. 

**Choice and flexibility**

Save your files to your favorite cloud, like OneDrive or Dropbox, and access them from any device you choose. Browse the Microsoft Store for thousands of apps, and if you don’t find exactly what you want, you can easily [switch out of S mode](https://docs.microsoft.com/en-us/windows/deployment/windows-10-pro-in-s-mode) at any time and search the web for more choices. 

![Switching out of S mode flow chart](images/s-mode-flow-chart.png)


## Deployment
Windows 10 S mode is built for [Modern Management](https://docs.microsoft.com/en-us/windows/client-management/manage-windows-10-in-your-organization-modern-management) which means using [Windows Auto Pilot](https://docs.microsoft.com/en-us/windows/deployment/windows-autopilot/windows-10-autopilot). The best way to start using an S mode device is to embrace Modern Management fully when designing the deployment plan. Windows Auto Pilot allows you to deploy the deivce directly to the employee without having to touch the physical device. Instead of manually deploying a custom image to a machine, Windows Auto Pilot will start with a generic PC that can only be used to join the company domain; Polices are then deployed automatically through Modern Device Management.

![Windows auto pilot work flow](images/autopilotworkflow.png)

## Related links

- [Consumer applications for S mode](https://www.microsoft.com/en-us/windows/s-mode)
- [S mode devices](https://www.microsoft.com/en-us/windows/view-all-devices)
- [Windows Defender Application Control deployment guide](https://docs.microsoft.com/en-us/windows/security/threat-protection/windows-defender-application-control/windows-defender-application-control-deployment-guide)
- [Windows Defender Advanced Threat Protection](https://www.microsoft.com/en-us/WindowsForBusiness/windows-atp)