# A&E Use case to demo GHCP https://github.com/marrobi/product-dev-copilot 

1. Clone https://github.com/marrobi/product-dev-copilot
2. Review the prompts and follow instructions to build your prototype
3. This repo shows the following results
  - Problem Statement for A&E Triage: saved in tmp/scenario.md
  - Personas for the use case: saved personas/
  - User journeys for the scenario in user_journeys/data
  - Prototype generated based on the user journey (journey-ae-triage.md): saved in prototype
    - To view the prototype: 
  
    ```bash
    cd prototype && npm install
    npm run build
    npm start
    ```