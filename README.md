# Supply Chain Optimization Model
## Supply Chain Network Optimizer — Browser-Based Distribution Tool
A single-file, browser-based supply chain optimization app built with vanilla HTML, CSS, and JavaScript. Developed as part of a Decision Models course project (BANA 4095), this app models and solves a multi-stage distribution problem entirely in the browser — no installation or backend required.

**Features:**
* Solves minimum-cost distribution across a 3-stage supply chain (Factories → DCs → Retailers)
* Editable input fields for costs, capacities, and demand values
* Compares baseline vs. expansion scenarios with cost recommendations
* Interactive network diagram showing active/inactive routes, shipment volumes, and flow direction
* Handles infeasible problems with clear error messages

**Tech Stack:**
* Vanilla HTML / CSS / JavaScript
* JavaScript LP/transportation solver via CDN

**Usage:**
* Just open supply-chain.html in any modern browser (Chrome, Firefox, Edge). No setup needed.

**Validated Against:**
* Sports of All Sorts skateboard distribution network: **3 factories; 4 distribution centers; 3 retailers** (expansion scenario analysis included)

<img width="1920" height="826" alt="Screenshot 2026-05-16 at 9 37 47 PM" src="https://github.com/user-attachments/assets/4e48da09-8d72-4bd7-8d37-b8b2ab0b4744" />
<img width="1920" height="959" alt="Screenshot 2026-05-16 at 9 34 54 PM" src="https://github.com/user-attachments/assets/16793d6b-15eb-4c7f-9354-26621273a184" />



