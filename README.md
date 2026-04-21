<!--  CLIFFORDSON CETOUTE · Automation & Systems Engineer · Labs & Flows  -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1a22,40:1b2932,100:0d1a22&height=220&section=header&text=Cliffordson%20Cetoute&fontSize=46&fontColor=d3b58e&fontAlignY=40&desc=Automation%20%26%20Systems%20Engineer%20%20%C2%B7%20%20Founder%20%40%20Labs%20%26%20Flows&descSize=16&descAlignY=62&descColor=8a7050&animation=fadeIn" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Sora&weight=500&size=16&duration=2800&pause=1400&color=8A9BA8&center=true&vCenter=true&width=680&lines=Building+systems+that+run+while+you+sleep.;Pipelines+that+recover+from+their+own+failures.;Infrastructure+that+scales+without+you." />

<br/>

<a href="https://www.linkedin.com/in/cliffordson-cetoute-264411348/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-1B2932?style=for-the-badge&logo=linkedin&logoColor=d3b58e&labelColor=1B2932"/>
</a>
&nbsp;
<a href="mailto:cliffordsoncetoute004@gmail.com" target="_blank">
  <img src="https://img.shields.io/badge/Gmail-1B2932?style=for-the-badge&logo=gmail&logoColor=d3b58e&labelColor=1B2932"/>
</a>
&nbsp;
<a href="https://labsandflows.com.br" target="_blank">
  <img src="https://img.shields.io/badge/Labs_%26_Flows-1B2932?style=for-the-badge&logo=vercel&logoColor=d3b58e&labelColor=1B2932"/>
</a>

</div>

<br/>

---

<br/>

<div align="center">

```
  I don't build demos.
  I build systems with queues, retries, audit logs, and failure recovery.
  Systems that are still running months after deployment.
  That's the difference.
```

</div>

<br/><br/>

---

<br/>

## Core Engineering

<br/>

<div align="center">
<table border="0" cellpadding="0" cellspacing="0" width="94%">
<tr valign="top">
<td width="48%">

```yaml
WORKFLOW AUTOMATION:
  - n8n multi-step flows, production grade
  - Event-driven arch with async queues
  - Retry logic and dead-letter queues
  - Webhook triggers & scheduled jobs
  - Full execution logging at scale
```

```yaml
BACKEND ORCHESTRATION:
  - Document processing pipeline design
  - REST & webhook integration patterns
  - Queue-based async job management
  - Error isolation & fault boundaries
  - API normalization across systems
```

</td>
<td width="4%"></td>
<td width="48%">

```yaml
DATA & STORAGE:
  - Relational schema design (Supabase/PG)
  - High-volume document pipelines
  - Audit trails & status tracking
  - Data integrity patterns at scale
  - Structured flows with validation layers
```

```yaml
INFRASTRUCTURE:
  - Multi-VPS production management
  - Deployment, monitoring, maintenance
  - Health checks & anomaly alerting
  - Log aggregation across services
  - Observable, fault-tolerant design
```

</td>
</tr>
</table>
</div>

<br/><br/>

---

<br/>

## Tech Stack

<br/>

<div align="center">

<sub>AUTOMATION CORE</sub>

<img src="https://skillicons.dev/icons?i=nodejs,linux,docker&theme=dark" height="46"/>&nbsp;&nbsp;<img src="https://img.shields.io/badge/n8n-1B2932?style=flat-square&logo=n8n&logoColor=EF4E3E" height="46" style="border-radius:10px"/>

<br/><br/>

<sub>DATA & BACKEND</sub>

<img src="https://skillicons.dev/icons?i=supabase,postgres,js,ts&theme=dark" height="46"/>

<br/><br/>

<sub>FRONTEND & INTERFACES</sub>

<img src="https://skillicons.dev/icons?i=nextjs,react,tailwind,figma&theme=dark" height="46"/>

<br/><br/>

<sub>TOOLS & CLOUD</sub>

