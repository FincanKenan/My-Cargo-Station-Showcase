# 📦 My Cargo Station

**Playable – In Development | 3D Management Simulation | Unity & C#**

My Cargo Station is a playable 3D management simulation currently in development with Unity and C#.

The player manages a cargo branch by handling incoming deliveries, warehouse storage, customer requests, product transfers, workers, and branch operations.

---

## 🎮 Gameplay

The core gameplay loop connects cargo handling, customer service, warehouse management, and branch operations.

**receive cargo → store products → serve customers → manage demand → improve the branch**

<img width="600" height="1000" alt="Ekran görüntüsü 2026-10-13 061512" src="https://github.com/user-attachments/assets/b35a16e4-0ddc-4709-963d-9e0645d362df" />


---

## 🔄 Core Management Loop

The game is built around a daily branch-management cycle.

During each day, the player:

1. Receives incoming cargo
2. Transfers products into storage
3. Manages available stock
4. Serves customer requests
5. Handles branch operations
6. Reviews daily performance and prepares for the next day

<img width="600" height="1000" alt="Ekran görüntüsü 2026-10-13 061409" src="https://github.com/user-attachments/assets/7030f2ca-b9c6-484b-92a3-45065e2a043d" />


---

## 📦 Cargo & Carrying System

Cargo is handled through a data-driven carrying system.

Different items can have different:

- Carry values
- Vehicle requirements
- Visual prefabs
- Placement offsets
- Storage behavior

Carriers use configurable grid dimensions, depth, layers, spacing, and capacity rules.

Items are visually arranged based on their size and carrying value.

<img width="600" height="1000" alt="Ekran görüntüsü 2026-10-13 061457" src="https://github.com/user-attachments/assets/67a09fba-9871-4aaa-8ea8-6a66a1de685d" />


---

## 🏬 Warehouse & Storage

Products are stored using product-specific racks and storage rules.

The warehouse system supports:

- Product-specific racks
- Rack capacity
- Multiple storage locations
- Transfer between carriers and storage
- Expandable branch layouts

<img width="600" height="1000" alt="Ekran görüntüsü 2026-10-13 061548" src="https://github.com/user-attachments/assets/f375bf6c-ad46-4f8a-8198-9f58eb0ba42d" />


---

## 👥 Customer & Service Flow

Customers enter through the branch entrance and follow a queue-based service system.

The flow includes:

- Customer spawning
- Queue positions
- Service points
- Waiting / patience logic
- Product delivery
- Customer exit flow

Customer behavior is separated from supplier and warehouse workflows.


---

## 🚚 Inbound & Supplier Flow

Incoming deliveries use a separate supplier flow.

Suppliers enter through the warehouse side of the branch and deliver ordered cargo near the storage area.

Customer and supplier paths are intentionally separated to keep branch operations readable and modular.


---

## 📊 Orders, Demand & Economy

Branch demand is generated based on the products currently available in the branch.

The system includes:

- Daily demand generation
- Product orders
- Stock requirements
- Revenue and expenses
- Reputation
- Branch progression

Orders placed for future demand are delivered during the next operating day.

<img width="600" height="1000" alt="Ekran görüntüsü 2026-10-13 061605" src="https://github.com/user-attachments/assets/e829e7d7-7cdf-4920-b677-402a36d144fa" />


---

## 💻 PC Management System

The in-game PC acts as the main management interface for branch operations.

Current and planned management areas include:

- Daily demand
- Product orders
- Products
- Workers
- Branch information
- Economy and reporting

The PC interface is designed to centralize management systems without interrupting the physical gameplay loop.

<img width="600" height="1000" alt="Ekran görüntüsü 2026-10-13 061718" src="https://github.com/user-attachments/assets/1cff0b71-a1dd-4905-b373-a3cd2ac31ce6" />


---

## 🧑‍💼 Worker System

Worker roles are designed around branch operations.

Current role structure:

- Inbound
- Outbound
- Cashier

Workers are intended to have upgradeable runtime stats such as movement speed, carrying capacity, transfer speed, working behavior, and equipment access.

---

## 🏗️ Branch & Facility Architecture

The branch layout is designed to support future expansion.

Current systems include:

- Configurable branch dimensions
- Modular walls
- Adjustable entrances and delivery openings
- Customer and supplier spawn areas
- Warehouse and service zones
- Expandable facility systems

The architecture is designed so future branches can use different sizes, layouts, and operational configurations without rebuilding the core systems.

<img width="1000" height="700" alt="Ekran görüntüsü 2026-10-13 062548" src="https://github.com/user-attachments/assets/7777c791-2096-43f0-ba96-ca4aae327165" />

---

## 🎮 Character & Animation

The player uses a CharacterController-based movement system.

The project also includes:

- Runtime movement
- Character rotation
- Gravity handling
- Animator integration
- Mixamo animation workflow
- Support for future vehicle interaction


---

## ⚙️ Core Systems

- 3D player movement
- Cargo carrying and visual stacking
- Product-specific storage
- Customer queue and service flow
- Supplier / inbound delivery flow
- Daily demand generation
- Order and stock management
- Economy and reputation foundations
- PC management interface
- Worker role architecture
- Modular branch layout
- Configurable facility systems
- Save-ready gameplay architecture
- Data-driven item configuration

---

## 🧱 Tech Stack

- Unity
- C#
- ScriptableObjects
- CharacterController
- Unity UI / TextMeshPro
- Animator / Mixamo
- Git / GitHub

---

## 📱 Project Status

**Playable – In Development**

The current build includes the core branch environment, player movement, cargo handling foundations, customer/service systems, demand generation, management UI, and modular branch architecture.

The project is actively being expanded with additional management, worker, economy, and branch progression systems.

The full production source code is kept private.

This repository showcases the project's 3D gameplay systems, management architecture, and technical development for portfolio purposes.
