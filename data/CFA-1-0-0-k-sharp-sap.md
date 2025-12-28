# Section 3.2: K# Layer - The SAP Structural Revolution

## 1. Rationale: From ONC to SAP
The transition from **Onset-Nucleus-Coda (ONC)** to **Subject-Action-Parameter (SAP)** marks the shift from linguistic-probabilistic parsing to deterministic-structural governance. 

## 2. Formal BNF Grammar (K# Syntax)
The K# SAP structure is defined by:
- <instruction> ::= <subject> <action> <parameter_list>
- <subject> ::= "@" <id> | "SYSTEM" | "USER"
- <action> ::= "!" <verb>
- <parameter_list> ::= "(" <parameter> ")"

## 3. Complexity Analysis: O(n)
Strictly linear complexity ensures real-time safety validation without backtracking.
