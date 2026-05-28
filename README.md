# AI Business Plan Agents 🚀

> 4 specialized AI agents that collaborate to write investor-ready business plans in 30 seconds

**Built for Outskill × OpenAI AI Builders Hackathon 2026 | Phase 1 Submission**

[[Live Demo](https://rajegowdac024.github.io/Business-plans-mvp-agent-/)]

### **🎯 Problem**
First-time founders waste 40+ hours writing business plans. $5k consultants are too expensive. ChatGPT gives generic one-shots with no financials. 67% of pre-seed founders in India delay fundraising due to doc prep.

### **💡 Solution**
Multi-agent AI system where specialized agents work like a real founding team:

1. **Market Researcher Agent**: Calculates TAM/SAM/SOM + competitor analysis
2. **CFO Agent**: Builds 3-year financial model + unit economics 
3. **CMO Agent**: Creates GTM strategy + customer acquisition plan
4. **Critic Agent**: Red-teams the plan for gaps investors will catch

**User Journey**: Enter startup idea → Agents work in parallel → Review/edit → Export PDF

### **🛠️ Tech Stack**
| Layer | Tech | Why |
| --- | --- | --- |
| **LLM** | GPT-4o via OpenAI API | Best reasoning for financials |
| **Orchestration** | CrewAI | Multi-agent task delegation + memory |
| **Backend** | Python + FastAPI | Async endpoints = 30s generation |
| **Frontend** | Next.js + Tailwind | Ships fast, looks pro |
| **Data** | LangChain + Perplexity API | Real-time market data via RAG |

### **⚡ Live Demo**
[**MVP Link**]: (https://rajegowdac024.github.io/Business-plans-mvp-agent/)  

### **🚀 How to Use**
1. Open the [Live Demo](https://rajegowdac024.github.io/Business-plans-mvp-agent-/)
2. Enter your startup idea: "D2C millet snacks for urban millennials"
3. Click "Generate Plan" and watch agents work in real-time
4. Review Market, Financials, GTM, and Critic tabs
5. Click "Export PDF" to download investor-ready plan

### **🤖 How We Used AI to Build This**
- **Codex**: Wrote 80% of FastAPI boilerplate + async error handling for OpenAI API fails. Saved 4+ hours.
- **GPT-4o**: Prompt engineered all 4 agent personas. Pressure-tested CFO agent math to catch calculation errors.
- **CrewAI**: Handled agent orchestration so we could focus on business logic vs infrastructure.

Total build time: 6 hours from idea to deployed MVP.

### **🎯 Target Audience**
**Primary ICP**: Pre-seed founders & solopreneurs in Bangalore/Mumbai, aged 22-35. Technical founders with no finance background, raising first $50k-500k.

**Secondary**: B-school students, incubators like YC/Accel screening 1000s of plans.

**Beachhead Market**: 50k new startups/year in India. TAM: $250M for business planning tools.

### **🗺️ Phase 2 Roadmap**
1. **Investor Agent**: Scores your plan vs YC criteria + connects to AngelList
2. **Real Data API**: Auto-pull TAM from Statista/Tracxn instead of LLM estimates  
3. **Fine-tuning**: Train on 10k rejected YC applications to beat generic GPT
4. **Unit Economics**: Add CAC/LTV calculator based on user feedback

### **👥 Team**
Built by RAJE GOWDA.C for **Outskill × OpenAI AI Builders Hackathon 2026**

### **📬 Feedback**
Founders: Would you use this before your next investor call? What's missing? 
Open an Issue and DM me on [LinkedIn](https://www.linkedin.com/in/raje-gowda-c-a4b56929a).

---

**#AIBuildersHackathon #Outskill #OpenAI #Codex #BuildInPublic #AIagents #OutskillxOpenAI**
