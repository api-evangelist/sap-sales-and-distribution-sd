---
title: "Error calling API_BUSINESS_PARTNER via Communication Arrangement in S/4HANA Public Cloud"
url: "https://community.sap.com/t5/abap-forum/error-calling-api-business-partner-via-communication-arrangement-in-s-4hana/m-p/14435427#M1087"
date: "2026-07-07"
author: "Ainun"
feed_url: "https://community.sap.com:443/khhcw49343/rss/Community?interaction.style=forum"
---
Hi Experts, I am trying to consume the standard API_BUSINESS_PARTNER service from ABAP Cloud in SAP S/4HANA Public Cloud. I have already completed the following: Created the Communication System Created the Communication Arrangement using SAP_COM_0008 Activated the service Generated a Service Consumption Model from the service metadata Implemented the API call in ABAP Cloud I am using: lo_destination = cl_http_destination_provider=>create_by_comm_arrangement( comm_scenario = 'SAP_COM_0008' comm_system_id = ' CS_EINVOICE_SAP_COM_0008' service_id = ' API_BUSINESS_PARTNER_0001_IWSG ' ). However, 
