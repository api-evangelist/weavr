# Weavr

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Weavr is an embedded-finance ("banking-as-a-service") platform that lets software companies embed regulated financial products — managed accounts, IBANs, virtual and physical cards, transfers, sends and wire payments — directly inside their applications. Its Multi API issues accounts and cards to corporate and consumer end-users with full KYB/KYC onboarding, Strong Customer Authentication (SCA) step-up challenges, and client-side "Secure Components" that tokenize sensitive data so the embedder stays out of PCI scope. Weavr operates through regulated EMI partners (Paynetics AD in the EU, Paynetics UK in the UK) and exposes a Multi API, a BackOffice programme-operations API, an Embedded Payment Run API, a Webhooks event surface and a sandbox Simulator API, backed by SDKs for Web, iOS, Android and React Native and an official agent-skills pack.

**Areas:** Embedded Finance · Banking as a Service · Payments · Cards · Fintech · Account · KYC · Company

## Weavr on APIs.io

Everything profiled for Weavr is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/weavr/](https://apis.io/providers/weavr/)** — or go straight to one of the APIs or properties below.

### APIs (54)

- [Weavr Access Token API](https://apis.io/apis/weavr/weavr-access-token-api/) — Acquire a token granting you access to perform sensitive operations on behalf of an identity.
- [Weavr Access Tokens API](https://apis.io/apis/weavr/weavr-access-tokens-api/) — Acquire and revoke access tokens.
- [Weavr Accounts API](https://apis.io/apis/weavr/weavr-accounts-api/) — The Accounts API from Weavr — 2 operation(s) for accounts.
- [Weavr Additional Factors API](https://apis.io/apis/weavr/weavr-additional-factors-api/) — The Additional Factors API from Weavr — 2 operation(s) for additional factors.
- [Weavr Authentication Factors API](https://apis.io/apis/weavr/weavr-authentication-factors-api/) — Manage user authentication factors, including passwords and device-based factors (OTP and push).
- [Weavr Authorised Signatories API](https://apis.io/apis/weavr/weavr-authorised-signatories-api/) — Verify the email of root users who act as authorised signatories of a Corporate or Consumer identity.
- [Weavr Authorised Users API](https://apis.io/apis/weavr/weavr-authorised-users-api/) — Corporate and Consumer identities can invite authorised users to access their account. Once on-boarded, authorised users can create and manage instruments…
- [Weavr Buyer Authorised Users API](https://apis.io/apis/weavr/weavr-buyer-authorised-users-api/) — Buyers can invite authorised users to access their account. Once on-boarded, authorised users can transact on behalf of the identity they are on-boarded…
- [Weavr Buyers API](https://apis.io/apis/weavr/weavr-buyers-api/) — Buyers are identities representing a business Once on-boarded, Buyers can create payment runs and pay their suppliers in your application.
- [Weavr Card Payments API](https://apis.io/apis/weavr/weavr-card-payments-api/) — Retrieve card payment activity, including authorisations, settlements, and related events.
- [Weavr Cards API](https://apis.io/apis/weavr/weavr-cards-api/) — The Cards API from Weavr — 7 operation(s) for cards.
- [Weavr Confirmation Challenges API](https://apis.io/apis/weavr/weavr-confirmation-challenges-api/) — Issue and verify confirmation challenges used to authorise lists of resources.
- [Weavr Consumers API](https://apis.io/apis/weavr/weavr-consumers-api/) — The Consumers API from Weavr — 3 operation(s) for consumers.
- [Weavr Corporates API](https://apis.io/apis/weavr/weavr-corporates-api/) — The Corporates API from Weavr — 3 operation(s) for corporates.
- [Weavr Correspondent Bank Transfers API](https://apis.io/apis/weavr/weavr-correspondent-bank-transfers-api/) — Correspondent bank transfers allow financial institutions to initiate wire transfers on behalf of originators (third parties). These transfers comply with…
- [Weavr Customer Data & Due Diligence API](https://apis.io/apis/weavr/weavr-customer-data-due-diligence-api/) — Manage customer profile data and KYC/KYB due diligence flows for corporates and consumers.
- [Weavr Factors API](https://apis.io/apis/weavr/weavr-factors-api/) — The Factors API from Weavr — 3 operation(s) for factors.
- [Weavr Fees API](https://apis.io/apis/weavr/weavr-fees-api/) — The Fees API from Weavr — 4 operation(s) for fees.
- [Weavr Incoming Wire Transfers API](https://apis.io/apis/weavr/weavr-incoming-wire-transfers-api/) — Incoming wire transfers received from external bank accounts to managed accounts with IBANs.
- [Weavr Institutions API](https://apis.io/apis/weavr/weavr-institutions-api/) — Institutions supported by Embedded Payment Run.
- [Weavr Linked Accounts API](https://apis.io/apis/weavr/weavr-linked-accounts-api/) — The Linked Accounts API from Weavr — 11 operation(s) for linked accounts.
- [Weavr Manage API](https://apis.io/apis/weavr/weavr-manage-api/) — The Manage API from Weavr — 7 operation(s) for manage.
- [Weavr Managed Accounts API](https://apis.io/apis/weavr/weavr-managed-accounts-api/) — Managed Accounts are a type of financial instrument offered by Weavr. They hold funds for their owner, and can be upgraded to IBANs so as to receive and…
- [Weavr Managed Cards API](https://apis.io/apis/weavr/weavr-managed-cards-api/) — Managed Cards are a type of financial instrument offered by Weavr. Cards created in prepaid mode have their own balance, whereas those created in debit mode…
- [Weavr Operations API](https://apis.io/apis/weavr/weavr-operations-api/) — The Operations API from Weavr — 9 operation(s) for operations.
- [Weavr Outgoing Wire Transfers API](https://apis.io/apis/weavr/weavr-outgoing-wire-transfers-api/) — The Outgoing Wire Transfer transaction is used to transfer funds from managed accounts to an external bank account.
- [Weavr Passwords API](https://apis.io/apis/weavr/weavr-passwords-api/) — The Passwords API from Weavr — 5 operation(s) for passwords.
- [Weavr Payment runs API](https://apis.io/apis/weavr/weavr-payment-runs-api/) — A Payment run contains a list of supplier payments. A Payment run can be - created by a user with a `CREATOR` role - confirmed by a user with a `CONTROLLER`…
- [Weavr Roles API](https://apis.io/apis/weavr/weavr-roles-api/) — The Roles API from Weavr — 1 operation(s) for roles.
- [Weavr Sends API](https://apis.io/apis/weavr/weavr-sends-api/) — The Send transaction is used to send funds between managed accounts and managed cards belonging to different identities.
- [Weavr Setup API](https://apis.io/apis/weavr/weavr-setup-api/) — Register and manage the lifecycle of users that can access an identity, including authorised users invited by a Corporate or Consumer root user.
- [Weavr Sign-in API](https://apis.io/apis/weavr/weavr-sign-in-api/) — Sign users in using passwords, biometrics, or third-party auth providers.
- [Weavr Simulator API](https://apis.io/apis/weavr/weavr-simulator-api/) — Simulators enable you to trigger processes in Sandbox that in Production are triggered from an external action rather than from your application. this way…
- [Weavr Simulator Linked accounts API](https://apis.io/apis/weavr/weavr-simulator-linked-accounts-api/) — The Simulator Linked accounts API from Weavr — 2 operation(s) for simulator linked accounts.
- [Weavr Spend Controls API](https://apis.io/apis/weavr/weavr-spend-controls-api/) — Manage spend rules and authorisation forwarding to approve or reject card payments in real time.
- [Weavr Step up API](https://apis.io/apis/weavr/weavr-step-up-api/) — The Step up API from Weavr — 2 operation(s) for step up.
- [Weavr Step-up Challenges API](https://apis.io/apis/weavr/weavr-step-up-challenges-api/) — Issue and verify step-up challenges that elevate an existing user token.
- [Weavr Tokens API](https://apis.io/apis/weavr/weavr-tokens-api/) — The Tokens API from Weavr — 2 operation(s) for tokens.
- [Weavr Transaction Activity API](https://apis.io/apis/weavr/weavr-transaction-activity-api/) — Retrieve the consolidated transaction activity across instruments.
- [Weavr Transfers API](https://apis.io/apis/weavr/weavr-transfers-api/) — The Transfers API from Weavr — 3 operation(s) for transfers.
- [Weavr Trusted Payees API](https://apis.io/apis/weavr/weavr-trusted-payees-api/) — Manage a list of trusted payees for Outgoing wire transfers and Sends. Aside from convenience and a reduced chance of making errors when making…
- [Weavr User Impersonation API](https://apis.io/apis/weavr/weavr-user-impersonation-api/) — The User Impersonation API from Weavr — 1 operation(s) for user impersonation.
- [Weavr Authentication Factors Webhooks API](https://apis.io/apis/weavr/weavr-authentication-factors-webhooks-api/) — Notification of the Authentication Factors that are used for the `Identity`.
- [Weavr Bulk Operations API](https://apis.io/apis/weavr/weavr-bulk-operations-api/) — The Bulk Operations API from Weavr — 0 operation(s) for bulk operations.
- [Weavr Buyers Webhooks API](https://apis.io/apis/weavr/weavr-buyers-webhooks-api/) — Buyers are identities representing companies. Once on-boarded, Buyers can create and manage their own instruments via your application.
- [Weavr Linked Accounts Webhooks API](https://apis.io/apis/weavr/weavr-linked-accounts-webhooks-api/) — Notification that the status of a Linked Account has been updated.
- [Weavr Login API](https://apis.io/apis/weavr/weavr-login-api/) — The Login API from Weavr — 0 operation(s) for login.
- [Weavr Manual Transactions API](https://apis.io/apis/weavr/weavr-manual-transactions-api/) — The Manual Transactions API from Weavr — 0 operation(s) for manual transactions.
- [Weavr Payment runs Webhooks API](https://apis.io/apis/weavr/weavr-payment-runs-webhooks-api/) — Notification that the Payment Run and payment statuses have been updated.
- [Weavr Stepup Webhooks API](https://apis.io/apis/weavr/weavr-stepup-webhooks-api/) — Notification that a step-up has been completed or declined.
- [Weavr Tokens Webhooks API](https://apis.io/apis/weavr/weavr-tokens-webhooks-api/) — Tokens webhooks
- [Weavr Transactions Webhooks API](https://apis.io/apis/weavr/weavr-transactions-webhooks-api/) — Notification that the status of a transaction has been updated.
- [Weavr Ibans API](https://apis.io/apis/weavr/weavr-ibans-api/) — The Ibans API from Weavr — 0 operation(s) for ibans.
- [Weavr Wire Transfers API](https://apis.io/apis/weavr/weavr-wire-transfers-api/) — The Wire Transfers API from Weavr — 2 operation(s) for wire transfers.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (2)

Multi-step workflows that chain operations into a business task.

- [Fund a managed account and move money](https://apis.io/arazzos/weavr/weavr-fund-account-and-transfer/)
- [Onboard a corporate and issue a virtual card](https://apis.io/arazzos/weavr/weavr-onboard-corporate-and-issue-card/)

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Weavr Webhooks](https://apis.io/asyncapis/weavr/weavr-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [weavr](https://apis.io/servers/weavr/weavr/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Weavr Agentic Access](https://apis.io/agentic-access/weavr/weavr-agentic-access/)

#### JSON Schema (23)

The data models the API reads and writes.

- [BulkProcessesPaged](https://apis.io/schemas/weavr/weavr-bulk-processes-paged/)
- [CurrencyAmount](https://apis.io/schemas/weavr/weavr-currency-amount/)
- [Date](https://apis.io/schemas/weavr/weavr-date/)
- [DepositRequest](https://apis.io/schemas/weavr/weavr-deposit-request/)
- [DepositRequestByAccountId](https://apis.io/schemas/weavr/weavr-deposit-request-by-account-id/)
- [DepositResponse0](https://apis.io/schemas/weavr/weavr-deposit-response0/)
- [DepositResponse1](https://apis.io/schemas/weavr/weavr-deposit-response1/)
- [Email](https://apis.io/schemas/weavr/weavr-email/)
- [ImpersonateIdentityLoginRequest](https://apis.io/schemas/weavr/weavr-impersonate-identity-login-request/)
- [LinkedAccountRunRequest](https://apis.io/schemas/weavr/weavr-linked-account-run-request/)
- [Mobile](https://apis.io/schemas/weavr/weavr-mobile/)
- [OutgoingWireTransferCreateRequest](https://apis.io/schemas/weavr/weavr-outgoing-wire-transfer-create-request/)
- [OutgoingWireTransferUpdateBeneficiaryNameRequest](https://apis.io/schemas/weavr/weavr-outgoing-wire-transfer-update-beneficiary-name-request/)
- [ProfileId](https://apis.io/schemas/weavr/weavr-profile-id/)
- [PurchaseRequest](https://apis.io/schemas/weavr/weavr-purchase-request/)
- [PurchaseRequestByCardId](https://apis.io/schemas/weavr/weavr-purchase-request-by-card-id/)
- [PurchaseResponse](https://apis.io/schemas/weavr/weavr-purchase-response/)
- [RbacRole](https://apis.io/schemas/weavr/weavr-rbac-role/)
- [Response](https://apis.io/schemas/weavr/weavr-response/)
- [SendCreateRequest](https://apis.io/schemas/weavr/weavr-send-create-request/)
- [SimulateVerifyChallengeResponse](https://apis.io/schemas/weavr/weavr-simulate-verify-challenge-response/)
- [VerificationCode](https://apis.io/schemas/weavr/weavr-verification-code/)
- [VerifyRequestByAccountId](https://apis.io/schemas/weavr/weavr-verify-request-by-account-id/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Weavr Context](https://apis.io/jsonld/weavr/weavr-context/)

#### Collections (43)

Postman and Open Collection request collections.

- [Weavr Multi Product BackOffice Access Token API](https://apis.io/collections/weavr/open-weavr-access-token-api/)
- [Weavr Multi Product BackOffice Access Token Access Tokens API](https://apis.io/collections/weavr/open-weavr-access-tokens-api/)
- [Weavr Multi Product BackOffice Access Token Accounts API](https://apis.io/collections/weavr/open-weavr-accounts-api/)
- [Weavr Multi Product BackOffice Access Token Additional Factors API](https://apis.io/collections/weavr/open-weavr-additional-factors-api/)
- [Weavr Multi Product BackOffice Access Token Authentication Factors API](https://apis.io/collections/weavr/open-weavr-authentication-factors-api/)
- [Weavr Multi Product BackOffice Access Token Authorised Signatories API](https://apis.io/collections/weavr/open-weavr-authorised-signatories-api/)
- [Weavr Multi Product BackOffice Access Token Authorised Users API](https://apis.io/collections/weavr/open-weavr-authorised-users-api/)
- [Weavr Multi Product BackOffice Access Token Buyer Authorised Users API](https://apis.io/collections/weavr/open-weavr-buyer-authorised-users-api/)
- [Weavr Multi Product BackOffice Access Token Buyers API](https://apis.io/collections/weavr/open-weavr-buyers-api/)
- [Weavr Multi Product BackOffice Access Token Card Payments API](https://apis.io/collections/weavr/open-weavr-card-payments-api/)
- [Weavr Multi Product BackOffice Access Token Cards API](https://apis.io/collections/weavr/open-weavr-cards-api/)
- [Weavr Multi Product BackOffice Access Token Confirmation Challenges API](https://apis.io/collections/weavr/open-weavr-confirmation-challenges-api/)
- [Weavr Multi Product BackOffice Access Token Consumers API](https://apis.io/collections/weavr/open-weavr-consumers-api/)
- [Weavr Multi Product BackOffice Access Token Corporates API](https://apis.io/collections/weavr/open-weavr-corporates-api/)
- [Weavr Multi Product BackOffice Access Token Correspondent Bank Transfers API](https://apis.io/collections/weavr/open-weavr-correspondent-bank-transfers-api/)
- [Weavr Multi Product BackOffice Access Token Customer Data & Due Diligence API](https://apis.io/collections/weavr/open-weavr-customer-data-due-diligence-api/)
- [Weavr Multi Product BackOffice Access Token Factors API](https://apis.io/collections/weavr/open-weavr-factors-api/)
- [Weavr Multi Product BackOffice Access Token Fees API](https://apis.io/collections/weavr/open-weavr-fees-api/)
- [Weavr Multi Product BackOffice Access Token Incoming Wire Transfers API](https://apis.io/collections/weavr/open-weavr-incoming-wire-transfers-api/)
- [Weavr Multi Product BackOffice Access Token Institutions API](https://apis.io/collections/weavr/open-weavr-institutions-api/)
- [Weavr Multi Product BackOffice Access Token Linked Accounts API](https://apis.io/collections/weavr/open-weavr-linked-accounts-api/)
- [Weavr Multi Product BackOffice Access Token Manage API](https://apis.io/collections/weavr/open-weavr-manage-api/)
- [Weavr Multi Product BackOffice Access Token Managed Accounts API](https://apis.io/collections/weavr/open-weavr-managed-accounts-api/)
- [Weavr Multi Product BackOffice Access Token Managed Cards API](https://apis.io/collections/weavr/open-weavr-managed-cards-api/)
- [Weavr Multi Product BackOffice Access Token Operations API](https://apis.io/collections/weavr/open-weavr-operations-api/)
- …and 18 more published on APIs.io

#### Overlays (5)

OpenAPI overlays, including conversational phrasing for each operation.

- [Weavr Multi Backoffice Overlay](https://apis.io/overlays/weavr/weavr-multi-backoffice-overlay/)
- [Weavr Multi Overlay](https://apis.io/overlays/weavr/weavr-multi-overlay/)
- [Weavr Payment Run Overlay](https://apis.io/overlays/weavr/weavr-payment-run-overlay/)
- [Weavr Simulator Overlay](https://apis.io/overlays/weavr/weavr-simulator-overlay/)
- [Weavr Webhooks Overlay](https://apis.io/overlays/weavr/weavr-webhooks-overlay/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Weavr API Rules](https://apis.io/rules/weavr/weavr-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Weavr Authentication](https://apis.io/security/weavr/weavr-authentication/)
- [Weavr Domain Security](https://apis.io/security/weavr/weavr-domain-security/)
- [Weavr Trust Center](https://apis.io/security/weavr/weavr-trust-center/)

#### Plans and pricing (2)

Published plans, tiers and prices.

- [Weavr Plans Pricing](https://apis.io/plans/weavr/weavr-plans-pricing/)
- [Weavr Price Estimates](https://apis.io/plans/weavr/weavr-price-estimates/)

#### Rate limits (1)

Published request limits.

- [Weavr Rate Limits](https://apis.io/rate-limits/weavr/weavr-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.weavr.io/)
- [Documentation](https://docs.weavr.io/)
- [Getting started](https://docs.weavr.io/start/multi-welcome/)
- [API reference](https://api.weavr.io/products/multi/openapi)
- [Pricing](https://www.weavr.io/pricing/)
- [Sign up](https://portal.weavr.io/)
- [Support](https://support.weavr.io/)
- [Blog](https://www.weavr.io/blog/)
- [Compliance](https://security.weavr.io/)
- [Terms of service](https://www.weavr.io/terms-policies/)
- [Privacy policy](https://www.weavr.io/privacy-policy/)
- [GitHub](https://github.com/weavr-io)
- [Status](https://weavr.statuspage.io/)

## API Evangelist rating

**Kin Score 72.2** — exemplar · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 81.7 |
| Contract quality | 76.0 |
| Contract governance | 35.6 |
| Operational transparency | 73.7 |
| Developer ergonomics | 76.2 |
| Access clarity | 68.4 |

**Agent readiness 54.9** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | verified |
| Event Surface Described | yes |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | conformant |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 39.3** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/weavr/](https://apis.io/providers/weavr/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Weavr: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/weavr/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
