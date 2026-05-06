# GSoC-2026-Proposal-for-SymPy

My GSoC 2026 proposal for SymPy - https://drive.google.com/file/d/12sOocdxNUTsieGMxxQY6P34Z-aWrnBst/view?usp=sharing

Title - Enhancing Assumptions via EUF Integration, LRA Robustness, and Property-Based Testing

Description - This project focuses on making SymPy's assumptions system more robust, efficient, and reliable through a three component architectural upgrade. The first component introduces a backend solver for Equality Logic and Uninterpreted Functions (EUF) directly into the SAT engine. The second component upgrades the Linear Real Arithmetic (LRA) solver to safely handle complex domains, irrational boundary limits, and symbolic infinities (like oo) without failing while also refactoring the core ask dispatcher to resolve many recursion loops during query evaluation. Last component, the project will replace thousands of hardcoded static unit tests with dynamic, property-based tests using the Hypothesis library. By automatically generating complex mathematical trees to find hidden bugs, these enhancements will smooth out the rough edges of the assumptions module, making it a significantly faster and mathematically stronger.
