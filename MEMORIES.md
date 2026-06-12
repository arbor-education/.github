last_run_iso: 2026-06-12T21:02:27Z
posted_prs:
  - arbor-education/sis#34879
  - arbor-education/arbor-fe-library#3657
  - arbor-education/sis#34969
  - arbor-education/arbor-fe-library#3659
  - arbor-education/arbor-fe-library#3673
  - arbor-education/sis#34954
  - arbor-education/sis.communications-service#286
  - arbor-education/arborfinance.web#820
  - arbor-education/arborfinance.database#324
  - arbor-education/arborfinance.admin#56
  - arbor-education/arborfinance.background-worker#133
  - arbor-education/data.mis-warehouse#3344
  - arbor-education/bizops.upload-portal#939
borderline:
  - arbor-education/ai.claude.extensions#26: Internal Salesforce Claude extension. Useful to Sales Ops, but not a customer-visible release.
  - arbor-education/sis.communications-service#280: Security hardening for webhook handling. Customer-visible effect was unclear, and the follow-up status callback fix was posted.
  - arbor-education/data.mis-warehouse#3346: Ofsted source schema fix. Downstream customer impact was not explicit.
  - arbor-education/data-integration#3799: Private API Gateway signing for ADP integration. PR body reads as infrastructure-only.
  - arbor-education/sis.admin-ui#166: Admin UI error messaging. Appears to be internal admin tooling.
  - arbor-education/sis.vle-integrations#344: Removed IAM group access after SSO migration. Appears to be infrastructure access rather than customer-facing behaviour.
