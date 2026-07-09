# Job Search Strategy & Resume Report — Ansh Singh

*Prepared July 2026. Based on your resume (Jul 2026) and current market research.*

---

## 1. What your profile actually is (and where you're a top candidate)

You look like three different candidates on paper: a **simulation/CAE engineer**, a **scientific-ML engineer**, and an **AI product manager**. That breadth reads as "unfocused" to a generalist recruiter, but it is a genuine superpower for one specific, fast-growing niche.

**Your strongest wedge: ML × physics simulation.** Very few people combine deep FEA/CFD/thermal domain knowledge (RWTH M.Sc., journal-bearing thermo-mechanics, pyrolysis reactor, geothermal cooling) *with* production-grade ML for simulation (GNN surrogate model in PyTorch/DGL that cut FEM runtime 50%, synthetic-data pipelines, NumPy/Pandas). That intersection is exactly what an entire category of well-funded companies is built around — and where you should aim first, because there you are not competing against 500 pure-CAE applicants.

Honest read on each track:

- **ML/Simulation hybrid (surrogate modeling, GNN/PINN, ML-for-CAE)** — *Your best fit.* Rare skill combination, high demand, fewer qualified applicants. Target this hardest.
- **Simulation / CAE Engineer** — *Strong fit,* especially thermal/CFD and R&D-flavored roles. Weaker for automotive OEM crash/NVH roles (see keyword gaps — you lack LS-DYNA, HyperMesh, Nastran).
- **Mechanical / Systems Design Engineer** — *Solid fit* for R&D, hardware startups, cleantech, and prototype-heavy roles (pyrolysis reactor + DIN EN 13445/13480 experience is a real differentiator here).

A note on how to *frame* this: don't send the same resume to all three. Lead with the ML-simulation intersection for the hybrid roles, and produce a "simulation-forward" variant that de-emphasizes the AI PM role for pure CAE roles.

---

## 2. Job listings where you'd be a top candidate

Individual job-posting URLs expire within weeks, so this section pairs **named target employers** (where your profile is unusually strong) with **live search links** that stay current. Click the search links to see today's openings.

### Tier 1 — Physics-AI / ML-for-simulation companies (your sharpest edge)

These companies exist specifically to merge simulation with ML. Your GNN-surrogate + FEA background is close to their ideal hire, and they value the domain knowledge that pure ML candidates lack.

