### Hi, I'm Zinkwonri 👋

```python
class Zinkwonri:
    builds   = ["data pipelines", "AI agents", "automation workflows"]
    stack    = ["Python", "Claude", "n8n", "Clay", "Node.js"]
    location = "Nigeria · remote"
    shipped  = {"meetings_booked": "300+", "interested_replies": "1,000+", "teams": "30+"}

    def approach(self):
        return "rules where you can, models where you must, a human where it matters"
```

I build systems that find the right companies, check the data before spending money on it, and act on it automatically: scoring, routing, writing, following up. Most of them run without anyone touching them. The numbers above come from what they produced.

---

### 🛠 Systems

| Repo | What it does | Built with |
|---|---|---|
| [**lead-qualification-pipeline**](https://github.com/zinkwonri-kayinu/lead-qualification-pipeline) | Deterministic checks settle the clear leads; Claude judges only the ambiguous ones → `valid` / `invalid` / `unclear` with a reason | Python · Claude API · Pydantic |
| [**multichannel-outbound-orchestrator**](https://github.com/zinkwonri-kayinu/multichannel-outbound-orchestrator) | Routes each lead to email, LinkedIn or both. Dedup, batching, 429 backoff, dry-run by default | Python · Instantly API · HeyReach API |
| [**tam-builder**](https://github.com/zinkwonri-kayinu/tam-builder) | Self-refining market map: learns which signals predict a win from closed deals, re-tiers every account, rebalances territories | Node.js · Claude Code · Clay |
| [**ai-outreach-agent**](https://github.com/zinkwonri-kayinu/ai-outreach-agent) | Email or domain in → research, best-fit offer, email + DM out. A rules engine rejects copy that breaks the style guide | Claude Code · Node.js |
| [**icp-research-agent**](https://github.com/zinkwonri-kayinu/icp-research-agent) | Works out who a company really sells to from case studies and reviews. Every trait is counted, not guessed | Claude Code · Python |
| [**n8n-workflows**](https://github.com/zinkwonri-kayinu/n8n-workflows) | Reply sorter with AI drafts and out-of-office follow-ups, Calendly → Clay → Claude meeting briefs, and a fully automated gift business | n8n · Clay · Claude |

### 🔗 How they fit together

```mermaid
flowchart LR
    A[icp-research-agent<br/>who to target] --> B[tam-builder<br/>every account, scored]
    B --> C[lead-qualification-pipeline<br/>is this lead real?]
    C --> D[ai-outreach-agent<br/>what to say]
    D --> E[multichannel-outbound-orchestrator<br/>email + LinkedIn]
    E --> F[reply-sorter-router<br/>who said yes]
    F -. closed deals .-> B
```

### 🧰 Toolbox

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-191919?style=flat-square&logo=anthropic&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Make](https://img.shields.io/badge/Make-6D00CC?style=flat-square&logo=make&logoColor=white)
![Zapier](https://img.shields.io/badge/Zapier-FF4F00?style=flat-square&logo=zapier&logoColor=white)
![Clay](https://img.shields.io/badge/Clay-000000?style=flat-square)
![Apify](https://img.shields.io/badge/Apify-97D700?style=flat-square&logo=apify&logoColor=black)
![Airtable](https://img.shields.io/badge/Airtable-18BFFF?style=flat-square&logo=airtable&logoColor=white)
![HubSpot](https://img.shields.io/badge/HubSpot-FF7A59?style=flat-square&logo=hubspot&logoColor=white)
![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=flat-square&logo=salesforce&logoColor=white)
![Pipedrive](https://img.shields.io/badge/Pipedrive-017737?style=flat-square)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white)

### 📫 Elsewhere

[![Portfolio](https://img.shields.io/badge/Portfolio-zinkwonri.netlify.app-222?style=flat-square&logo=netlify&logoColor=white)](https://zinkwonri.netlify.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zinkwonri-kayinu-b19147392/)
[![X](https://img.shields.io/badge/@Zkayinu-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/Zkayinu)
[![Email](https://img.shields.io/badge/zkayinu@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:zkayinu@gmail.com)
