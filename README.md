# Should I Use AI? — Decision Tools

Two interactive assessment tools to help you decide whether AI is the right fit for your specific task or use-case.

## Files

- **`Should_I_use_AI_Offline.html`** — General-purpose version for any task (fully offline, no internet required)
- **`Should_I_use_AI_Manufacturing_Offline.html`** — Purpose-built for manufacturing, production, and maintenance tasks (fully offline, no internet required)

## How to Use

1. **Open either HTML file directly in a web browser** — no installation, server, or internet connection required.
2. **Answer 7 quick questions** about your task or use-case (~90 seconds).
3. **Get a verdict** on whether AI fits, which type to use, and what guardrails to put in place.

## Versions

### General Version (`Should_I_use_AI_Offline.html`)

Guides you through:
- What the task mainly involves (LLM, ML, perception, classification, RPA, agent, or rules-based)
- Whether you can fully specify the logic
- Frequency and data availability
- Error cost and auditability requirements
- Human oversight model

**Suited for:** Software projects, content work, automation, business processes, data analysis.

### Manufacturing Version (`Should_I_use_AI_Manufacturing_Offline.html`)

Tailored for the shop floor, maintenance, and production planning:
- Seven manufacturing use-cases: defect detection, predictive maintenance, process optimisation, document AI, MES/ERP automation, scheduling, operator assist
- Sensor & historian data assessment
- Real-time latency vs. batch vs. async requirements
- **Safety classification** (IEC 61508 / ISO 13849 framing)
- **Traceability** for quality systems (ISO / FDA / CE)
- **OT/IT integration** readiness (OPC-UA, air-gapped, legacy PLC environments)

**Suited for:** Production lines, condition monitoring, quality inspection, predictive maintenance, process control, operator support systems.

---

## Example Verdicts

| Verdict | Meaning | What to do |
|---------|---------|-----------|
| **GOOD FIT** | AI is the right tool here | Proceed with a pilot or proof-of-concept |
| **CONDITIONAL** | AI can work — with guardrails | Address flagged risks (data, safety, integration) in parallel |
| **NOT A FIT** | A simpler tool beats AI | Use standard automation, RPA, PLC logic, or rule-based software instead |

---

## Tips

- **Think of one concrete task** — the more specific, the more useful the recommendation.
- **Collect data first** — AI models need training material. If you have little or no data, the tool will flag this and suggest data collection first.
- **Start small** — run a pilot on one line or one workflow before scaling.
- **Keep humans in the loop** — especially for safety-critical or high-stakes decisions.
- **Audit trails matter** — if your industry requires traceability (ISO, FDA, CE), log AI inputs, outputs, and model versions.

---

## GitHub Pages

Once published, the tools are accessible directly in the browser — no download needed:

- **General:** https://dannielarsen.github.io/Should-I-use-AI-manufacturing-edition-/Should_I_use_AI_Offline.html
- **Manufacturing:** https://dannielarsen.github.io/Should-I-use-AI-manufacturing-edition-/Should_I_use_AI_Manufacturing_Offline.html

Enable via: GitHub repo → **Settings → Pages → Source: main branch, root `/`**

---

## Made by

**Dannie Larsen**

---

## License & Usage

These tools are provided as-is for decision support. They offer guidance but do not replace professional engineering judgment, functional safety assessment, or regulatory compliance review.

For manufacturing applications with safety implications, consult qualified functional safety engineers (IEC 61508 / ISO 13849 certified).
