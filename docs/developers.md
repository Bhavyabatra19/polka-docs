# Developer Guide

This section is for contributors, integrators, and bot developers.

## 🔌 API Access

Use our GraphQL API:

```graphql
query {
  posts(limit: 5) {
    title
    proposer
    onchainLink {
      onchain_proposal_id
    }
  }
}
