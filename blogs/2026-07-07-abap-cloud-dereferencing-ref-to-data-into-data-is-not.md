---
title: "ABAP Cloud dereferencing REF TO DATA into DATA is not working for not released data types"
url: "https://community.sap.com/t5/abap-forum/abap-cloud-dereferencing-ref-to-data-into-data-is-not-working-for-not/m-p/14435295#M1084"
date: "2026-07-07"
author: "Yrfo"
feed_url: "https://community.sap.com:443/khhcw49343/rss/Community?interaction.style=forum"
---
I faced one behavior in BTP ABAP Cloud, which I find weird. Maybe someone can bring more info on the topic. Imaging we have: software component A - generic tool for something, and can work on generic data type software component B - want to use the tool from A If I do the tool to accept this data as data ref REF TO data, and this assignment fails in case B sends data ref to not released type (without released API contract).
