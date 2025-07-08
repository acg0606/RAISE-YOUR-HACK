🚀 RAISE‑YOUR‑HACK – Project Submission
🔗 Event on lablab.ai: Raise Your Hack
https://lablab.ai/event/raise-your-hack

✨Check our project!✨
https://lablab.ai/event/raise-your-hack/sampa-nine-nine-vultr-track/airdrop-optimizer-multiagent-system-for-airdrop

📋 1. Project Title
Airdrop Optimizer: Multi‑Agent Autonomous System for Crypto Airdrop Maximization

✨ 2. Short Description
An autonomous multi-agent system that detects, evaluates, and executes crypto airdrop campaigns to maximize rewards through smart, automated trading simulations.

📖 3. Long Description
🎯 The Problem
Over US$ 1.2 billion in crypto airdrops go unclaimed annually.

Hundreds of campaigns launch monthly—each with complex volume and timing requirements.

Manual monitoring and execution are impractical and time-consuming.

💡 Our Solution
A coordinated multi-agent system that autonomously handles campaigns in four stages:

Airdrop Scout Agent

Simulates scraping airdrop listings (e.g., Binance).

Extracts campaign data: token, required volume, reward, duration, and URL.

Assigns a viability score (0–10).

Campaign Creator Agent

Filters campaigns with viability ≥ 5.0.

Assigns risk level (LOW, MEDIUM, HIGH) by score.

Launches Trading Agents configured for each campaign.

Prediction Agent

Performs technical analysis (moving averages, RSI), simulated sentiment analysis, and trend forecasting.

Aggregates insights to generate recommendations (BUY / SELL / HOLD).

Trading Agent

Executes simulated spot trades to meet campaign volume.

Manages balances with stop-loss and take-profit controls.

Tracks trade metrics: number of trades, success rate, profit/loss.

Reports status updates and final performance.

🔧 Architecture & Infrastructure
Asynchronous orchestration via Celery + Redis for scalable background execution.

CLI entry point via main.py.

RESTful interface using FastAPI (api/main.py) with endpoints to:

List campaigns

Create, start/stop agents

Monitor agent status

Swagger UI available for interactive testing 

🌐 Deployment on Vultr
The entire system is hosted on Vultr SSD VPS, which offers high-performance, reliable, and scalable cloud infrastructure using SSD-backed servers. We leverage Vultr’s features as follows:

Compute Resources: Fast Intel/AMD CPUs with SSD storage for efficient Celery task execution and low-latency FastAPI performance.

Scalability: Instantly provision new servers to handle increasing campaign volume and Celery queue throughput .

Global Reach: Multiple data centers enable deployments closer to users or exchanges, reducing latency.

Cost Efficiency: Hourly and monthly billing enables optimized infrastructure costs without long-term commitments.

Container/VM Deployment: Supports containerization (Docker, Kubernetes) or direct VM deployment. The REST API is exposed via load balancer for resilience and autoscaling.

📈 Scalability & Modularity
Celery enables parallel execution of agents across campaigns.

Each Trading Agent runs independently, identifiable via unique token-based IDs.

Simulated results include total trades executed, success rate, profit/loss, and campaign duration.

🧩 4. Technology & Category Tags
Technologies: Python, FastAPI, Celery, Redis, simulated Web scraping, simulated Spot trading
Categories: Crypto Trading, DeFi, Autonomous Agents, Multi‑agent Systems, Airdrop Optimization
Track: RAISE‑YOUR‑HACK (lablab.ai)

📸 5. Cover Image & Presentations
https://lablab.ai/event/raise-your-hack/sampa-nine-nine-vultr-track/airdrop-optimizer-multiagent-system-for-airdrop

💻 6. App Hosting & Code Repository
GitHub Repository: https://github.com/VieiraGabrielAlexandre/lablabai-hackathon-raise-your-hack-sampa-nine-nine

