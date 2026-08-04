---
title: "SAP BTP Trial (us10-001) - CAP MTA deployment stuck in STAGING, droplet not created"
url: "https://community.sap.com/t5/sap-cap-forum/sap-btp-trial-us10-001-cap-mta-deployment-stuck-in-staging-droplet-not/m-p/14446805#M90"
date: "2026-07-23"
author: "deepak3830"
feed_url: "https://community.sap.com:443/khhcw49343/rss/Community?interaction.style=forum"
---
Hello Experts, I am facing a deployment issue on an SAP BTP Trial account (Cloud Foundry region us10-001). Environment ----------- BTP Trial Account Cloud Foundry Runtime Region: us10-001 SAP BAS @SAP /cds: 9.9.1 @SAP /cds-dk: 9.9.3 MBT: 1.2.34 Issue ----- My CAP application builds successfully and the MTAR is generated without errors. Commands executed: mbt build Output: - cds build completed successfully - MTAR created successfully - mta_archives/mycapapp_1.0.0.mtar generated Deployment ---------- cf deploy mta_archives/mycapapp_1.0.0.mtar Deployment progresses to: Creating application "myca
