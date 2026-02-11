# Product Requirements Document (PRD): "SmartSpec" Compliance Agent

| Attribute | Details |
| :--- | :--- |
| **Product Name** | SmartSpec Audit Agent |
| **Target User** | Technical Engineers (Initiators) & Procurement Specialists (Reviewers) |
| **Status** | Draft v1.0 |
| **Date** | 2026-02-11 |

## 1. The Core Problem (JTBD)
**Context:** KTZ procurement is bottlenecked because technical specifications submitted by field engineers are frequently non-compliant with shifting regulations (ESG, Local Content, GOST Standards), forcing Procurement Officers to manually reject and redline documents.

**The Job to be Done (JTBD):**
> "When I am creating a technical specification for a new tender, I want to inevitably draft it correctly the first time by having it automatically checked against all current rules, so that I can get my materials faster and avoid the 'rejection loop' with the Procurement department."

## 2. Strategic Alignment
*   **Goal 1 (Efficiency):** Reduces "Time to Tender" by eliminating rework loops.
*   **Goal 4 (Digitalisation):** Moves from "Digital Postman" (moving PDFs) to "Smart Validation" (understanding content).
*   **Goal 5 (ESG):** Enforces environmental standards (e.g., "no lead-acid batteries") at the source of the request.

## 3. The Solution: AI-Powered "Compliance Guardrails"
We will build a **Generative AI Agent** embedded in the specification drafting workflow. It acts as a "Virtual Compliance Officer."

### Core Value Proposition
*   **For Engineers:** "Instant feedback." No more waiting 3 weeks to be told you used the wrong font or cited a dead law.
*   **For Procurement:** "Clean inbox." Only 100% compliant specs reach the final review stage.

## 4. Functional Requirements

### 4.1. The "Live-Check" Editor (The Interface)
*   **FR-01:** The system MUST provide a text editor (or Word plugin) where engineers draft specifications.
*   **FR-02:** The system MUST highlight non-compliant terms in real-time (e.g., red underline for expired GOSTs, yellow for missing Local Content clauses).

### 4.2. The "Rule Engine" (The Brain)
*   **FR-03:** The Agent MUST ingest and index unstructured regulatory documents (Internal KTZ Orders, Samruk-Kazyna Rules, National Laws) nightly.
*   **FR-04:** The Agent MUST be able to semantically map a "requested item" (e.g., "Railpad Type 2") to its specific regulatory requirements.

### 4.3. The "Auto-Fix" Capability (The Accelerator)
*   **FR-05:** Upon detecting an error (e.g., "This spec is missing the ESG disposal clause"), the Agent MUST propose a specific text insertion to fix it.
*   **FR-06:** The Agent MUST generate a "Compliance Certificate" score (0-100%). Procurement Officers can filter their inbox to see only documents with Score > 95%.

## 5. Non-Functional Requirements
*   **Auditability:** Every "correction" suggested by the AI must cite the specific source document (e.g., "Suggested per Rule 402, Section 3.1").
*   **Security:** Data must remain on-premise (private cloud) to comply with KTZ internal security policies.

## 6. Meaningful Metrics (Success Criteria)
*   **Primary Metric:** "First-Pass Yield" (Percentage of specs approved by Procurement without return). Target: 20% &rarr; 80%.
*   **Secondary Metric:** "Procurement Cycle Time" (Request to Tender Published). Target: Reduction from 45 days to 15 days.
