# IMC Prosperity Trading Challenge 2025

This repository contains the complete codebase and reasoning developed for the IMC Prosperity Trading Challenge 2025.

### About the Challenge

Organized by IMC Trading, Prosperity is a 15-day competition where participants design autonomous trading strategies and solve real-world trading puzzles under uncertainty.

The competition is split into:

Algorithmic Trading: Building real-time trading bots interacting with a simulated exchange.

Manual Trading: Solving complex, game-theoretic, and probabilistic optimization problems.

Our team engineered models that balanced theoretical rigor and practical robustness, adapting dynamically to market conditions as complexity increased round after round. At the end, we ranked 32th in the world and 3rd in France on over 12600 participants.

### Project Structure

/algo_finalsub/
    r1_submitted.py
    r2_submitted.py
    r3_submitted.py
    r4_submitted.py
    r5_submitted.py
    datamodel.py

/manual_trading/
    manual.ipynb
    round2_manual.py
    round3_manual.ipynb
    round4_manual.ipynb

Note: datamodel.py is required for the algorithmic code to run. It must be placed manually in the working directory. It is not available via pip or external package managers.

### Highlights

#### Algorithmic Trading:

- Adaptive inventory-based quoting
- Synthetic arbitrage across composite products
- Option pricing approximations with implied volatilities (Brent root-finding method)
- Real-time decision engines under latency and transaction constraints

#### Manual Trading:

- Application of Quantal Response Equilibrium (QRE) to model bounded rationality
- Analytical derivations and sensitivity analysis
- Portfolio optimizations balancing alpha generation and cost minimization

### Installation & Running

To reproduce our local environment:

pip install numpy pandas matplotlib seaborn

Place datamodel.py in the same directory as the algorithm files.

Manual trading solutions can be run directly via Jupyter notebooks.

This project was developed on Python 3.12.

### Why This Project Matters

This competition taught us how to:
- Design robust, adaptive strategies for highly dynamic markets.
- Implement and validate quantitative methods under real-world execution constraints.
- Balance between theoretical optimality and practical viability.


### Credits

Thanks to my incredible and talented team, who helped me improve and learn so much. Thanks also to IMC Trading for hosting one of the most realistic and challenging student competitions in algorithmic trading.