<img src="https://skillicons.dev/icons?i=git,vscode,postman&theme=dark" height="46"/>&nbsp;&nbsp;<img src="https://img.shields.io/badge/Oracle%20Cloud-1B2932?style=flat-square&logo=oracle&logoColor=F80000" height="46" style="border-radius:10px"/>

</div>

<br/><br/>

---

<br/>

## Systems I've Built

<p align="center"><sub>Production systems — not tutorials, not demos.</sub></p>

<br/>

```
╔══════════════════════════════════════════════════════════════════════════╗
║  01 · LARGE-SCALE DOCUMENT PROCESSING PIPELINE                          ║
║  n8n · Supabase · Queues · Webhooks · Dead-letter pattern               ║
╚══════════════════════════════════════════════════════════════════════════╝

  Problem → Thousands of documents needed to be classified, extracted
            and stored automatically, with zero tolerance for silent
            failures and without any manual intervention.

  INGEST    →  Webhook triggers feed a prioritized processing queue
  PROCESS   →  n8n: classify · extract · transform · validate
  STORE     →  Supabase with relational schemas + full audit log
  RECOVER   →  Dead-letter queues + automatic retry on failure
  OBSERVE   →  Per-document status tracking + full execution history

  Result    →  Self-healing pipeline. Running in production.
               Observable from day one.
```

<br/>

```
╔══════════════════════════════════════════════════════════════════════════╗
║  02 · MULTI-SYSTEM API INTEGRATION LAYER                                ║
║  REST · Webhooks · Normalization · Error Isolation · Logging            ║
╚══════════════════════════════════════════════════════════════════════════╝

  Problem → Multiple external systems — different APIs, auth models,
            schemas — needing real-time sync without one failure
            bringing down the rest.

  RECEIVE    →  Webhook receivers + polling jobs — real-time & batch
  NORMALIZE  →  Translation layer to unify data models across systems
  ISOLATE    →  Error boundaries — a failing integration stays contained
  LOG        →  Centralized logging: API calls, responses, retries
  SCALE      →  Modular — add new integrations without refactoring

  Result     →  Decoupled integration backbone that handles edge
                cases without drama.
```

<br/>

```
╔══════════════════════════════════════════════════════════════════════════╗
║  03 · PRODUCTION AUTOMATION INFRA — LABS & FLOWS                        ║
║  Multi-VPS · Monitoring · Deployment · Self-healing · Log Aggregation   ║
╚══════════════════════════════════════════════════════════════════════════╝

  Problem → Multiple environments in production — different workloads,
            uptime SLAs, release cycles — managed by one person,
            zero ops team.

  SEGMENT    →  VPS environments by workload type & criticality
  MONITOR    →  Health checks + alerting on anomalies and failures
  DEPLOY     →  Structured process with rollback capability
  AGGREGATE  →  Centralized log collection across all services
  AUTOMATE   →  Maintenance: cleanup · backup · re-queue — automated

  Result     →  Infrastructure that operates autonomously.
               The backbone of labsandflows.com.br
```

<br/><br/>

---

<br/>

## Engineering Principles

<br/>

```
  Build for failure     →  Assume it will break. Plan the recovery first.
  Observability first   →  Logs and alerts are not optional — they are the system.
  Decouple aggressively →  Independence is a feature, not a luxury.
  Automate the routine  →  Manual processes are a liability at scale.
  Design to maintain    →  Future you is also a stakeholder.
```

<br/><br/>

---

<br/>

## Certifications

<br/>

<div align="center">

<a href="https://catalog-education.oracle.com/ords/certview/sharebadge?id=A1CF8D105535A6E101289D08018E64FECBF66EB486866C50E1A459A1F91005D5" target="_blank">
  <img src="https://img.shields.io/badge/Oracle_Cloud_%7C_OCI_2025_Foundations_Associate-1B2932?style=for-the-badge&logo=oracle&logoColor=F80000&labelColor=1B2932"/>
</a>

<br/><br/>

<a href="https://www.coursera.org/account/accomplishments/professional-cert/XTMKVVL2C36L" target="_blank">
  <img src="https://img.shields.io/badge/Google_%7C_UX_Design_Professional_Certificate-1B2932?style=for-the-badge&logo=google&logoColor=4285F4&labelColor=1B2932"/>
