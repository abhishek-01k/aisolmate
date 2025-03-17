# AI Investment Research and DeFi Strategy Agent

A powerful AI agent platform built with Sonic Agent Kit for investment research, DeFi strategy automation, and transaction building.

## Features

### AI Investment Research and Analysis

- Aggregates analysis from AI agents with token fundamentals, on-chain data, and social media trends
- Natural language interface for describing investment goals and generating optimized strategies
- Transaction compliance screening to detect sanctioned addresses before execution

### AI-Driven DeFi Strategy Automation

- Cross-chain execution framework for asset transactions and liquidity management
- Context-aware routing across L1/L2 chains based on real-time network conditions
- MEV-resistant execution with AI simulation to detect sandwich attacks
- Natural language command interface for strategy creation and execution

## Technology Stack

- **Frontend**: Next.js 13+, React, Tailwind CSS
- **AI Agent Framework**: Sonic Agent Kit
- **Blockchain Integration**: Solana Web3.js

## Getting Started

### Prerequisites

- Node.js 16+
- pnpm (recommended) or npm

### Installation

1. Clone the repository:
```bash
git clone https://github.com/kamalbuilds/ai-investment-agent.git

cd ai-investment-agent
```

2. Install dependencies:
```bash
pnpm install
```

3. Create a `.env.local` file in the root directory with the following variables:
```
OPENAI_API_KEY=your_openai_api_key
SOLANA_RPC_URL=your_solana_rpc_url
WALLET_PRIVATE_KEY=your_wallet_private_key
```

4. Start the development server:
```bash
pnpm dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Project Structure

- `/app` - Next.js app router pages
- `/components` - React components
  - `investment-agent.tsx` - AI Investment Research component
  - `defi-strategy.tsx` - DeFi Strategy Automation component
- `/lib` - Utility functions and business logic
  - `sonic-agent.ts` - Sonic Agent Kit integration

## Usage

### Investment Research

1. Navigate to the "Market Analysis" tab to get current market sentiment, trending topics, and recommendations
2. Use the "Investment Strategy" tab to generate personalized investment strategies based on your goals and risk tolerance
3. Research specific tokens in the "Token Research" tab to get fundamental and on-chain data

### DeFi Strategy Automation

1. Use natural language commands to create and execute DeFi strategies
2. View and manage your active strategies in the "Strategies" tab
3. Monitor transactions in the "Transactions" tab
4. Configure MEV protection settings in the "MEV Protection" tab

## Future Enhancements

- AI Civilization/Swarms: Implement a blockchain-based governance system for AI agent collaboration
- Advanced MEV protection with TEE (Trusted Execution Environment)
- Multi-agent coordination for complex DeFi strategies
- Integration with more chains and DeFi protocols

## License

MIT

## Acknowledgements

- [Sonic Agent Kit](https://github.com/sendaifun/sonic-agent-kit)
- [BCG X AgentKit](https://github.com/BCG-X-Official/agentkit)
- [AIXBT](https://twitter.com/aixbt_agent) for inspiration on AI investment research 