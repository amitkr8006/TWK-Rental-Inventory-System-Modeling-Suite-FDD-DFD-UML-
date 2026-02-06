# TWK Rental & Inventory System Modeling Suite (FDD + DFD + UML)

This project models the end-to-end business processes of the Teton Whitewater Kayak (TWK) rental operation using structured systems analysis diagrams. It covers front-office customer flows (reservation, rental, return, used-equipment purchase) and back-office operations (inventory, procurement, and reporting). The goal is to produce clear, implementation-ready system models showing how users interact with processes and how data moves through stores and external entities.

## Objectives
- Decompose TWK operations into clear processes and sub-processes using a Functional Decomposition Diagram (FDD).
- Represent system boundaries, external entities, data stores, and information movement using context-level and multi-level Data Flow Diagrams (DFDs).
- Capture user-system interaction logic with a UML use case model and a UML sequence diagram.
- Improve design clarity and completeness through peer feedback and iterative refinement.

## What’s Included
- Functional Decomposition Diagram (FDD) covering customer experience and operational management.
- Context-level DFD showing TWK system boundary and external entities (Customer, Employee, Supplier, Management).
- System-level DFD modelling core processes, data stores, and data exchanges across reservations, rentals, returns, sales, procurement, and reporting.
- Lower-level DFD detailing the used equipment purchase process (tagging/quality checks, reclassification, status updates, charge calculation, payment, receipt).
- UML use case diagram (reservation + rental + return) with structured use case specification including preconditions, normal flow, postconditions, and exceptions.
- UML sequence diagram for used equipment purchase including a loop for multi-item purchases and a dedicated payment system interaction.

## Key Design Rules & Assumptions (Highlights)
- Centralized, real-time database supports customer history, inventory status, reservations, deposits, damages, and balances.
- Reservation flow is uniform across online/phone/in-person channels.
- Inventory alerts and reporting support restocking and operational decisions.
- Used equipment sales do not store customer data long-term; details are used only to generate receipts.
- Standard pricing policy for used equipment is applied consistently during purchase calculations.

## Outcome
A cohesive modelling package that translates a real-world rental business into clear system models—useful for requirements clarification, process improvement, and implementation planning—refined through peer feedback to improve clarity, completeness, and usability.
