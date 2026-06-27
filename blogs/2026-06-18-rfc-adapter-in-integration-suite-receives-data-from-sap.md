---
title: "RFC adapter in Integration Suite receives data from SAP backend but drops payload"
url: "https://community.sap.com/t5/integration-forum/rfc-adapter-in-integration-suite-receives-data-from-sap-backend-but-drops/m-p/14422804#M335"
date: "2026-06-18"
author: "Erick_Grilo23"
feed_url: "https://community.sap.com:443/khhcw49343/rss/Community?interaction.style=forum"
---
A technical issue reported where an RFC adapter receives approximately 4,000 lines (3MB payload) from an ECC backend but fails to return data. Pagination resolves the problem, suggesting size limitations. The payload drops at the RFC step before XML conversion, and documentation consultation has not resolved the issue.
