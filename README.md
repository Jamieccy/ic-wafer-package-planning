ic-wafer-package-planning

IC design supply chain rolling planning system.  It calculates wafer and package work orders based on customer orders,  process parameters (EPI layers, technology node, etc.) and lead time rules,  and generates purchase recommendations for wafer suppliers and package houses.

# IC Supply Chain Rolling Planning System

This project simulates a **real IC design company supply chain scenario**:

- Customer places wafer / IC orders with requested delivery dates.
- Each product has different **process parameters**:
  - Technology node (e.g. 28nm, 40nm)
  - EPI layers
  - Process complexity (metal layers, special steps)
- Each foundry / package house has different **lead time (LT)** rules.

The system helps the planner to:

1. Calculate the required **wafer start** and **package work orders** based on customer demand and lead time rules.
2. Generate **purchase orders** (PO) suggestions for wafer suppliers.
3. Provide a **rolling planning view** (e.g. weekly) so the planner can continuously update orders and re-generate work orders.

## Tech Stack

- **Frontend**: Figma for UI design, then Nuxt.js (Vue framework)
- **Backend**: Django + Django REST Framework
- **Database**: (To be decided, e.g. PostgreSQL or SQLite for demo)
- **OS**: Windows

## Project Goals

- Show how to combine **supply chain planning logic** with a **web system**.
- Demonstrate rolling planning based on:
  - Customer order demand
  - Process parameters (lead time, EPI layers, etc.)
  - Supplier lead time and capacity constraints (later phase)

This project will be developed step by step for interview preparation.
