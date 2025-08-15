Mrcrypto is a powerful and modular CLI toolkit designed for researchers, developers, and cybersecurity enthusiasts to analyze and audit blockchain address activity. It allows users to scrape the most active wallet addresses from public blockchain explorers and test private key combinations against them using high-speed brute-force scripts.

The toolkit supports major networks including Bitcoin (BTC), Ethereum (ETH), Solana (SOL), Dogecoin (DOGE), Litecoin (LTC), and Dash (DASH). With a queue-based system, concurrency management, and .bat launcher support, Striker offers flexibility for both single-chain and multi-chain operations.



<img width="294" height="340" alt="Image" src="https://github.com/user-attachments/assets/0b5d26fb-413b-49b1-af57-ada08c062895" />
<img width="348" height="257" alt="Image" src="https://github.com/user-attachments/assets/49e44925-ab40-41ba-9e76-35635f7d6ae2" /> 


Features
Address Parsers for:
BitInfoCharts: BTC, DOGE, LTC, DASH
Etherscan: ETH
SolScan: SOL
Brute-force engines for multiple blockchains
Queue-based processing with concurrency limits
Clean output to .txt files, one per chain
Launchable via .bat for Windows automation
Modular codebase for extending networks easily


Mrcrypto repository is organized to ensure modularity and ease of use:

parsers/ — Contains individual scrapers for top wallet addresses (one per chain).
tablet/ — Includes brute-force scripts tailored for each blockchain.
run_parsers.js — Script that executes all available parsers sequentially.
Mrcrypto.js — Launches all brute-force modules in parallel (up to 6 simultaneously).
.bat files:
1. Run parsers for create bases.bat — Launches all parsers and generates address lists.
2. Start.bat — Starts all brute-force scripts using the generated address lists.
package.json — Contains dependencies and project metadata.
This layout allows quick setup, testing, and extension to new chains with minimal adjustments.


For full version write me on discord : endorphine_a



BTC - 50 USDT
ETH - 75 USDT
DOGE - 100 USDT
DASH - 120 USDT
USDT/TRX - 150 USDT


⚙ Installation
⚠️ Requires Node.js 22.11.0 or higher
✅ Recommended: Use Node.js version manager like nvm

🛠Manual Setup
If you prefer not to use Git:

Download the repository as a .zip or copy the project files manually.
Open your terminal in the project folder.
Install dependencies: npm install
