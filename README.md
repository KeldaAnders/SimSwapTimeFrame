<a href="https://github.com/camaraproject/SimSwapTimeFrame/commits/" title="Last Commit"><img src="https://img.shields.io/github/last-commit/camaraproject/SimSwapTimeFrame?style=plastic"></a>
<a href="https://github.com/camaraproject/SimSwapTimeFrame/issues" title="Open Issues"><img src="https://img.shields.io/github/issues/camaraproject/SimSwapTimeFrame?style=plastic"></a>
<a href="https://github.com/camaraproject/SimSwapTimeFrame/pulls" title="Open Pull Requests"><img src="https://img.shields.io/github/issues-pr/camaraproject/SimSwapTimeFrame?style=plastic"></a>
<a href="https://github.com/camaraproject/SimSwapTimeFrame/graphs/contributors" title="Contributors"><img src="https://img.shields.io/github/contributors/camaraproject/SimSwapTimeFrame?style=plastic"></a>
<a href="https://github.com/camaraproject/SimSwapTimeFrame" title="Repo Size"><img src="https://img.shields.io/github/repo-size/camaraproject/SimSwapTimeFrame?style=plastic"></a>
<a href="https://github.com/camaraproject/SimSwapTimeFrame/blob/main/LICENSE" title="License"><img src="https://img.shields.io/badge/License-Apache%202.0-green.svg?style=plastic"></a>
<a href="https://github.com/camaraproject/SimSwapTimeFrame/releases/latest" title="Latest Release"><img src="https://img.shields.io/github/release/camaraproject/SimSwapTimeFrame?style=plastic"></a>
<a href="https://github.com/camaraproject/Governance/blob/main/ProjectStructureAndRoles.md" title="Sandbox API Repository"><img src="https://img.shields.io/badge/Sandbox%20API%20Repository-yellow?style=plastic"></a>

# SimSwapTimeFrame

Sandbox API Repository to describe, develop, document, and test the SimSwapTimeFrame Service API(s) within the Sub Project [Number Insights](https://lf-camaraproject.atlassian.net/wiki/x/BYEpBQ).

* API Repository [wiki page](https://lf-camaraproject.atlassian.net/wiki/x/A4ClS)

## Scope

* Service API(s) "SimSwapTimeFrame" (see [APIBacklog.md](https://github.com/camaraproject/APIBacklog/blob/main/documentation/APIbacklog.md))
* The API(s) provide(s) the API consumer with the ability to:
  * retrieve the SIM swap age band for a phone number: a standardized time band indicating how recently the most recent SIM swap occurred, or that none has occurred, to support fraud and risk decisions.
* The age band is returned in a single response, with bounded disclosure compared with an exact SIM swap date. Consumers apply their own thresholds and step-up logic outside the API contract.
* The API continues the SIM swap age band work started in [SimSwap#253](https://github.com/camaraproject/SimSwap/issues/253) and developed in [SimSwap#273](https://github.com/camaraproject/SimSwap/pull/273). The TSC agreed on 2026-09-17 to move it into a separate API repository ([TSC minutes](https://lf-camaraproject.atlassian.net/wiki/spaces/CAM/pages/1131708461/2026-09-17+TSC+Minutes)); it was removed from SimSwap by [SimSwap#292](https://github.com/camaraproject/SimSwap/pull/292) before the r4.1 release. The existing SimSwap APIs remain unchanged.
* Describe, develop, document, and test the API(s)
* Started: October 2026

<!-- CAMARA:RELEASE-INFO:START -->
<!-- The following section is automatically maintained by the CAMARA project-administration tooling: https://github.com/camaraproject/project-administration -->

## Release Information

The repository has no (pre)releases yet, work in progress is within the main branch.

<!-- CAMARA:RELEASE-INFO:END -->

## Contributing

* Meetings are held virtually as part of the Number Insights Sub Project meeting
  * Schedule: Every 4 weeks, Thursday, 7:30 AM UTC (8:30 CET/9:30 CEST)
  * [Registration / Join](https://zoom-lfx.platform.linuxfoundation.org/meeting/94893248838?password=05b2197d-309e-41ef-aadf-639f71ef7f38)
  * Minutes: Access [meeting minutes](https://lf-camaraproject.atlassian.net/wiki/x/hDze)
* Mailing List
  * Subscribe / Unsubscribe to the mailing list <https://lists.camaraproject.org/g/sp-number-insights>.
  * A message to the community of this Sub Project can be sent using <sp-number-insights@lists.camaraproject.org>.
