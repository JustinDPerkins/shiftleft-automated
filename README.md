# shiftleft-automated

Upwind GitHub Automated Scanning — do not delete.

Required Actions secrets on **this repo**:

| Secret | Source |
|--------|--------|
| `UPWIND_CLIENT_ID` | Upwind Console |
| `UPWIND_CLIENT_SECRET` | Upwind Console |
| `AWS_ECR_PULL_ROLE_ARN` | `terraform output -raw github_actions_ecr_pull_role_arn` from JaysSurfShop |

The Upwind GitHub App dispatches scans here after JaysSurfShop pushes images to ECR.