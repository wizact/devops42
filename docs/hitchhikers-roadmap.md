---
layout: post
title: Hitchhiker's Roadmap
published: true
order: 2
permalink: hitchhikers-roadmap.html
---

Phase 0
------------------------------------
#### Metrics
   - Throughput
       - Increase deployment frequency
       - Decrease lead time
   - Stability
       - Faster recovery time
       - Lower failure rate
	   
#### Culture
   - High trust organisation & mission command
   - Version-control everything
   - Automate everything
   - Build quality in the product & everyone is responsible for quality
   - You build it, you release it, you fix it
   - Evolutionary architecture rather than big bang

Phase 1
------------------------------------
- Build Pipeline for CD
   - To enable TBD and continuous commits to the mainline 
- Infra-as-code
- Automation Testing 0 (Unit Test)

Phase 2
------------------------------------
- Automation Testing 1 (Integration Test)
- Centralised Logging/Correlation
- Build pipeline for Infra-as-code

Phase 3
------------------------------------
- Trunk-Based Development
- Canary Release/Blue Green for Serverless/ECS
- Automation Testing 2 (System Test)

Phase 4
------------------------------------
- Configuration Management & Auditing
   - Config-as-code
   - Audit changes on services
- Alerting

Phase 5
------------------------------------
- Automation Testing 4 (Synthetic testing)
   - Automated Synthetic in prod and alerting

Phase 6
------------------------------------
- Automation Testing 5 (Performance testing)
   - Build performance testing in build pipeline
- Metric Tracking Across Services

Phase 7
------------------------------------
- DiRT Planning
   - Incident Response Planning
   - Chaos Troop
   - Graceful fail-over