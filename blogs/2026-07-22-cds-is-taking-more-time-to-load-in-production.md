---
title: "CDS is taking more time to load in Production"
url: "https://community.sap.com/t5/abap-forum/cds-is-taking-more-time-to-load-in-production/m-p/14446703#M1120"
date: "2026-07-22"
author: "Abhi9"
feed_url: "https://community.sap.com:443/khhcw49343/rss/Community?interaction.style=forum"
---
Hi , I have a CDS which is taking more than 40 seconds and sometime even more time to load the data or filter the data. Is there any way in ABAP CDS to achieve behavior similar to SAP table buffering for small, rarely changing configuration/customizing tables, so that repeated accesses are served from a buffer/cache instead of triggering database reads each time? If the data has already been fetched from the CDS view and we apply an additional filter for records that are already present in the fetched result set, the CDS query appears to trigger another database call.
