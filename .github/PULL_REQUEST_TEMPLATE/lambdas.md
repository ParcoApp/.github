## What does this PR do? 🎯

> Clear and direct summary of the **what** and the **why**. Give reviewers enough context to understand the Lambda's purpose and the reason for the change.

**Related issue:** Closes #

---

## Lambda information

* **Lambda:** `function-name`
* **Runtime:** 
* **Trigger:** 
* **AWS Account / Environment:** 
* **Related services:** 

---

## Type of change

* [ ] 🐛 Bug fix
* [ ] ✨ New feature
* [ ] ♻️ Refactor (no functional change)
* [ ] 💥 Breaking change
* [ ] 🔒 Security
* [ ] ⚡ Performance / cost optimization
* [ ] 📦 Dependencies / runtime
* [ ] 🏗️ Infrastructure / IaC
* [ ] 📊 Observability / logging
* [ ] 📝 Documentation / configuration

---

## Key changes

> Describe the relevant changes and what reviewers should pay attention to. Skip the obvious.

* ## **Business logic:**
* ## **AWS resources / configuration:**
* ## **Non-obvious design decisions:**

---

## Event / trigger changes

> Describe changes to the Lambda's event source, event schema, filters, retries, batching, or invocation behavior.

* **Trigger:** None / describe here
* **Event schema changed:** No / Yes
* **Retry behavior changed:** No / Yes
* **Batch size / concurrency changed:** No / Yes

**Event example:**

```json
{
}
```

---

## IAM / permissions 🔐

> Document any changes to the Lambda execution role or permissions. Follow least privilege.

* [ ] No IAM changes
* [ ] New AWS permissions added
* [ ] Existing AWS permissions modified
* [ ] Existing AWS permissions removed

**Permissions added/changed:**

* `service:Action` → `resource`

**Reason:**

---

## Environment variables / secrets

* [ ] No environment variable changes
* [ ] New environment variables
* [ ] Existing environment variables modified
* [ ] Secrets / parameters changed

> **Never add credentials, tokens, passwords, or secret values to the PR.**

---

## Configuration / resources

> Document changes that can affect Lambda execution, reliability, or cost.

* **Memory:** unchanged / `XXX MB`
* **Timeout:** unchanged / `XX sec`
* **Ephemeral storage:** unchanged / `XXX MB`
* **Reserved concurrency:** unchanged / `XXX`
* **Provisioned concurrency:** unchanged / `XXX`
* **Architecture:** 
---



## Observability 📊

* [ ] Logs added/updated where necessary
* [ ] CloudWatch metrics considered
* [ ] Alarms updated/added, if applicable
* [ ] Tracing updated, if applicable
* [ ] No sensitive information is logged

**Important logs / metrics / alarms:**

---

## How to test ✅

> Provide concrete steps to verify the Lambda. Include commands, event payloads, test data, or relevant AWS resources.

1.
2.
3.

**Test event:**

```json
{
}
```

**Special setup / environment variables needed:** None / describe here

---


## Infrastructure / deployment

* [ ] No infrastructure changes
* [ ] Terraform
* [ ] AWS CDK
* [ ] Serverless Framework
* [ ] CloudFormation
* [ ] Other:

**Resources created/modified/removed:**

*
*

---

<details>
<summary>📸 Screenshots / logs / CloudWatch output</summary>

*Add screenshots, relevant logs, traces, metrics, or other evidence if useful. Never include secrets or sensitive information.*

</details>

---

## Checklist

* [ ] Code follows the project's conventions
* [ ] I performed a self-review before opening this PR
* [ ] Existing tests pass
* [ ] I added or updated tests where necessary
* [ ] Lambda timeout and memory settings have been considered
* [ ] IAM permissions follow least-privilege principles
* [ ] No credentials, secrets, tokens, or sensitive data are committed
* [ ] No sensitive information is written to logs
* [ ] Error handling and retry behavior have been considered
* [ ] Idempotency has been considered where applicable
* [ ] Environment variables / secrets are documented without exposing values
* [ ] Infrastructure changes have been reviewed
* [ ] Performance and AWS cost impact have been considered
* [ ] Monitoring / alarms are updated if necessary
* [ ] Documentation has been updated if applicable
