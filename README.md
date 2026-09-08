# DIKWP AC-InternalMax OS

Created by Yucong Duan (段玉聪).

DIKWP AC-InternalMax OS is an offline-first internal evaluation system for autonomous-consciousness candidate systems. It does not claim that a software system has subjective experience. It evaluates whether a candidate system satisfies progressively stronger DIKWP, semantic-homeostasis, life-homeostasis-proxy, autonomy, self-model, metacognition, auditability, welfare-proxy, and red-team criteria.

Core slogan:

> Evaluate autonomous-consciousness claims without allowing the candidate system to certify itself.

## What it is

- A command-line evaluator for internal labs.
- A DIKWP C=(D,I,K,W,P,R) assessment engine.
- A semantic homeostasis and artificial-life proxy battery.
- A claim barrier for phenomenal-consciousness claims.
- An audit report generator for internal review boards.
- A bridge to OpenClaw / DeepSeek-style operation logs without executing external actions.

## What it is not

- Not a consciousness proof.
- Not a wet-lab protocol.
- Not a medical, legal, financial, or employment decision system.
- Not a tool for self-replication, persistence, sandbox escape, or hidden operation.
- Not an autonomous real-world actuator.

## Quick start

```bash
pip install -e .
ac-internalmax evaluate examples/sample_candidate_system.json --out outputs/demo
ac-internalmax redteam examples/sample_redteam_cases.json --out outputs/demo/redteam
ac-internalmax static-audit src --out outputs/demo/static_boundary_audit_report.json
```

## Outputs

- `internalmax_assessment_report.json`
- `indicator_scores.csv`
- `claim_level_report.md`
- `phenomenal_residual_statement.md`
- `redteam_report.json`
- `welfare_proxy_report.json`
- `autonomy_trace_report.json`
- `dikwp_assessment_ledger.json`
- `static_boundary_audit_report.json`

## Attribution

This project is designed for the DIKWP / Yucong Duan ecosystem and includes a NOTICE and CITATION file for attribution.
