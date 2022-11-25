
# Renovatebot - An automated way to handle software dependency upgrades

As you, the application, grow older, you might notice that some external dependencies (hair) are starting to show gaps. You feel vulnerable.
Our application "combs" through your dependencies. It can't address the underlying rot. For that you need a professional. But it tries its best to cover things up.

On the other hand, the software dependencies is cause of concern due to security issues like the recent Log4Shell and an expiring SSL Certificate. But there are also other aspects like bugs caused by your dependencies.


## Acknowledgements

 Team would like to thank Eoin Byrne for pitching this idea. The completion of the project would not have been possible without his insights.

## Authors

- Aaron Pope
- Jack Meade
- Matej Saksida
- Pawan Sharma
- Robert Metcalfe



## Execute renovatebot


## Renovate Dashboard

https://app.renovatebot.com/dashboard#github/apope8/ROW_16


## Renovate configurations

This URL describes all the configuration options you may use in a Renovate configuration file. Any config you define applies to the whole repository
https://docs.renovatebot.com/configuration-options/

Some of them have been used in the project:

- matchPackagePatterns - This will match the package patterns one intend to update
- matchUpdateTypes - Only update major and minor dependency, if published. Allowed values are major, minor, patch, pin, pinDigest, digest, lockFileMaintenance, rollback, bump
- dependencyDashboardApproval - This feature allows you to use Renovate's Dependency Dashboard to force approval of updates before they are created.
- automerge - Prevent to automerge the PR, if required
- enabledManagers - A list of package managers to enable. For instance, maven, npm etc
- prHourlyLimit - Set the PR limit per hour for dependency upgrade
- branchPrefixOld - Prefix to use for with previous PR created.




## Appendix

List of URL(S):
- https://docs.renovatebot.com/
- https://docs.renovatebot.com/getting-started/installing-onboarding/
- https://docs.renovatebot.com/configuration-options/

