# Brian Lund Larsen

  Open to freelance or the right role in Paris or Nice.

## What I work on

- CI/CD, release engineering and developer platforms
- AWS infrastructure, Kubernetes and infrastructure as code
- Developer experience, internal tools and engineering automation
- Observability, operational readiness and security guardrails
- Python, PowerShell, shell scripting and pragmatic systems tooling

## Selected projects

### [Dreaming Logger](https://github.com/brianlund/ds-logger)

A maintained Chrome extension for logging external language-learning activity.
It is distributed through the Chrome Web Store and includes automated tests,
linting, CI validation and release packaging.  

### [AWS Cost Summary](https://github.com/brianlund/aws_cost_summary)

A Python tool for monitoring cost development across multiple AWS accounts. It
identifies significant service-level increases and longer-term trends, providing
a practical starting point for recurring FinOps reviews and automated reporting.
Note that AWS Cost Explorer and Budget reports now supports most of the features. 


### [AWS CodeDeploy ELB for PowerShell](https://github.com/brianlund/codedeploy-elb-powershell)

A PowerShell implementation of AWS CodeDeploy load-balancer lifecycle hooks for
Windows deployments. It supports Classic ELB and ALB target groups, allowing
instances to be removed from traffic and registered again around deployments.

The implementation was developed for production use and shared in
 [AWS Samples issue #44](https://github.com/aws-samples/aws-codedeploy-samples/issues/44#issuecomment-268464191).

This is a historical project and has not been validated against current AWS APIs
or PowerShell versions.

## Selected open-source contributions

- **[lua-resty-auto-ssl](https://github.com/auto-ssl/lua-resty-auto-ssl)** -
    Improved certificate-renewal scalability by persisting expiry metadata and
    avoiding premature ACME renewal attempts. The work was tested
    and run in production with more than houndred and twenty thousands of domains.
    [Merged PR #111](https://github.com/auto-ssl/lua-resty-auto-ssl/pull/111)

- **[JetBrains TeamCity Helm Plugin](https://github.com/JetBrains/teamcity-helm-plugin)** -
    Fixed Helm upgrade argument parsing so multiple command-line flags are handled
    correctly in TeamCity build workflows.
    [Merged PR #40](https://github.com/JetBrains/teamcity-helm-plugin/pull/40)

- **[AWS CodeDeploy Samples](https://github.com/aws-samples/aws-codedeploy-samples)** -
    Contributed a merged correction to ELBv2 deregistration diagnostics.
    [Merged PR #63](https://github.com/aws-samples/aws-codedeploy-samples/pull/63)

## Elsewhere and contact

- [cze.dk](https://cze.dk)
