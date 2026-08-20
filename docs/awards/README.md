# Awards And Programs

External programs and competitions where UMMAYA was presented. This page records outcomes only; it does not imply endorsement by any organizer, agency, or sponsor.

## 제11회 부울경 AI 융합 해커톤 (2026)

| Item | Detail |
|---|---|
| Event | 제11회 부울경 AI 융합 해커톤 (11th Busan–Ulsan–Gyeongnam AI Convergence Hackathon) |
| Host | 부산광역시 · 부산정보산업진흥원 |
| Organizers | 부산대학교 · 동아대학교 · 국립부경대학교 · 경남대학교 · 국립창원대학교 · 울산대학교 |
| Dates | 2026-07-09 (Thu) 13:00 – 2026-07-10 (Fri) 17:00 |
| Result | 본선 진출 (advanced to the final round) |
| Entry | UMMAYA — 흩어진 국가행정을 하나의 대화로 잇는 국민-측 AX 하네스 |

### Artifacts

- Presentation deck: [`presentation/UMMAYA_latest_deck.pptx`](../../presentation/UMMAYA_latest_deck.pptx)
- Participation certificate: [`2026-buulgyeong-ai-convergence-hackathon-certificate.pdf`](2026-buulgyeong-ai-convergence-hackathon-certificate.pdf)

### What Was Presented

The deck argues the project in five blocks — problem, approach, implementation, proof, and impact.

| Block | Content |
|---|---|
| Problem | Korean national administration is siloed by ministry and agency, so identity checks, issuance, applications, and payments sit behind different entry points, credentials, and UX. The cost of that fragmentation lands on citizens. |
| Approach | A single conversational harness on the citizen side, powered by `K-EXAONE-236B-A23B` through FriendliAI, chosen for Korean tokenizer efficiency, MoE cost profile, and sovereign self-hosting potential. No change is required inside agency systems. |
| Implementation | Agentic execution loop (intent decomposition, hybrid BM25 + dense tool retrieval, gated tool calls, observe-and-repeat), layered architecture (LLM/context, tool registry, permission gate, OTEL observability, session, TUI), and five primitives `find` · `locate` · `check` · `send` · `document`. |
| Proof | Live 74-second terminal demo covering the primitives, Layer 1 to Layer 2 permission escalation, and PIPA §22-2 consent citation, plus an explicit Live / Mock / Handoff coverage table and stated limitations. |
| Impact | Quantitative expectations are framed as external-evidence analogy rather than measured results, including the METR counter-example; qualitative value centers on digital inclusion, accessibility, trust, sovereignty, and a single life-event flow. |

Capability honesty carries over from the main [README](../../README.md): identity and submission paths remain Mock or Handoff until an official callable channel, valid credential, and documented contract exist.
