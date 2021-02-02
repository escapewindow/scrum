# Themes

Themes are large focus areas than span the Mozilla organization and are pertinent and addressable by the Taskcluster team.

The following are the current themes:

* [Support cost reduction](#cost-reduction)
* [Team Operations](#operations)
* [Security](#security)
* [Support user growth in Mozilla products](#user-growth)
* [Workflow](#workflow)

To update this information, edit `data/themes.yml` and run `generate.py`.

## cost-reduction
*Support cost reduction*

Build functionality that can be used to reduce costs for the projects we develop and operate.

*Associated Initiatives:*

* [Speed up update verify](./initiatives.md#speed-up-update-verify)
* [Automate QA's Firefox Update Tests](./initiatives.md#automate-firefox-update-tests)
* [Migrate Windows 10 from AWS to Azure](./initiatives.md#migrate-windows-10-to-azure)
* [Migrate from MDC2](./initiatives.md#migrate-from-mdc2)
* [Bitbar contract renewal](./initiatives.md#bitbar-contract-renewal)
* [Treeherder - Identify bad machines](./initiatives.md#treeherder-bad-machines)
* [Intermittents: quickly move repeatable failures to a quarantine job](./initiatives.md#quarantine-intermittents)
* [Work with l10n team to deprecate l10n repacks](./initiatives.md#deprecate-l10n-repacks)
* [Reduce wasted compute and idle time in our CI infrastructure](./initiatives.md#task-efficiencies)
* [archive.mozilla.org cleanup](./initiatives.md#archive-cleanup)
* [Right-size cloud instances](./initiatives.md#right-size-instances)
* [Test Scheduling improvements](./initiatives.md#test-scheduling)
* [Valuing Bug Sources](./initiatives.md#valuing-bug-sources)


## operations
*Team Operations*

Improve our operational efficiency, including
 * Releaseduty
 * General team operations (secret handling, access control, cross-training, etc.)

*Associated Initiatives:*

* [Keep the Lights On](./initiatives.md#ktlo)
* [Automate Mac Signer Maintenance](./initiatives.md#automate-mac-signer-maintenance)
* [Modernizing OS/Hardware for CI tests](./initiatives.md#modernizing-test-platforms)
* [Productionize or EOL ActiveData](./initiatives.md#activedata-eol)
* [Finish Python 3 migration](./initiatives.md#python-3-migration)
* [Improve mobile release and CI task robustness](./initiatives.md#mobile-task-robustness)
* [Migrate Windows 10 from AWS to Azure](./initiatives.md#migrate-windows-10-to-azure)
* [Migrate from MDC2](./initiatives.md#migrate-from-mdc2)
* [Bitbar contract renewal](./initiatives.md#bitbar-contract-renewal)
* [Add support for Linux ARM64 in the CI](./initiatives.md#linux-arm64-ci)
* [Treeherder - move to CloudOps dockerflow](./initiatives.md#treeherder-cloudops)
* [EOL Firefox Lite](./initiatives.md#firefox-lite-eol)


## security
*Security*

Improve our operational security, including
 * Chain of Trust
 * Adding signoffs and monitoring
 * Reducing manual interaction with sensitive systems to zero
 * Allowing for cert rotations

*Associated Initiatives:*

* [Implement Android v3 signatures and sign Fenix with them](./initiatives.md#fenix-v3-signatures)
* [Automate shipping system addons through Balrog](./initiatives.md#system-addons-balrog)
* [Automate Mac Signer Maintenance](./initiatives.md#automate-mac-signer-maintenance)
* [Finish Python 3 migration](./initiatives.md#python-3-migration)
* [Password Rotations and Sharing](./initiatives.md#password-rotations)
* [Develop Releng for Mozilla Proposal](./initiatives.md#releng-for-mozilla-proposal)
* [Make Firefox Snap the default format on Ubuntu](./initiatives.md#firefox-snap-default)
* [Binary Transparency](./initiatives.md#binary-transparency)
* [Standardize Python Dependency Pinning in Gecko](./initiatives.md#standardize-gecko-python)
* [Support Mozilla China Fenix](./initiatives.md#mozilla-china-fenix)
* [Support tests in external contributor PRs in Android-Components](./initiatives.md#android-components-contributor-prs)
* [Support Focus releases through Shipit](./initiatives.md#focus-shipit)


## user-growth
*Support user growth in Mozilla products*

Build functionality to ship features, products, and fixes that increase Mozilla product user growth and retention.

*Associated Initiatives:*

* [Integrate Geckoview and Android-Components in the Fenix pipeline on Shipit](./initiatives.md#geckoview-android-components-shipit)
* [Apple Silicon Support](./initiatives.md#apple-silicon-support)
* [Develop Releng for Mozilla Proposal](./initiatives.md#releng-for-mozilla-proposal)
* [Make Firefox Snap the default format on Ubuntu](./initiatives.md#firefox-snap-default)
* [Work with l10n team to deprecate l10n repacks](./initiatives.md#deprecate-l10n-repacks)


## workflow
*Workflow*

Improvements in Mozilla CI and release pipelines and tooling workflow.

*Associated Initiatives:*

* [Keep the Lights On](./initiatives.md#ktlo)
* [Integrate Geckoview and Android-Components in the Fenix pipeline on Shipit](./initiatives.md#geckoview-android-components-shipit)
* [Implement Android v3 signatures and sign Fenix with them](./initiatives.md#fenix-v3-signatures)
* [Automate shipping system addons through Balrog](./initiatives.md#system-addons-balrog)
* [Work with the Addons team to formalize the Addons Pipeline](./initiatives.md#formalize-addons-pipeline)
* [Apple Silicon Support](./initiatives.md#apple-silicon-support)
* [Modernizing OS/Hardware for CI tests](./initiatives.md#modernizing-test-platforms)
* [Push Health UX Rework](./initiatives.md#push-health-ux-rework)
* [Drive desktop Firefox Nightly automation through shipit](./initiatives.md#firefox-nightly-shipit)
* [Speed up update verify](./initiatives.md#speed-up-update-verify)
* [Developer Productivity](./initiatives.md#developer-productivity)
* [Treeherder: Improve login experience](./initiatives.md#treeherder-login-experience)
* [Treeherder: Maintenance/Backlog](./initiatives.md#treeherder-maintenance)
* [Automate QA's Firefox Update Tests](./initiatives.md#automate-firefox-update-tests)
* [Develop Releng for Mozilla Proposal](./initiatives.md#releng-for-mozilla-proposal)
* [Make Firefox Snap the default format on Ubuntu](./initiatives.md#firefox-snap-default)
* [Fully automate mergeduty](./initiatives.md#automate-mergeduty)
* [Standardize Python Dependency Pinning in Gecko](./initiatives.md#standardize-gecko-python)
* [Support Mozilla China Fenix](./initiatives.md#mozilla-china-fenix)
* [Support tests in external contributor PRs in Android-Components](./initiatives.md#android-components-contributor-prs)
* [Improve mobile release and CI task robustness](./initiatives.md#mobile-task-robustness)
* [Support Focus releases through Shipit](./initiatives.md#focus-shipit)
* [Add support for Linux ARM64 in the CI](./initiatives.md#linux-arm64-ci)
* [Treeherder - move to CloudOps dockerflow](./initiatives.md#treeherder-cloudops)
* [TreeHerder Failure Classification](./initiatives.md#treeherder-failure-classification)
* [Treeherder - sheriff improvement fixes/requests](./initiatives.md#treeherder-sheriff-requests)
* [Treeherder - Identify bad machines](./initiatives.md#treeherder-bad-machines)
* [Intermittents: quickly move repeatable failures to a quarantine job](./initiatives.md#quarantine-intermittents)
* [Work with l10n team to deprecate l10n repacks](./initiatives.md#deprecate-l10n-repacks)
* [Test Scheduling improvements](./initiatives.md#test-scheduling)
* [reduce taskgraph learning curve](./initiatives.md#taskgraph-learning-curve)
* [Team view of riskiness of pushes](./initiatives.md#push-riskiness)
* [Implement a dark mode theme in Treeherder](./initiatives.md#treeherder-dark-mode)
* [Automate Fenix Betas](./initiatives.md#automate-fenix-betas)

