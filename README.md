# WhatIfCity - Decision-Consequence Agent

An intelligent decision-consequence simulation agent that models urban, policy, or scenario decisions and projects their downstream impacts and cascading consequences.

---

## 📁 Repository Structure

```text
WhatIfCity/
├── backend/            # Decision-consequence engine, APIs, and agent logic
│   └── README.md
├── frontend/           # Interactive dashboard and scenario simulation interface
│   └── README.md
├── data/               # Simulation datasets, scenario definitions, and state schemas
│   └── README.md
├── docs/               # System architecture, documentation, and user guides
│   ├── screenshots/    # UI mockups, screenshots, and visual assets
│   │   └── README.md
│   └── README.md
├── .env.example        # Environment variable template
├── .gitignore          # Git ignore specifications
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites
- Python 3.10+ (or Node.js 18+ for frontend)
- Git

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/Universal-codeweb/WhatIfCity.git
   cd WhatIfCity
   ```

2. Configure environment variables:
   ```bash
   cp .env.example .env
   ```

3. Install backend dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## 📌 Modules
- **[backend](backend/)**: Core agent reasoning loop, decision impact models, and REST API.
- **[frontend](frontend/)**: Visual simulation dashboard and consequence timeline.
- **[data](data/)**: Raw scenarios, baseline indicators, and simulation state.
- **[docs](docs/)**: Comprehensive documentation and [screenshots](docs/screenshots/).
