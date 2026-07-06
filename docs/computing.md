# Computing

## Core services

Most students working with SHiP will encounter these CERN services:

| Service | Use |
| --- | --- |
| CERN Single Sign-On | Login to CERN web applications and protected resources. |
| Users Portal | Manage account-related information and service subscriptions. |
| Group Management System | Groups, access control, and mailing-list-style membership. |
| CERNBox | Cloud storage, sharing, synchronization, and collaborative work. |
| GitLab | Code hosting, issues, merge requests, CI, and private project access. |
| Indico | Meetings, agendas, minutes, materials, room booking, and event records. |
| Mattermost | Professional chat for the CERN community and external collaborators. |
| LXPLUS | Interactive Linux login environment for CERN computing work, where eligible. |
| HTCondor batch | High-throughput computing for jobs at CERN. |

## CERNBox

CERNBox provides cloud data storage to CERN users. It supports storing, sharing, synchronizing across devices, and browser or file-explorer access. It is useful for notes, drafts, plots, shared documents, and lightweight collaboration.

Use experiment storage, EOS, CVMFS, or approved analysis storage for data and software artifacts when your group requires it.

## GitLab

Use CERN GitLab or the relevant GitHub organization depending on the project. SHiP public software repositories are under [ShipSoft](https://github.com/ShipSoft), while CERN-internal work may live on `gitlab.cern.ch`.

Ask your supervisor where the canonical repository is before forking or creating a new project.

## Meetings

Indico is CERN's standard tool for meetings and events. It supports meetings, lectures, conferences, timetable material, minutes, and room booking. SHiP meetings linked from the SHiP public site are a good entry point.

## Chat and support

Mattermost at CERN provides professional chat for colleagues and external collaborators. Access to some teams and support channels depends on having a full CERN account and the correct group membership.

For service problems, open a ticket through the CERN Service Portal rather than relying only on chat.

## Batch and analysis computing

The CERN Batch Service is based on HTCondor and provides high-throughput computing for experiments and users. It is the right place for many non-interactive workloads once your environment, input data, and output handling are defined.

For a first SHiP computing task, clarify:

- Which software stack to use.
- Whether to work on LXPLUS, a local machine, or a container.
- Where input data lives.
- Where output should be written.
- Whether your jobs should use local batch, grid resources, or another service.
