# stickermule-agents

Technical brief for the Sticker Mule AI Agent Engineer role — three evidence-based agentic workflow proposals grounded in direct research on SM's order API, Notify schema, and support infrastructure.

**Live:** https://eaterofsouls.github.io/Agents-Proposed-SM

---

## What this is

A research memo, not a portfolio piece. Built on:
- Direct observation of SM's order state machine (public REST API)
- GraphQL introspection of `/notify/graphql` and `/bridge/backend/graphql`
- Confirmed email infrastructure, Pub/Sub architecture, and Asana usage
- Adversarial falsification audit (what SM has NOT built and why)
- Five expert frameworks: Anthropic, Lilian Weng, Jason Liu, Simon Willison, Eugene Yan

## Three proposals

| Proposal | Pattern | Priority | Key dependency |
|---|---|---|---|
| **OrderGuardian** | Prompt Chaining Workflow | 1st — build first | GCloud Pub/Sub topic (Day 1 `gcloud` audit) |
| **NotifyMind** | Parallelization + Evaluator-Optimizer | 2nd | Asana API (confirmed) · Notify write mutations (Day 1 investigation) |
| **ReplyMind** | Routing Workflow | 3rd | Reply internal API (no public access — negotiate first) |

## By Daksh Chauhan

- Email: me@buildwithdaksh.com  
- Portfolio: [buildwithdaksh.com](https://buildwithdaksh.com)  
- GitHub: [Eaterofsouls](https://github.com/Eaterofsouls)
