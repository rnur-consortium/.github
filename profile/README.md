# Reddit Neographical Unicode Registry (RNUR) Consortium

Welcome to the official GitHub home of the **RNUR Consortium**. We are a collaborative community organization dedicated to the digital preservation, standardization, and structured allocation of constructed scripts (conscripts) and neographies within the Unicode standard.

Our primary focus is the technical architecture, glyph metrics, and registry coordination of under-represented and constructed writing systems, maintaining full comprehensive management over all **Unicode Private Use Area (PUA)** code points.

---

## 🗺️ Mission & Scope

The RNUR Consortium acts as an open, community-driven registry framework to ensure stable, conflict-free digital mapping for modern neographies. By establishing clear typography standards and registry tables, we enable font engineers, conlangers, and software developers to share a unified architectural space.

*   **Total PUA Management:** Coordinating systematic script allocations across all designated Unicode Private Use Areas, spanning Plane 0 (Basic Multilingual Plane), Plane 15, and Plane 16.
*   **Font Engineering & Standardization:** Promoting strict guidelines for glyph metrics, scaling rules, and script properties.
*   **Digital Preservation:** Building human-readable registry infrastructure and technical documentation for constructed writing systems.

---

## 📐 Allocation Framework: Working in Sets

To maintain structural integrity and scalability across the vast landscape of the PUA, the RNUR architecture organizes script allocations using a **strict set-based framework**. Rather than scattering scripts ad-hoc, allocations are grouped into distinct, logical **Sets** based on script properties, complexity, and community usage status.

*   **Modular Organization:** Every script belongs to a designated Set, ensuring that block ranges across all PUA planes are highly organized and predictable.
*   **Collision Prevention:** Set-based sorting allows multiple engineers to develop fonts and data tables concurrently without overlapping code points.
*   **Scalable Metrics:** Grouping scripts into technical sets makes it easier to apply uniform scaling rules, tracking rules, and glyph metrics to similar writing systems.

---

## 📂 Core Registries & Projects

Our repositories host the active development of our standards, font hubs, and registry tables:

| Repository | Description | Status |
| :--- | :--- | :--- |
| **`registry-tables`** | The master data files, allocation sets, and character mapping tables for all Unicode PUA planes. | 🏗️ In Development |
| **`FontsHub`** | Central repository for compliant font files, engineering tools, and typography metrics. | ⚙️ Active |
| **`documentation`** | Technical specifications, submission guidelines, and architectural rules for script inclusion. | 📝 Drafting |

---

## 👥 Collaboration & Community

The RNUR Consortium thrives on community input and expert collaboration. We work alongside pioneers in the neography and conscript registry spaces to maintain compatibility and structural integrity across digital registries.

### How to Get Involved
1.  **Review the Specs:** Check our active registry sets to see current PUA allocations.
2.  **Submit a Proposal:** Open an issue or submit a pull request if you are looking to register or standardize a script allocation.
3.  **Contribute to FontsHub:** Help us refine glyph architectures, loopless variants, or custom font metrics.

---

## 🛡️ Governance & Contact

The RNUR Consortium is managed by independent script engineers, font designers, and neographers. 

*   **Inquiries:** For formal coordination, script registry requests, or infrastructure questions, please open an issue in our meta repository or contact the administration via the organization's listed endpoint.
*   **Licensing:** All registry data schemas and open-source documentation are preserved under highly accessible open licenses to ensure long-term digital utility.

***
*Securing the digital future of constructed writing systems, one plane at a time.*
