🚀 RAISE‑YOUR‑HACK – Project Submission</p>
🔗 Event on lablab.ai: Raise Your Hack</p>
https://lablab.ai/event/raise-your-hack</p>
</p>
</p>✨Check our project!✨</p>
https://lablab.ai/event/raise-your-hack/sampa-nine-nine-vultr-track/airdrop-optimizer-multiagent-system-for-airdrop
</p>
</p>📋 1. Project Title</p>
Airdrop Optimizer: Multi‑Agent Autonomous System for Crypto Airdrop Maximization
</p>
✨ 2. Short Description</p>
An autonomous multi-agent system that detects, evaluates, and executes crypto airdrop campaigns to maximize rewards through smart, automated trading simulations.
</p>
📖 3. Long Description</p>
</p>🎯 The Problem
Over US$ 1.2 billion in crypto airdrops go unclaimed annually.
</p>
Hundreds of campaigns launch monthly—each with complex volume and timing requirements.
</p>
Manual monitoring and execution are impractical and time-consuming.
</p>
💡 Our Solution</p>
A coordinated multi-agent system that autonomously handles campaigns in four stages:
</p>
Airdrop Scout Agent
</p>
Simulates scraping airdrop listings (e.g., Binance).
</p>
Extracts campaign data: token, required volume, reward, duration, and URL.
</p>
Assigns a viability score (0–10).
</p>
Campaign Creator Agent
</p>
Filters campaigns with viability ≥ 5.0.
</p>
Assigns risk level (LOW, MEDIUM, HIGH) by score.
</p>
Launches Trading Agents configured for each campaign.
</p>
Prediction Agent
</p>
Performs technical analysis (moving averages, RSI), simulated sentiment analysis, and trend forecasting.
</p>
Aggregates insights to generate recommendations (BUY / SELL / HOLD).
</p>
Trading Agent
</p>
Executes simulated spot trades to meet campaign volume.
</p>
Manages balances with stop-loss and take-profit controls.
</p>
Tracks trade metrics: number of trades, success rate, profit/loss.
</p>
Reports status updates and final performance.
</p>
🔧 Architecture & Infrastructure
</p>Asynchronous orchestration via Celery + Redis for scalable background execution.

</p>CLI entry point via main.py.

</p>RESTful interface using FastAPI (api/main.py) with endpoints to:

</p>List campaigns

</p>Create, start/stop agents

</p>Monitor agent status

</p>Swagger UI available for interactive testing 

</p>🌐 Deployment on Vultr
</p>The entire system is hosted on Vultr SSD VPS, which offers high-performance, reliable, and scalable cloud infrastructure using SSD-backed servers. We leverage Vultr’s features as follows:

</p>Compute Resources: Fast Intel/AMD CPUs with SSD storage for efficient Celery task execution and low-latency FastAPI performance.

</p>Scalability: Instantly provision new servers to handle increasing campaign volume and Celery queue throughput .

</p>Global Reach: Multiple data centers enable deployments closer to users or exchanges, reducing latency.

</p>Cost Efficiency: Hourly and monthly billing enables optimized infrastructure costs without long-term commitments.

</p>Container/VM Deployment: Supports containerization (Docker, Kubernetes) or direct VM deployment. The REST API is exposed via load balancer for resilience and autoscaling.

</p>📈 Scalability & Modularity
</p>Celery enables parallel execution of agents across campaigns.

</p>Each Trading Agent runs independently, identifiable via unique token-based IDs.

</p>Simulated results include total trades executed, success rate, profit/loss, and campaign duration.

</p>🧩 4. Technology & Category Tags
</p>Technologies: Python, FastAPI, Celery, Redis, simulated Web scraping, simulated Spot trading
</p>Categories: Crypto Trading, DeFi, Autonomous Agents, Multi‑agent Systems, Airdrop Optimization
</p>Track: RAISE‑YOUR‑HACK (lablab.ai)

</p>📸 5. Cover Image & Presentations
</p>https://lablab.ai/event/raise-your-hack/sampa-nine-nine-vultr-track/airdrop-optimizer-multiagent-system-for-airdrop

</p>💻 6. App Hosting & Code Repository
</p>GitHub Repository: https://github.com/VieiraGabrielAlexandre/lablabai-hackathon-raise-your-hack-sampa-nine-nine