</a>

<br/><br/>

<a href="https://www.credly.com/badges/fa9f423f-2b48-42c0-8743-3afd9b363127" target="_blank">
  <img src="https://img.shields.io/badge/Credly_%7C_Google_UX_Design_Verified_Badge-1B2932?style=for-the-badge&logo=credly&logoColor=FF6B00&labelColor=1B2932"/>
</a>

<br/><br/>

<a href="https://www.coursera.org/account/accomplishments/verify/Q5WK33I6LYUI" target="_blank">
  <img src="https://img.shields.io/badge/Google_%7C_Foundations_of_Data-1B2932?style=for-the-badge&logo=google&logoColor=34A853&labelColor=1B2932"/>
</a>

</div>

<br/><br/>

<div align="center">

```yaml
Google UX Design — 7 Courses Completed:
  Foundations of UX Design:                    95.30%  · Feb 2024
  Empathize, Define & Ideate:                  91.87%  · Mar 2024
  Wireframes & Low-Fidelity Prototypes:        85.87%  · Mar 2024
  UX Research & Early Concept Testing:         93.12%  · Apr 2024
  High-Fidelity Designs in Figma:              90.18%  · Jun 2024
  Dynamic UI for Websites:                     89.30%  · Jun 2024
  Design for Social Good:                      94.95%  · Jun 2024

Skills: Figma · Design Thinking · Information Architecture
        Responsive Web Design · Prototyping · Usability Testing
```

</div>

<br/><br/>

---

<br/>

## GitHub Activity

<br/>

<div align="center">

<img width="47%" src="https://github-readme-stats.vercel.app/api?username=Cliffordson01&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&bg_color=1B2932&title_color=d3b58e&icon_color=d3b58e&text_color=8a9ba8&ring_color=d3b58e" />
&nbsp;
<img width="47%" src="https://streak-stats.demolab.com?user=Cliffordson01&hide_border=true&background=1B2932&stroke=263d4a&ring=d3b58e&fire=c4a070&currStreakNum=d3b58e&sideNums=8a9ba8&currStreakLabel=d3b58e&sideLabels=8a9ba8&dates=4a6070" />

<br/><br/>

<img width="55%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Cliffordson01&layout=compact&hide_border=true&langs_count=8&bg_color=1B2932&title_color=d3b58e&text_color=8a9ba8" />

<br/><br/>

<img width="96%" src="https://github-readme-activity-graph.vercel.app/graph?username=Cliffordson01&bg_color=1B2932&color=d3b58e&line=8a7050&point=d3b58e&area=true&hide_border=true&area_color=263d4a" />

</div>

<br/><br/>

---

<br/>

<div align="center">

## Let's Build Something That Scales

<sub>Open to international opportunities · Automation Engineering · Backend Systems · Technical Architecture<br/>Full-time &nbsp;·&nbsp; Contract &nbsp;·&nbsp; Consulting</sub>

<br/><br/>

<a href="https://www.linkedin.com/in/cliffordson-cetoute-264411348/" target="_blank">
  <img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-1B2932?style=for-the-badge&logo=linkedin&logoColor=d3b58e&labelColor=1B2932"/>
</a>
&nbsp;
<a href="mailto:cliffordsoncetoute004@gmail.com" target="_blank">
  <img src="https://img.shields.io/badge/Send%20an%20Email-1B2932?style=for-the-badge&logo=gmail&logoColor=d3b58e&labelColor=1B2932"/>
</a>
&nbsp;
<a href="https://labsandflows.com.br" target="_blank">
  <img src="https://img.shields.io/badge/Visit%20Labs%20%26%20Flows-1B2932?style=for-the-badge&logo=vercel&logoColor=d3b58e&labelColor=1B2932"/>
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Cliffordson01&label=Profile+Views&color=d3b58e&style=flat-square&labelColor=1B2932"/>

<br/><br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1a22,40:1b2932,100:0d1a22&height=120&section=footer&animation=fadeIn"/>

</div>
