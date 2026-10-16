# Feature NNN: <name> — PLAN

Status: Draft | In review | Approved
Based on spec version: <x.y>
Plan version: 0.1

> HOW only. Every decision here must trace back to a requirement in spec.md.

## 1. Approach summary
Two or three sentences.

## 2. Modules touched
Which of: Identity, Blueprint, RAS Graph, Intake, Ranking, Commitment, Reviews, Data Products, Billing.

## 3. Data model
Tables, columns, types, indexes, constraints. Every tenant-scoped table carries `industry_id`.

## 4. API contract
Endpoints, request and response shapes. Must match `specs/contracts/openapi.yaml`.

## 5. Events emitted or consumed
Names and payloads. Must match `specs/contracts/events.md`.

## 6. Module design
Public interface of each module touched. No cross-module table access.

## 7. LLM usage (if any)
Prompt name and version, schema for outputs, which model tier, cost expectation.

## 8. Security and privacy
Auth rules, RBAC, row-level security, PII handling.

## 9. Test strategy
Unit, integration, contract, replay tests. Map to acceptance criteria.

## 10. Risks and rollback
What could go wrong and how to undo it.
