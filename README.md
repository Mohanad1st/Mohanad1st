## Mohannad Hesham Abouelrouse

Founder and CEO of [Life From Water](https://lifefromwater.net), an Egyptian NGO working on water
access and climate resilience. I teach and build practical AI governance for Arabic-speaking
organisations: safeguards written as checks a system has to pass, not only as policy. One worked
example is [mindkata-gate0](https://github.com/Mohanad1st/mindkata-gate0).

<p dir="rtl" lang="ar">مؤسس ورئيس تنفيذي لمؤسسة «ومن الماء حياة» في مصر. أدرّب وأبني أدوات عملية لحوكمة الذكاء الاصطناعي بالعربية والإنجليزية.</p>

### Evidence

- **Field work.** Life From Water started in 2011 and was registered in Egypt in 2014 (no. 9575/2014).
  It has delivered 3,105 water interventions, 79 of them treatment stations, across 259 villages in
  eight governorates, reaching 1,005,072 people (the figures used on [mohannadhesham.com](https://mohannadhesham.com)).
- **Evaluation.** Life From Water has been the implementing NGO for randomised evaluations run by
  academic teams, including a household water-treatment study with
  [J-PAL MENA](https://www.povertyactionlab.org/blog/11-16-23/20-20-life-waters-evidence-based-journey-egypt)
  ([trial registration](https://www.socialscienceregistry.org/trials/9944)).
- **Teaching.** 27,000+ learners across published AI courses and live cohorts. I co-developed and
  taught AI for Palestine: 18 live sessions, 100 participants and 15 graduation projects
  (self-reported). Training engagements are listed on [mohannadhesham.com](https://mohannadhesham.com).
- **Recognition.** [Ashoka Fellow](https://www.ashoka.org/en-us/fellow/mohannad-hesham). Attended the 4th
  UNESCO Global Forum on the Ethics of AI, Riyadh, September 2026.

### AI risk and capacity building

- **Agent oversight in practice.** mindkata-gate0, the prototype for a product-validation study with pre-set stop rules, fails the build if a coding agent adds an unapproved
  dependency, directory, mission or model-API import: 61 lines of Node that CI runs. It checks
  specific patterns; its known bypasses are written down in the repository.
- **Teaching in Arabic and English.** The courses and cohorts above. A free governance course is built
  but not yet public; its interface is bilingual and its Arabic lessons are in progress. It covers the
  UNESCO Recommendation on the Ethics of AI with its readiness and ethical impact assessments, the main
  international frameworks and the governance of AI agents in organisations. It does not cover
  catastrophic or frontier-model risk.

### Selected work

Code you can read:

- **[mindkata-gate0](https://github.com/Mohanad1st/mindkata-gate0)**: a study-scope lock a build can
  check, with the decision records, threat model and data classification behind it.
  [Prototype](https://mindkata-gate0.vercel.app).
- **[motion-study](https://github.com/Mohanad1st/motion-study)**: video-based motion and time study
  for assembly lines. Apache-2.0, where most comparable tools are commercial.
  [Demo report](https://motion-study-demo.vercel.app).

Case studies of private systems (no code, demo data only):

- **[AI Governance Roadmap](https://github.com/Mohanad1st/ai-governance-roadmap-showcase)**: a free
  governance course from first definitions to a working plan. *Built, not yet public.*
- **[Anchor Learning Hub](https://github.com/Mohanad1st/anchor-learning-hub-showcase)**: a bilingual,
  offline-ready platform for running training cohorts. *Live demo.*
- **[LFW HR System](https://github.com/Mohanad1st/lfw-hr-system-showcase)**: attendance, leave and
  approvals for a field NGO, in Arabic and English. *In production use.*
- **[WaterEye](https://github.com/Mohanad1st/watereye-showcase)**: reading analogue water gauges from a
  phone photo. *Field pilot in one village; accuracy not yet measured.*
- **[Dr. Water OS](https://github.com/Mohanad1st/dr-water-os-showcase)**: daily operations for water
  treatment plants. *Paid pilot.*
- **[Life From Water donation platform](https://github.com/Mohanad1st/lifefromwater-website-showcase)**:
  donations and a public impact map. *Prototype; donations switched on at launch.*

<details>
<summary>Other case studies</summary>

- [Impact Anchor site](https://github.com/Mohanad1st/impact-anchor-site-showcase): my consulting practice's bilingual site
- [Mohandes AI](https://github.com/Mohanad1st/mohandes-ai-showcase): applied AI for technical teams in MENA
- [GrantsAI](https://github.com/Mohanad1st/grantsai-showcase): grant discovery and drafting for small NGOs, in development
- [Opportunity Studio](https://github.com/Mohanad1st/opportunity-studio-showcase): an evidence-first pipeline for funding applications

</details>

### How the safeguards map to the UNESCO Recommendation on the Ethics of AI (2021)

- **Human oversight and determination:** nothing is written or submitted without a person confirming
  it ([Ameen](https://github.com/Mohanad1st/ameen-showcase),
  [Opportunity Studio](https://github.com/Mohanad1st/opportunity-studio-showcase)).
- **Proportionality and do no harm:** [motion-study](https://github.com/Mohanad1st/motion-study)
  measures operations and refuses to rate workers.
- **Transparency and explainability:** each factual claim in a proposal is sourced or marked unconfirmed (Opportunity Studio).
- **Privacy and data protection:** donor and personal data can only be written by the server, under
  row-level security (the [donation platform](https://github.com/Mohanad1st/lifefromwater-website-showcase)).
- **Responsibility and accountability:** an audit trail of actions that company admins can review
  ([Dr. Water OS](https://github.com/Mohanad1st/dr-water-os-showcase)).

### Working with partners

I offer bilingual (Arabic and English) training on AI ethics and governance, help turning a
governance framework into checks a team can run, and Life From Water as a field case study of AI in
a small NGO. Contact me through [mohannadhesham.com](https://mohannadhesham.com) or
[LinkedIn](https://www.linkedin.com/in/mohannadhesham/).

### How I build

Most of what I build lives in private repositories: internal systems for NGOs and clients. That work
isn't public and shouldn't be; the case studies above describe it without the code. I build with coding
agents, and I own the problem definition, the architecture, the threat model and the verification.
If something I've written is worth discussing, I can explain every design decision in it without the
agent in the room.
