# Initiatives

An _initiative_ is a collection of one or more milestones that, taken together, address one or more themes. Initiatives map to major projects that the Taskcluster team would like to accomplish, and can be either new functionality or substantial reworks of existing functionality. Depending on the project area, an initiative can be a thin wrapper around a single milestone if that milestone is high value and self-contained.

The following are the current initiatives:

* [Keep the Lights On](#ktlo)
* [Integrate Geckoview and Android-Components in the Fenix pipeline on Shipit](#geckoview-android-components-shipit)
* [Implement Android v3 signatures and sign Fenix with them](#fenix-v3-signatures)
* [Automate shipping system addons through Balrog](#system-addons-balrog)
* [Work with the Addons team to formalize the Addons Pipeline](#formalize-addons-pipeline)
* [Automate Mac Signer Maintenance](#automate-mac-signer-maintenance)
* [Apple Silicon Support](#apple-silicon-support)
* [Modernizing OS/Hardware for CI tests](#modernizing-test-platforms)
* [Push Health UX Rework](#push-health-ux-rework)
* [Drive desktop Firefox Nightly automation through shipit](#firefox-nightly-shipit)
* [Speed up update verify](#speed-up-update-verify)
* [Developer Productivity](#developer-productivity)
* [Productionize or EOL ActiveData](#activedata-eol)
* [Treeherder: Improve login experience](#treeherder-login-experience)
* [Treeherder: Maintenance/Backlog](#treeherder-maintenance)
* [Finish Python 3 migration](#python-3-migration)
* [Automate QA's Firefox Update Tests](#automate-firefox-update-tests)
* [Password Rotations and Sharing](#password-rotations)
* [Develop Releng for Mozilla Proposal](#releng-for-mozilla-proposal)
* [Make Firefox Snap the default format on Ubuntu](#firefox-snap-default)
* [Fully automate mergeduty](#automate-mergeduty)
* [Test Scheduling improvements](#test-scheduling)
* [Reduce wasted compute and idle time in our CI infrastructure](#task-efficiencies)
* [Right-size cloud instances](#right-size-instances)
* [Specific bug fixes and feature requests for sheriffs](#treeherder-sheriff-requests)
* [Push Health MozCI integration](#push-health-mozci)
* [Test distribution and scheduling optimizations](#test-distribution-optimization)
* [archive.mozilla.org cleanup](#archive-cleanup)
* [Improve iOS build, release, and CI pipeline](#ios-needs)
* [Support MozillaVPN Releases](#mozillavpn)

To update this information, edit `data/initiatives.yml` and run `generate.py`.

## ktlo
*Keep the Lights On*

Ensure all RelEng systems are working in order to keep our products pipeline running.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Aktlo)

*Addresses Themes:*

* [Workflow](./themes.md#workflow)
* [Team Operations](./themes.md#operations)


## geckoview-android-components-shipit
*Integrate Geckoview and Android-Components in the Fenix pipeline on Shipit*

Automate GeckoView and Android-Components releases like Fenix, reducing cross-team interactions and friction.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Ageckoview-android-components-shipit)

*Addresses Themes:*

* [Support user growth in Mozilla products](./themes.md#user-growth)
* [Workflow](./themes.md#workflow)


## fenix-v3-signatures
*Implement Android v3 signatures and sign Fenix with them*

We should sign Fenix with both v1 and v3 signatures so that we support legacy versions of Android while covering ourselves in case of a key leakage.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Afenix-v3-signatures)

*Addresses Themes:*

* [Workflow](./themes.md#workflow)
* [Security](./themes.md#security)


## system-addons-balrog
*Automate shipping system addons through Balrog*

Document, automate, and run periodic tests to make sure we are ready to ship system addons to all versions of Firefox through automation.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Asystem-addons-balrog)

*Addresses Themes:*

* [Workflow](./themes.md#workflow)
* [Security](./themes.md#security)


## formalize-addons-pipeline
*Work with the Addons team to formalize the Addons Pipeline*

Clarify and streamline the rules and process of the addons pipeline.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Aformalize-addons-pipeline)

*Addresses Theme:*

* [Workflow](./themes.md#workflow)


## automate-mac-signer-maintenance
*Automate Mac Signer Maintenance*

End goal of rolling out changes to the mac signers via ronin-puppet commit, reducing ssh and manual maintenance to zero.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Aautomate-mac-signer-maintenance)

*Addresses Themes:*

* [Team Operations](./themes.md#operations)
* [Security](./themes.md#security)


## apple-silicon-support
*Apple Silicon Support*

Determine what is needed to support Apple Silicon build signing and testing, and the timeframe it’s needed in.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Aapple-silicon-support)

*Addresses Themes:*

* [Support user growth in Mozilla products](./themes.md#user-growth)
* [Workflow](./themes.md#workflow)


## modernizing-test-platforms
*Modernizing OS/Hardware for CI tests*

Keep Firefox CI OS+hardware/cloud environments relevant and investigate ways to reduce pain points.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Amodernizing-test-platforms)

*Addresses Themes:*

* [Team Operations](./themes.md#operations)
* [Workflow](./themes.md#workflow)


## push-health-ux-rework
*Push Health UX Rework*

Give developers a simple view of what failures seen in CI need their attention.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Apush-health-ux-rework)

*Addresses Theme:*

* [Workflow](./themes.md#workflow)


## firefox-nightly-shipit
*Drive desktop Firefox Nightly automation through shipit*

Unify nightly and release automation in Gecko.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Afirefox-nightly-shipit)

*Addresses Theme:*

* [Workflow](./themes.md#workflow)


## speed-up-update-verify
*Speed up update verify*

Speed up update verify.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Aspeed-up-update-verify)

*Addresses Themes:*

* [Support cost reduction](./themes.md#cost-reduction)
* [Workflow](./themes.md#workflow)


## developer-productivity
*Developer Productivity*

Improve developer productivity by addressing bugs developers file/mention and being proactive on workflows

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Adeveloper-productivity)

*Addresses Theme:*

* [Workflow](./themes.md#workflow)


## activedata-eol
*Productionize or EOL ActiveData*

Productionize or EOL ActiveData.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Aactivedata-eol)

*Addresses Theme:*

* [Team Operations](./themes.md#operations)


## treeherder-login-experience
*Treeherder: Improve login experience*

Minimize papercuts in Treeherder by increasing login TTL.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Atreeherder-login-experience)

*Addresses Theme:*

* [Workflow](./themes.md#workflow)


## treeherder-maintenance
*Treeherder: Maintenance/Backlog*

Treeherder maintenance and backlog

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Atreeherder-maintenance)

*Addresses Theme:*

* [Workflow](./themes.md#workflow)


## python-3-migration
*Finish Python 3 migration*

Python 2 has been EOLed since the end of 2019. Pip dropped support for Python 2.7 in Jan 2021.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Apython-3-migration)

*Addresses Themes:*

* [Team Operations](./themes.md#operations)
* [Security](./themes.md#security)


## automate-firefox-update-tests
*Automate QA's Firefox Update Tests*

QA runs update tests against a matrix of Firefox versions. They want us to run these tests in automation.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Aautomate-firefox-update-tests)

*Addresses Themes:*

* [Support cost reduction](./themes.md#cost-reduction)
* [Workflow](./themes.md#workflow)


## password-rotations
*Password Rotations and Sharing*

Rotate secrets and populate the new secrets store.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Apassword-rotations)

*Addresses Theme:*

* [Security](./themes.md#security)


## releng-for-mozilla-proposal
*Develop Releng for Mozilla Proposal*

Create a proposal to also help non-Gecko teams at Mozilla with their release pipelines.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Areleng-for-mozilla-proposal)

*Addresses Themes:*

* [Workflow](./themes.md#workflow)
* [Security](./themes.md#security)
* [Support user growth in Mozilla products](./themes.md#user-growth)


## firefox-snap-default
*Make Firefox Snap the default format on Ubuntu*

Make Snap the default format on Ubuntu. This will make a Mozilla build the default, rather than a distribution rebuild. There may be contracts involved.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Afirefox-snap-default)

*Addresses Themes:*

* [Workflow](./themes.md#workflow)
* [Security](./themes.md#security)
* [Support user growth in Mozilla products](./themes.md#user-growth)


## automate-mergeduty
*Fully automate mergeduty*

Fully automate the rest of mergeduty.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Aautomate-mergeduty)

*Addresses Theme:*

* [Workflow](./themes.md#workflow)


## test-scheduling
*Test Scheduling improvements*

Use smarter scheduling algorithms to reduce the number of tasks we run in CI and give developers greater confidence in their try pushes.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Atest-scheduling)

*Addresses Themes:*

* [Support cost reduction](./themes.md#cost-reduction)
* [Workflow](./themes.md#workflow)


## task-efficiencies
*Reduce wasted compute and idle time in our CI infrastructure*

Reduce test frequencies, wasted time in tasks, and idle time in our CI infrastructure.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Atask-efficiencies)

*Addresses Theme:*

* [Support cost reduction](./themes.md#cost-reduction)


## right-size-instances
*Right-size cloud instances*

Create system to identify tasks running on oversized instances by collecting resource usage data into our data analytics platform (BigQuery)

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Aright-size-instances)

*Addresses Theme:*

* [Support cost reduction](./themes.md#cost-reduction)


## treeherder-sheriff-requests
*Specific bug fixes and feature requests for sheriffs*

Improving workflows for sheriffs make them more efficient and accurate. It also makes their lives easier.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Atreeherder-sheriff-requests)

*Addresses Theme:*

* [Workflow](./themes.md#workflow)


## push-health-mozci
*Push Health MozCI integration*

Improve Push Health regression detection accuracy by integrating MozCI

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Apush-health-mozci)

*Addresses Theme:*

* [Workflow](./themes.md#workflow)


## test-distribution-optimization
*Test distribution and scheduling optimizations*

Reduce overhead related to getting test files onto the test workers; stop scheduling builds for test-only changes.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Atest-distribution-optimization)

*Addresses Themes:*

* [Support cost reduction](./themes.md#cost-reduction)
* [Workflow](./themes.md#workflow)


## archive-cleanup
*archive.mozilla.org cleanup*

Get rid of unnecessary files on archive.mozilla.org and enact new retention policies

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Aarchive-cleanup)

*Addresses Theme:*

* [Support cost reduction](./themes.md#cost-reduction)


## ios-needs
*Improve iOS build, release, and CI pipeline*

iOS builds & releases are more important than ever, and ensuring developers are unblocked and that releases can ship on time is very important.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Aios-needs)

*Addresses Theme:*

* [Support user growth in Mozilla products](./themes.md#user-growth)


## mozillavpn
*Support MozillaVPN Releases*

MozillaVPN is a new product that is quickly gaining traction. We need make sure that they can ship, and eventually, have proper CI/Release automation.

[*Associated Epics*](https://github.com/taskcluster/scrum/issues?q=is%3Aissue+is%3Aopen+label%3Ainitiative%3Amozillavpn)

*Addresses Theme:*

* [Support user growth in Mozilla products](./themes.md#user-growth)

