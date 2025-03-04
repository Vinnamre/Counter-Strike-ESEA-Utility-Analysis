# Counter-Strike ESEA Tournament Utility-Based Analysis

## Overview
This project analyzes utility usage in Counter-Strike: Global Offensive (CS:GO) during the ESEA Tournament (South Pacific). The dataset includes thousands of competitive games, tracking utility such as smoke grenades, flashbangs, and hand grenades to understand their impact on round outcomes, bomb plants, and overall strategy.

## Dataset
The analysis is based on multiple datasets containing:
- **Grenade usage**: Location, type, and impact of grenades used by both teams.
- **Match metadata**: Map selection, round duration, and winner statistics.
- **Player statistics**: Equipment value, damage dealt, and kill information.

The primary focus is on Mirage, one of the most balanced maps in CS:GO.

## Key Findings
- **Mid Control Importance (T-Side)**: Most smokes are thrown around Mid, Connector, and Market to facilitate rotations and site control.
- **A and B Executions**: Ts use smokes to block CT vision and flashes to push into sites, while HEs and Molotovs clear common defensive spots.
- **CT-Side Defensive Utility**: CTs use smokes to delay pushes (A-Main, B-Apps), Molotovs to deny rushes, and flashes to regain lost areas or execute retakes.
- **Round Outcomes**: Utility plays a crucial role in site control, post-plant defense, and retakes, directly influencing win rates.

## Tools & Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - **pandas** – Data manipulation and analysis
  - **numpy** – Numerical computations
  - **seaborn** – Data visualization
  - **matplotlib** – Plotting graphs
  - **scikit-learn** – Machine learning models for pattern recognition
  - **tensorflow** – Deep learning analysis (if applicable)

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/csgo-utility-analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis script:
   ```bash
   python analysis.py
   ```

## Future Enhancements
- Extend analysis to other maps.
- Build predictive models for grenade effectiveness.
- Create visual heatmaps for utility usage patterns.

## Contributing
Feel free to fork this repository and submit pull requests for improvements or additional insights!

## License
MIT License
