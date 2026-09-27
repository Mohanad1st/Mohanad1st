## Mohannad Hesham Abouelrouse

I run [Life From Water](https://lifefromwater.net), an NGO in Egypt. Since 2011 we've delivered 3,105
water interventions across 259 villages in eight governorates, reaching 1,005,072 people.

I also teach AI, and I build the tools we run on. Most of that work is private. This page shows what I
can show.

One lesson shapes how I build. When AI first landed, we built a WhatsApp chatbot for the people running
our village plants. It was good. They refused to use it: they thought it meant no engineer would come
any more. So it isn't AI everywhere. It's AI in the right place, for the right person.

<p dir="rtl" lang="ar">أدير مؤسسة «ومن الماء حياة» في مصر. وأدرّس الذكاء الاصطناعي، وأبني الأدوات التي نعمل بها.</p>

### The record

- **Life From Water.** Founder and CEO. We started in 2011 and were registered in Egypt in 2014
  (no. 9575/2014). The figures above are the ones on [mohannadhesham.com](https://mohannadhesham.com).
- **Evaluation.** We were the implementing NGO for randomised evaluations run by academic teams,
  including a household water-treatment study by Brown and Stanford researchers with
  [J-PAL MENA](https://www.povertyactionlab.org/blog/11-16-23/20-20-life-waters-evidence-based-journey-egypt)
  ([trial registration](https://www.socialscienceregistry.org/trials/9944)).
- **Teaching.** 27,000+ learners across published AI courses and live cohorts. I co-developed and taught
  AI for Palestine: 18 live sessions, 100 participants and 15 graduation projects (self-reported).
  Training engagements are listed on [mohannadhesham.com](https://mohannadhesham.com).
- **Recognition.** [Ashoka Fellow](https://www.ashoka.org/en-us/fellow/mohannad-hesham). Attended the
  4th UNESCO Global Forum on the Ethics of AI, Riyadh, September 2026.

### AI risk and capacity building

- **Agent oversight in practice.** [mindkata-gate0](https://github.com/Mohanad1st/mindkata-gate0) is the
  prototype for a product-validation study with pre-set stop rules. Its check fails CI if a coding agent
  adds an unapproved runtime dependency, a banned directory, a third mission or a known model-API name:
  61 lines of Node. It checks specific patterns, and its known bypasses are written down in the
  repository.
- **Teaching in Arabic and English.** The courses and cohorts above. I've also built a free governance
  course that isn't public yet. Its interface is bilingual and its Arabic lessons are in progress. It
  covers the UNESCO Recommendation on the Ethics of AI with its readiness and ethical impact
  assessments, the main international frameworks and the governance of AI agents in organisations.

### Selected work

Code you can read:

- **[mindkata-gate0](https://github.com/Mohanad1st/mindkata-gate0)**: a study-scope lock that CI checks,
  with the decision records, threat model and data classification behind it.
  [Prototype](https://mindkata-gate0.vercel.app).
- **[motion-study](https://github.com/Mohanad1st/motion-study)**: video-based motion and time study for
  assembly lines. Apache-2.0. [Demo report](https://motion-study-demo.vercel.app).

Case studies of private systems (no code, demo data only):

- **[AI Governance Roadmap](https://github.com/Mohanad1st/ai-governance-roadmap-showcase)**: a free
  governance course, from first definitions to a working plan. *Built, not yet public.*
- **[Anchor Learning Hub](https://github.com/Mohanad1st/anchor-learning-hub-showcase)**: a bilingual,
  offline-ready platform for running training cohorts. *Live demo.*
- **[LFW HR System](https://github.com/Mohanad1st/lfw-hr-system-showcase)**: attendance, leave and
  approvals for our field staff, in Arabic and English. *In production use.*
- **[WaterEye](https://github.com/Mohanad1st/watereye-showcase)**: reading analogue water gauges from a
  photo. *Field pilot in one village; accuracy not yet measured.*
- **[Dr. Water OS](https://github.com/Mohanad1st/dr-water-os-showcase)**: daily operations for water
  treatment plants. *Pilot.*
- **[Life From Water donation platform](https://github.com/Mohanad1st/lifefromwater-website-showcase)**:
  donations and a public impact map. *Prototype; online donations not yet enabled.*

<details>
<summary>Other case studies</summary>

- [Impact Anchor site](https://github.com/Mohanad1st/impact-anchor-site-showcase): the bilingual site for my AI and evidence advisory work
- [Mohandes AI](https://github.com/Mohanad1st/mohandes-ai-showcase): applied AI for technical teams in MENA
- [GrantsAI](https://github.com/Mohanad1st/grantsai-showcase): grant matching and drafting for small NGOs, in development
- [Opportunity Studio](https://github.com/Mohanad1st/opportunity-studio-showcase): an evidence-first pipeline for funding applications

</details>

### How the safeguards map to the UNESCO Recommendation on the Ethics of AI (2021)

- **Human oversight and determination:** nothing is written or submitted without a person confirming it
  ([Ameen](https://github.com/Mohanad1st/ameen-showcase),
  [Opportunity Studio](https://github.com/Mohanad1st/opportunity-studio-showcase)).
- **Proportionality and do no harm:** [motion-study](https://github.com/Mohanad1st/motion-study)
  measures operations and refuses to rate workers.
- **Transparency and explainability:** each factual claim in a proposal is sourced or marked unconfirmed
  (Opportunity Studio).
- **Privacy and data protection:** donor and personal data can only be written by the server, under
  row-level security (the [donation platform](https://github.com/Mohanad1st/lifefromwater-website-showcase),
  built and not yet live).
- **Responsibility and accountability:** an audit trail of actions that company admins can review
  ([Dr. Water OS](https://github.com/Mohanad1st/dr-water-os-showcase)).

### Working with partners

I offer bilingual (Arabic and English) training on AI ethics and governance, and Life From Water as a
field case study of AI in a small NGO.
Contact me through [mohannadhesham.com](https://mohannadhesham.com) or
[LinkedIn](https://www.linkedin.com/in/mohannadhesham/).

### How I build

I build with coding agents. I own the problem definition, the architecture, the threat model and the
verification. If something I've written is worth discussing, I can explain the design decisions in it
without the agent in the room.
