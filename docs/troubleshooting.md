# Troubleshooting

## Issue:
Resource does not exist

Error:

Resource 'dotnet-webapp' doesn't exist

Cause:

Service Connection points to wrong subscription.

Solution:

Delete existing Service Connection.

Create a new connection.

Verify subscription.

---

## Issue:
Pipeline waiting indefinitely

Cause:

Environment approval enabled.

Solution:

Remove:

environment: production

---

## Issue:
No hosted agent available

Cause:

No parallel jobs.

Solution:

Organization Settings

→ Parallel Jobs

Enable free hosted agents

---

## Issue:
Deployment failed

Cause:

Wrong App Service Name

Solution:

Check exact App Service name from Azure Portal
