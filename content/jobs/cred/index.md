---
date: "2024-01-16"
title: "Backend Intern"
company: "CRED"
location: "Banglore, India"
range: "Jan - July 2024"
url: "https://cred.club/"
---

- Worked in the consumer payment processes team focusing on scan-and-pay and peer-to-peer payments. Built a new service
for handling beneficiary creation by listening to SQS events to manage beneficiaries, applying deduplication on VPAs and phone
numbers to show recent history, and built a search API that can list based on various filters like account type, beneficiary type,
and sort on various fields like last transacted time and updated at time.
- Part of developing a feature for pinning contacts to improve
M1 retention of New Transacting Users by 20-25%, aiming to increase the transactions per user in a month. Additionally
improved test coverage of the service from 10% to 90%. 
- Developed a configuration management module for scan-and-pay and peer-to-peer payments, aiming to centralize rule
management and enable UI configurability within the application. Revamped the UPI collect flow to improve SR by 5% and
discoverability by 10%
- Enhanced CPU utilization in case if any downstream services are down, the Hystrix thread now aborts as
SocketTimeoutException is raised, each API call has been configured with certain socket timeout, preventing the Hystrix
thread pool from becoming saturated
