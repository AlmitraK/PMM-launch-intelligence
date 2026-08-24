# Orchestrator

Intended flow:
1. select company
2. create new launch / upload PRD
3. load company context + approved memory
4. run Agent 1
5. human approval
6. run Agent 2 + verifier
7. human approval / publish
8. ingest actual metrics
9. run Agent 3
10. review/promote memory proposals

Do not make agents directly mutate each other or self-promote memory.