| Company | Why you fit | Where to look |
|---|---|---|
| **PhysicsX** (London/NY, hybrid, visa + relocation) | Roles for "simulation engineers who create, train, deploy physics-informed models." Large Physics Models = your GNN/surrogate work at scale. Actively hiring; relocation + UK visa sponsorship. | [PhysicsX Greenhouse board](https://job-boards.eu.greenhouse.io/physicsx) |
| **Monolith AI** (London/remote) | Learns from test + simulation data to predict product behavior; hiring ML/software engineers to solve scientific problems. | [Monolith on LinkedIn](https://www.linkedin.com/company/monolith-ai) → Jobs |
| **Neural Concept** (Lausanne/EU) | 3D deep learning on CAD/CAE data to shorten simulation-driven design loops. Your GNN-on-FEM experience maps directly. | Neural Concept careers page + LinkedIn Jobs |
| **Ansys (SimAI / ML)**, **Altair**, **Siemens Digital Industries**, **COMSOL** | The incumbents are building ML-surrogate features into their solvers — they want engineers who know both the solver and the ML. | [LinkedIn: "machine learning simulation" Germany](https://www.linkedin.com/jobs/search?keywords=machine%20learning%20simulation&location=Germany) |
| **Bosch Research**, **Robert Bosch** | Multiple ML-surrogate / multiphysics roles (incl. a PhD-level ML surrogate modeling posting via Bosch). Strong R&D fit. | [Simplify: Bosch ML surrogate modeling](https://simplify.jobs/p/a10ed5fb-6345-4e06-b78a-a90fb6af44bb) |

### Tier 2 — Simulation / CAE Engineer (Germany + EU + remote)

Germany is projected to have 300k+ vacant engineering roles by 2026; CAE is among the most in-demand. Best-fit subsegments for you: **thermal management, CFD, energy/cleantech, aerospace R&D** (avoid pure crash/NVH unless you add those tools).

- [LinkedIn — 4,000+ Simulation Engineer jobs in Germany](https://www.linkedin.com/jobs/search?keywords=Simulation+Engineer&geoId=101282230)
- [Glassdoor — Simulation Engineer, Berlin](https://www.glassdoor.com/Job/berlin-simulation-engineer-jobs-SRCH_IL.0,6_IC2622109_KO7,26.htm)
- [Glassdoor — CAE Engineer, Germany (567 roles)](https://www.glassdoor.com/Job/germany-cae-engineer-jobs-SRCH_IL.0,7_IN96_KO8,20.htm)
- [Glassdoor — FEA Simulation Engineer, Germany](https://www.glassdoor.com/Job/germany-fea-simulation-engineer-jobs-SRCH_IL.0,7_IN96_KO8,31.htm)
- [DEVjobs.de — Simulation Engineer (English-speaking, Germany)](https://en.devjobs.de/jobs/simulations-engineer)
- **Named fits:** Siemens Energy, Tesla (Berlin Gigafactory — thermal/battery), C1 Green Chemicals, EDAG, Bertrandt, plus energy/cleantech scale-ups where your reactor + geothermal work stands out.

### Tier 3 — Thermal / energy systems & data-center cooling (niche you literally have on your resume)

Your geothermal data-center cooling project (40% energy reduction) is directly relevant to today's AI-data-center cooling boom.

- [Jobgether — remote Data Center Cooling roles](https://jobgether.com/remote-jobs/data-center-cooling)
- [Jobgether — remote Thermal Engineering roles](https://jobgether.com/remote-jobs/thermal-engineering)
- [Glassdoor — Thermal Engineer, Germany](https://www.glassdoor.com/Job/germany-thermal-engineer-jobs-SRCH_IL.0,7_IN96_KO8,24.htm)
- **Named fits:** hyperscaler infra teams, liquid-cooling startups, and HVAC/thermal groups at data-center operators.

### Tier 4 — Remote-first ML / research (if you want to lean AI)

- [Arc.dev — remote PyTorch jobs](https://arc.dev/remote-jobs/pytorch)
- [Glassdoor — Machine Learning jobs, Germany (2,500+)](https://www.glassdoor.com/Job/germany-machine-learning-jobs-SRCH_IL.0,7_IN96_KO8,24.htm)
- Research-lab / postdoc-adjacent surrogate-modeling roles (e.g., University of Luxembourg ML + surrogate modeling) if you'd consider applied-research tracks.

> **Reality check on seniority:** For "Senior" simulation/ML titles, your continuous full-time engineering tenure is on the shorter side (a lot of your timeline is thesis/research + startup + ~1 yr PM). Apply to **mid-level and "Engineer II / Simulation Engineer"** roles as your center of gravity, and reach for Senior only where the ML-simulation combo is explicitly the differentiator.

---

## 3. ATS keywords you're likely missing

Your skills section is strong but has real gaps against how these roles are written. In 2026, 75%+ of large employers run an ATS keyword parse *plus* an AI/LLM ranking layer on top — missing the exact terms in a job description can drop you before a human ever looks. Add the terms below **only where they're true**, and always spell out the acronym once, e.g. "Reduced-Order Models (ROM)."

**Simulation / CAE (highest-impact gaps):**
- Meshing / mesh generation, mesh independence study
- Nonlinear analysis, contact mechanics, modal analysis, harmonic analysis
- Fatigue analysis, durability, NVH (noise-vibration-harshness)
- Verification & Validation (V&V), correlation to test data
- GD&T (Geometric Dimensioning & Tolerancing), tolerance stack-up
- **Tools recruiters filter on that you don't list:** LS-DYNA, Altair HyperMesh/HyperWorks, MSC Nastran, ANSA, Star-CCM+, OpenFOAM, ANSYS Fluent, ANSYS Mechanical (name the specific module, not just "ANSYS")

**ML / Simulation hybrid (add these — they're your differentiators and often literal JD requirements):**
- Physics-Informed Neural Networks (PINNs)
- Neural Operators — Fourier Neural Operator (FNO), DeepONet
- Reduced-Order Models (ROM), model order reduction
- Uncertainty Quantification (UQ)
- Design of Experiments (DOE), Bayesian optimization
- JAX, scikit-learn (alongside your PyTorch/DGL/TensorFlow)
- HPC / cluster computing, GPU acceleration

**Engineering-ML infrastructure (frequently required, currently absent):**
- MLOps, model deployment, model serving
- Git / version control, CI/CD
- Docker, Kubernetes
- Cloud: AWS / Azure / GCP
- Data pipelines / ETL (you do this — name it explicitly)

**Soft / process keywords worth surfacing:** cross-functional collaboration, stakeholder management, requirements engineering, root cause analysis (RCA — you have it), design reviews, technical documentation.

### Also fix these resume mechanics (they hurt ATS + human readers)

1. **No portfolio/GitHub link.** In 2026 your GitHub/portfolio carries close to interview-level weight for ML + simulation roles. Add a GitHub with the GNN surrogate work (even a cleaned-up write-up). This is the single highest-ROI change.
2. **Date overlap looks like an error.** Kyaani is listed "Sept 2025 – Present" while Wempyre is "April 2026 – July 2026." Overlapping current roles trip both parsers and recruiters — clarify (concurrent? contract? part-time?) or restructure.
3. **"English (Native)" + only intermediate German.** Fine for remote/EU and English-speaking German employers; a blocker for many on-site German roles that want B2/C1. Prioritize accordingly, and keep pushing German for the Berlin on-site market.
4. **Quantify consistently and keep the strong metrics up top** (40%, 25%, 50% are excellent — lead with them).
5. **Keep it single-column, standard section headings** ("Experience," "Education," "Skills") — you already do this well; don't add columns/tables/graphics that break parsers.

---

## 4. How modern engineering hiring actually works (2026)

The process has changed a lot in the last two years, mostly because AI now sits on *both* sides — screening candidates and being used by candidates. Here's the real pipeline for an engineering role at a mid-to-large employer, and where people get filtered out.

**Stage 0 — Sourcing.** Roughly half of hires never come through the "apply" button. Recruiters source directly on LinkedIn, and **referrals** are the highest-conversion channel by a wide margin. Practical implication: a referral into PhysicsX/Monolith/Bosch is worth more than 50 cold applications. Optimize your LinkedIn for the exact keywords in Section 3, because that's how sourcers find you.

**Stage 1 — ATS parse + knockout.** Your PDF is converted to plain text and structured fields. Then automatic "knockout" questions (work authorization, location, minimum years) can auto-reject you. Then a keyword/semantic match against the job description. AI tools now screen ~250 resumes in under 30 minutes, and a poorly matched resume can be filtered in under a second. This is why Section 3 matters — not to "game" it, but to make sure true skills aren't invisible.

**Stage 2 — AI/LLM ranking (new since ~2024).** On top of the classic keyword parse, an LLM layer summarizes and ranks the survivors by "fit score" against the JD, routing borderline cases to humans. The takeaway: mirror the language of each specific posting (their words for the same skill), and keep the resume clean/structured so the summarizer represents you accurately.

**Stage 3 — Recruiter screen.** A 20–30 min call on motivation, comp expectations, logistics (visa, notice period, remote vs. hybrid), and a sanity check on your top claims. Have crisp answers on your date overlap and your "why this track."

**Stage 4 — Technical / problem-solving.** For simulation + ML roles this is often *not* LeetCode. Expect: a take-home or pair session on a modeling/simulation problem, a portfolio/past-project deep dive ("walk me through the GNN surrogate — architecture, data, validation, error"), and domain Q&A (FEA theory, meshing, thermal, or ML fundamentals). PhysicsX's own process, for example, is intro call → problem-solving interview → deeper technical → final with senior team → offer. Companies are deliberately adding **live/in-person verification** because AI has made async take-homes less trustworthy — 71% of engineering leaders say AI makes it harder to assess real skills, so expect at least one live technical conversation.

**Stage 5 — System/behavioral + panel.** Structured behavioral interviews (STAR format), plus for senior roles a design/architecture discussion. Prepare 4–6 STAR stories mapped to your best projects (the 25% bearing-reliability framework, the 50% FEM speedup, the 40% cooling reduction).

**Stage 6 — Offer + reference/background.** Negotiable; German roles often have longer notice periods and more formal contracts than US remote roles.

**What this means for you, concretely:**
- **Referrals first.** For each Tier-1 company, find one employee on LinkedIn and ask for a referral rather than applying cold.
- **Tailor per posting.** Keep a master resume; produce a 10-minute tailored version per application mirroring that JD's keywords.
- **Build the portfolio now.** It's the highest-leverage asset for your specific niche and it doubles as Stage-4 material.
- **Rehearse the project deep-dives.** Your differentiator is depth on the ML-simulation projects; be able to defend architecture, data, and validation choices cold.

---

## Sources

- [Glassdoor — Simulation Engineer jobs, Germany](https://www.glassdoor.com/Job/germany-simulation-engineer-jobs-SRCH_IL.0,7_IN96_KO8,27.htm)
- [Glassdoor — CAE Engineer jobs, Germany](https://www.glassdoor.com/Job/germany-cae-engineer-jobs-SRCH_IL.0,7_IN96_KO8,20.htm)
- [Glassdoor — Simulation Engineer, Berlin](https://www.glassdoor.com/Job/berlin-simulation-engineer-jobs-SRCH_IL.0,6_IC2622109_KO7,26.htm)
- [CAE Engineer Jobs in Germany 2026 — TerraTern](https://terratern.com/blog/cae-engineer-jobs-in-germany/)
- [PhysicsX — Careers](https://www.physicsx.ai/careers) and [PhysicsX open roles (Greenhouse)](https://job-boards.eu.greenhouse.io/physicsx)
- [Monolith — LinkedIn](https://www.linkedin.com/company/monolith-ai)
- [Simplify — Bosch ML surrogate modeling role](https://simplify.jobs/p/a10ed5fb-6345-4e06-b78a-a90fb6af44bb)
- [University of Luxembourg — ML & Surrogate Modelling postdoc](https://www.uni.lu/en/jobs/postdoctoral-researcher-in-machine-learning-and-surrogate-modelling/)
- [Jobgether — remote data center cooling](https://jobgether.com/remote-jobs/data-center-cooling) and [remote thermal engineering](https://jobgether.com/remote-jobs/thermal-engineering)
- [Arc.dev — remote PyTorch jobs](https://arc.dev/remote-jobs/pytorch)
- [Mechanical Engineer Resume Keywords 2026 — ResumeAdapter](https://www.resumeadapter.com/blog/mechanical-engineer-resume-keywords)
- [Mechanical Engineering ATS Keywords — VisualCV](https://www.visualcv.com/blog/mechanical-engineering-ats-keywords-for-resume/)
- [12 Interview Trends in 2026 — Venture-Lab](https://venture-lab.org/2026/interview-trends-2026/)
- [How AI Screens Your Resume in 2026 — HappyPeopleAI](https://happypeopleai.com/blog/how-ai-screens-your-resume-in-2026-and-how-to-beat-ats-filters)
- [Resume Screening in 2026 — MiHCM](https://mihcm.com/resources/blog/resume-screening-in-2026-a-guide-to-ai-powered-screening-ats-integration-bias-governance/)
