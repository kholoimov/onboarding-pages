# SHiP Student Onboarding

This is a compact starting page for a student joining SHiP work at CERN. It is not a replacement for official CERN or SHiP documentation. Use it as a practical order of operations, then follow the linked source pages for the current rules, forms, and service details.

!!! note
    Your exact access depends on your institute, CERN registration category, supervisor, SHiP role, and safety requirements. When this page and an official CERN or SHiP page differ, follow the official page.

## 1. Understand where your work fits

Start by reading the public [SHiP website](https://ship.web.cern.ch/) and the [SHiP software documentation](https://shipsoft.github.io/Documentation/). You do not need to understand every detector or software component on day one, but you should be able to answer three questions:

- Which SHiP group or task are you joining?
- What is your first concrete deliverable?
- Which repository, dataset, meeting, or document is the source of truth for that deliverable?

For software work, also check the [ShipSoft GitHub organization](https://github.com/ShipSoft). Public documentation and public repositories are good entry points, while internal material may require CERN or collaboration access.

## 2. Sort out CERN registration

Before arrival, confirm your status with your supervisor, team leader, or institute contact. Registration controls many later steps: account creation, site access, insurance questions, safety training, computing eligibility, and protected resources.

Use the [CERN Users Office](https://usersoffice.web.cern.ch/) as the official starting point. In particular, check the [pre-arrival formalities](https://usersoffice.web.cern.ch/pre-arrival-formalities-and-information/) and [first-day onboarding](https://usersoffice.web.cern.ch/first-day-cern-and-onboarding) pages instead of copying their instructions into this guide.

Ask your supervisor:

- Which CERN category applies to you.
- Which documents your institute must provide.
- Whether you need a CERN access card.
- Whether you need safety courses, dosimetry, lab access, underground access, or radiation-area access.
- Who approves SHiP mailing-list, group, repository, and meeting access.

## 3. Activate the basic services

Once your CERN account is available, verify the services you will use regularly:

| Service | What to check |
| --- | --- |
| CERN Single Sign-On | You can sign in to CERN web services. |
| Users Portal | Your profile, affiliation, and service information look correct. |
| Groups and mailing lists | You have requested or received the memberships your task needs. |
| CERNBox | You can store and share ordinary documents. |
| GitLab or GitHub | You can access the repository used by your task. |
| Indico | You can open the meetings, agendas, and materials for your group. |
| Mattermost or email | You know where day-to-day discussion happens. |
| LXPLUS, EOS, CVMFS, batch | You know whether your task needs CERN computing resources. |

Official service pages:

- [CERN Authentication and Authorization docs](https://auth.docs.cern.ch/)
- [CERNBox docs](https://cernbox.docs.cern.ch/)
- [Indico docs](https://indico.docs.cern.ch/)
- [Mattermost at CERN docs](https://mattermost.docs.cern.ch/)
- [CERN Batch docs](https://batchdocs.web.cern.ch/)
- [CERN Service Portal](https://cern.service-now.com/service-portal)

## 4. Set up your first technical task

Do not begin by trying to configure every possible CERN and SHiP tool. Start from one reproducible task agreed with your supervisor.

Write down:

- The goal: for example, reproduce a simulation step, update documentation, test geometry configuration, make a validation plot, or prepare a short note.
- The repository or documentation page involved.
- The expected output: merge request, plot, log file, presentation, dataset, or written summary.
- The environment: laptop, LXPLUS, container, CVMFS release, or CI.
- The review path: supervisor, working group, repository maintainer, or SHiP contact.

For a first contribution, prefer something small and observable. Good first tasks include reproducing a documented command sequence, fixing outdated setup notes, adding a missing example, recording software versions, or improving a troubleshooting section.

## 5. Use this first-week checklist

- [ ] Confirm your CERN registration category and institute paperwork.
- [ ] Confirm your SHiP contact person and first task.
- [ ] Activate CERN account access and sign in successfully.
- [ ] Check your Users Portal profile.
- [ ] Request required groups, mailing lists, meetings, and repository access.
- [ ] Identify the relevant SHiP meeting on Indico.
- [ ] Find the canonical repository or documentation page for your work.
- [ ] Decide whether you should use a laptop, LXPLUS, container, CVMFS, or another environment.
- [ ] Reproduce one small documented command or workflow.
- [ ] Record the commands, software versions, input files, and output location.
- [ ] Agree on the first review or meeting date with your supervisor.

## 6. Know where to ask

Use the narrowest support path that fits the problem:

| Problem | First place to ask |
| --- | --- |
| Project scope, physics goal, review expectations | Your supervisor or SHiP working group |
| CERN registration, contracts, access cards, local life | [CERN Users Office](https://usersoffice.web.cern.ch/) |
| CERN service incident or access problem | [CERN Service Portal](https://cern.service-now.com/service-portal) |
| Repository permissions or merge-request review | Repository maintainers or your SHiP contact |
| Software setup, simulation, geometry, packaging | [SHiP software documentation](https://shipsoft.github.io/Documentation/) and the relevant maintainers |

## Minimal example workflow

Here is a simple first-week target that avoids overloading the onboarding process:

1. Read the public SHiP overview and the software documentation page closest to your task.
2. Confirm with your supervisor which repository and environment to use.
3. Clone or open only that repository.
4. Run one documented setup or test command.
5. Save a short note with the command, software version, result, and any error.
6. Bring that note to your first technical meeting.

This is usually more useful than collecting access to every service immediately. A small reproducible result gives your supervisor something concrete to review and exposes the next missing permission or setup step naturally.
