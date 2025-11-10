# Kitdot Payment Features Enhancement

- **Team Name:** WEB3DEV Community
- **Payment Details:**
  - **DOT**: N/A
  - **Payment**: 15wyV9jTKuNqU112iifFjxGQwFE1CeyFyxWJXH8qBCD5Pr2B
- **[Level](https://grants.web3.foundation/docs/Introduction/levels):** 2

## Project Overview :page_facing_up:

### Overview

**Tagline:** Web2-like payment experiences for building Polkadot dApps

We aim to expand kitdot templates to have a comprehensive toolkit that empowers developers to build production-ready applications on Polkadot with Web2-like payment experiences.

**Brief Description:**

Kitdot is a TypeScript development toolkit that helps developers build Polkadot dApps faster with ready-to-use templates. This grant proposal aims to enhance Kitdot with three critical milestones that address the biggest barriers to mainstream Web3 adoption:

1. **Gasless Transactions System** – Templates for gasless dApp interactions using account abstraction. Includes smart contracts, base contracts, relay services, and deployable production code.

2. **X402 Payment Protocol System** – Templates implementing the X402 protocol for content and API monetization. Include token contracts, facilitator services, and full paid API examples.

3. **Ecosystem Collaboration & UX Refinement** – Templates and integrations demonstrating DotConnect, ReactiveDot, Polkadot UI, and Dedot working together. Includes partner coordination, UX improvements, and comprehensive documentation.


**Why We're Creating This:**

WEB3DEV is committed to bringing mainstream adoption to Web3 using Polkadot by eliminating friction points that prevent Web2 developers and end-users from adopting Web3 technologies. Payment UX is the #1 barrier to adoption according to industry research. We believe Polkadot's technical capabilities (low fees, fast finality, cross-chain messaging) make it the ideal platform for next-generation payment applications, but the ecosystem lacks developer-friendly tooling to unlock this potential.

### Project Details

**Current Implementation:**

Kitdot is a CLI-first development toolkit that helps developers build Polkadot dApps through ready-to-use templates. The current implementation (v1.0) provides:

- **Template System:** Remote template loading from GitHub with validation
- **Project Scaffolding:** Automated setup for fullstack, frontend, and backend projects
- **Tool Management:** Cross-platform installation of Rust, Hardhat, Vite, and other development tools
- **Integration Patterns:** Web3Auth social login and native wallet examples

**Architecture:** Built as Node.js CLI using TypeScript, Commander.js for command structure, and degit for template management. The tool orchestrates multiple embedded development tools (Hardhat, Vite, TypeScript compiler) providing a unified interface for Polkadot Cloud development.

**This Grant Proposal:**

This grant will enhance Kitdot with two critical payment features that address mainstream Web3 adoption barriers:

1. **Gasless Transactions:** Templates implementing ERC-2771 meta-transactions on Passet Hub using account abstraction. Enables Web2-like UX where users interact with dApps without holding native tokens for gas fees. Includes forwarder contracts, relay service, and recipient contract patterns.

2. **X402 Payment Protocol:** Templates implementing HTTP-native payments using the X402 protocol with USDT on Passet Hub. Enables seamless programmatic payments for AI agents, APIs, and web services without registration or OAuth flows. Includes custom EIP-3009 USDT wrapper, facilitator service, and frontend integration.

Both features will be packaged as production-ready templates that developers can deploy using `kitdot init`, with comprehensive documentation and example applications demonstrating real-world use cases.

**Technical Research:**

We've conducted hands-on feasibility research for both payment features, testing implementations on Passet Hub and documenting findings through weeks of experimentation. Our notes, contract tests, and learnings have been aggregated into comprehensive reports:
- **Gasless Transactions:** https://research.w3d.community/gassless-transactions
- **X402 Protocol:** https://research.w3d.community/x402

**Ecosystem Collaboration:**

Throughout development, we maintain close collaboration with key ecosystem partners to ensure seamless integration:
- Worked with MetaMask DevRels to ensure Web3Auth compatibility with Passet Hub
- We are going to reach out to DotConnect, ReactiveDot, Polkadot UI, and Dedot core developers to build frontends using their tools and resources.
- We already have a channel of contact with thirdweb and we are going to reach out to Pimlico and Biconomy to discuss Asset Hub Integration on their infrastructure.

### Ecosystem Fit

**Position in Polkadot Ecosystem:**

Kitdot Payment Features sits at the intersection of developer tooling and payment infrastructure. It complements existing Polkadot tools by providing higher-level payment abstractions that Web2 developers can immediately understand and use without deep blockchain knowledge.

**Target Audience:**

1. **Primary:** Web2 developers transitioning to Web3 (JavaScript/TypeScript developers with no blockchain experience)
2. **Secondary:** dApp builders needing payment solutions (e-commerce, SaaS, creator economy, gaming)
3. **Tertiary:** Polkadot parachain teams wanting to add payment features to their chains
4. **Quaternary:** End users who benefit from gasless transactions and stablecoin payments


**Similar Projects in Related Ecosystems:**

- **Ethereum:** Pimlico, Biconomy (ERC-4337 bundlers) - Focus only on account abstraction, no UX improvements or X402 protocol

## Team :busts_in_silhouette:

### Team members

- **Yan Luiz** (nomadbitcoin) - Lead Developer
- **Anna Bida** - Project Manager, Documentation, QA & Reports

### Contact

- **Contact Name:** Yan Luiz
- **Contact Email:** yan@w3d.community
- **Website:** https://w3d.community/ && https://kitdot.dev/

### Legal Structure

- **Registered Address:** Avenida Paes de Barros, 3399, Suite R
Barueri São Paulo 03149-100
- **Registered Legal Entity:** Multiplica LTDA

### Team's experience

**WEB3DEV Community:**
WEB3DEV is Brazil's largest Web3 educational community with over 10,000 registered developers. Since 2022, the community has provided free Portuguese technical education including specialized Ethereum development courses, Rust bootcamps, and governance education, successfully graduating 500+ developers from online programs. WEB3DEV is also supporting and educating builders on Polkadot Hackatons happening in LATAM: https://latinhack.io/ and https://sub0.gg/

**Yan Luiz (Lead Developer):**
- PBA4 Alumni (Polkadot Blockchain Academy Hong Kong 2024, developer track)
- Founder of WEB3DEV and active Polkadot educator
- Creator of Kitdot, featured in Polkadot Ecosystem tools directory
- Created comprehensive [Rust State Machine bootcamp](https://build.w3d.community/courses/Rust_State_Machine) and an educational platform to host open courses.
- Extensive Web3 development experience across DeFi, tokens, NFTs, staking, and cross-chain products
- Collaborated with MetaMask DevRels to integrate Web3Auth for Passet Hub
- Over 4 years experience auditing blockchain projects and building tokenized vaults for automated strategies
- Created first comprehensive Portuguese-language Solidity/EVM development course
- Background: Python automation, data mining, SEO, Linux server management, researching crypto since 2013

**Anna Bida (Project Manager):**
- 15 years experience in Business Administration focusing on project, process, and people management
- Co-leader of WEB3DEV, coordinating technical education and collaborative learning experiences
- Organizes study groups on decentralized governance, DAOs, and collective coordination
- Mentors teams in hackathons on product strategy and pitch creation
- Co-host of Attempts at Governance (AAG) show covering Polkadot ecosystem in Portuguese
- Part of OpenSync (Polkadot) team following OpenGov proposals with focus on delivery and outcomes
- Applies governance in practice at Ipê City Network State experiment

**Project Experience:**

Kitdot CLI v1.0 has demonstrated significant real-world impact:

**Latin Hack Success:**
- Widely adopted during Latin Hack hackathon (https://latinhack.io)
- Over 50% of participants used Kitdot based on feedback and code review during judging
- 2 out of 3 winners used Kitdot to deploy contracts and build UIs with Web2-like experience
- Successfully onboarded 90%+ of audience into Polkadot (first Web3 experience for most participants)
- Detailed impact: https://docs.google.com/document/d/1OiKZWmJKH94GohlXupwLvkHY-QE-9OeJ-yGTm2fXzJU/edit

**Ecosystem Recognition:**
- Invitation to support Sub0 Hackathon participants
- Project endorsed by many community members and KOLs.
- Listed on Polkadot [Ecosystem tools directory](https://polkadotecosystem.com/tools/dev/kitdot)
- See more on [this forum discussion](https://forum.polkadot.network/t/kitdot-build-web2-like-apps-on-polkadot/15303)


### Team Code Repos

- https://github.com/w3b3d3v/kitdot (Kitdot CLI main repository)
- https://github.com/w3b3d3v/web3auth-examples/tree/web3dev-version (Web3Auth Asset Hub integration)
- https://github.com/w3b3d3v/create-polkadot-dapp/tree/web3dev-version (Polkadot dApp templates)
- https://github.com/nomadbitcoin (Yan's personal contributions)

### Team LinkedIn Profiles

- https://www.linkedin.com/in/nomadbitcoin/ (Yan Luiz)
- https://www.linkedin.com/in/annabida/ (Anna Bida)

## Development Status :open_book:

**Current Implementation Status:**
- **Kitdot CLI v1.0** launched and available at https://kitdot.dev/
- Initial codebase for project scaffolding and template generation
- Web3Auth integration patterns established
- Smart Contract setup initialization for PolkaVM development
- AGENTS.md file with comprehensive context for LLMS

**Research & Prior Work:**

Our team has completed comprehensive feasibility research for both payment features, including:

**Gasless Transactions Research:**
- PolkaVM compatibility testing with simplified forwarder contracts
- ERC-2771 meta-transaction standard analysis
- Constructor storage constraint solutions for Passet Hub
- Relay service architecture design adapted for PolkaVM
- Complete implementation roadmap validated through prototyping

**X402 Protocol Research:**
- USDT EIP-3009 compatibility analysis (standard USDT lacks required functions)
- Custom USDT wrapper contract design for Passet Hub
- Self-hosted facilitator architecture for PolkaVM
- Multi-dimensional resource metering integration
- HTTP 402 payment flow validation

**Documentation:**
- Research findings aggregated at https://research.w3d.community/gassless-transactions and https://research.w3d.community/x402
- Architecture documents detailing PolkaVM-specific adaptations
- Technical specifications for both payment systems

## Development Roadmap :nut_and_bolt:

### Overview

- **Total Estimated Duration:** 5 months
- **Full-Time Equivalent (FTE):** 1.5 FTE
- **Total Costs:** 30,000 USD (USDT or USDC)
- **DOT %:** 0% (100% stablecoin payment in USDT/USDC/HOLLAR)

### Milestone 1 — Gasless Transactions System

- **Estimated Duration:** 2 months
- **FTE:** 1.5
- **Costs:** 10,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 1. | Simplified Forwarder Contract | Solidity smart contract implementing ERC-2771 forwarder pattern adapted for PolkaVM constraints. Features: EIP-712 signature verification, nonce management, deadline validation, and call forwarding with sender extraction. Optimized to avoid constructor storage operations. |
| 2. | ERC2771Context Base Contract | Simplified recipient contract base that extracts real sender from forwarded calls. Enables existing contracts to support gasless transactions by inheriting this base. |
| 3. | Relay Service (Gasless Module) | Node.js/TypeScript service that accepts signed meta-transactions, validates them off-chain, and submits to forwarder contract. Features: whitelist management (user/contract/function-based), gas estimation for PolkaVM, rate limiting, and monitoring. |
| 4. | Whitelist Strategy Templates | Production-ready whitelist implementations: user-based (specific addresses authorized), contract-based (specific target contracts), function-based (specific function selectors), and hybrid approach. Each with rate limiting and gas budgets. |

### Milestone 2 — X402 Payment Protocol System

- **Estimated Duration:** 2 months
- **FTE:** 1.5
- **Costs:** 10,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 1. | USDT Wrapper Token Contract | Custom USDT implementation with full EIP-3009 support optimized for PolkaVM. Features: transferWithAuthorization, receiveWithAuthorization, signature-based transfers, nonce management, time-bound authorizations. Based on USDT0/txfusion patterns adapted for constructor constraints. |
| 2. | Self-Hosted Facilitator (X402 Module) | Payment processor service that validates X402 payments, verifies EIP-3009 signatures, and submits transactions to Passet Hub. Adapted for PolkaVM's multi-dimensional resource metering. Features: payment verification API, blockchain settlement, confirmation tracking, and replay protection. |
| 3. | HTTP 402 Server | Express/Fastify middleware implementing X402 challenge-response flow. Issues HTTP 402 challenges with payment details, verifies payment proofs via facilitator, and delivers resources upon confirmation. |
| 4. | Kitdot Template: X402 Paid API | Complete template for monetizing APIs with X402 payments. Includes: Express API server with 402 middleware, React frontend with payment handling, USDT Wrapper token contracts, facilitator configuration, and example paid endpoints (content access, data queries, AI agent integration). |

### Milestone 3 — Ecosystem Collaboration & UX Refinement

- **Estimated Duration:** 1 month
- **FTE:** 1.5
- **Costs:** 10,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 1. | Ecosystem Tool Partnerships | Reach out to and collaborate with ecosystem tool teams including: DotConnect, ReactiveDot, Polkadot UI, Dedot, PAPI, LV Wallet, and other builders. Goal: Understand integration requirements, gather technical guidance, and coordinate on template development. |
| 2. | Gasless Transaction Integration Templates | Build at least 2 production-ready templates demonstrating gasless transactions using ecosystem tools from partnerships above. Templates will showcase real-world use cases (e.g., gasless NFT minting with wallet X, gasless DeFi interaction with tool Y) with complete documentation. |
| 3. | X402 Payment Integration Templates | Build at least 2 production-ready templates demonstrating X402 payments using ecosystem tools from partnerships above. Templates will showcase monetization use cases (e.g., paid API with tool X, content paywall with wallet Y) with complete documentation. |
| 4. | UX Bounty Feedback Implementation | Address all feedback from UX Bounty team regarding developer experience improvements. This includes: refining landing page narrative, improving onboarding flow, enhancing CLI user interface, and iterating on documentation based on usability testing. |
| 5. | Developer Experience Refinement | Based on ecosystem partner feedback and UX Bounty recommendations, improve: error messages, debugging tools, template discovery, configuration workflows, and overall developer journey from installation to production deployment. |
| 6. | Integration Documentation | Comprehensive guides showing how to use Kitdot payment features with each partnered ecosystem tool. Includes: setup instructions, code examples, troubleshooting guides, and best practices for production deployments. |

## Future Plans

**Adoption & Promotion:**
After milestone completion, we'll drive adoption through live coding sessions, community partnerships across LATAM and globally, hackathon workshops, and published case studies of projects built with Kitdot.

**Continuous Improvement:**
We'll maintain an open feedback form for feature requests, iterate based on real-world usage, continuously refine documentation, and expand templates as the ecosystem evolves.

**JAM Migration:**
Once JAM is available, we plan to migrate relay services (gasless transactions and X402 facilitator) to JAM services, eliminating centralized off-chain dependencies while maintaining backward compatibility.

## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Community feedback and Polkadot ecosystem discussions about next steps for Kitdot.