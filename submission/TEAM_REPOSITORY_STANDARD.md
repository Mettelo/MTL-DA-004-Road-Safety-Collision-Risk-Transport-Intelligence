# Mandatory Team Repository Standard

Each approved team must create its own GitHub repository.

## Repository Name

```text
MTL-DA-004-<team-name>
```

Example:

```text
MTL-DA-004-safer-streets-lab
```

## Visibility

The repository may remain private during delivery.

If private, add the designated Mettelo reviewer GitHub account before final submission.

## Mandatory Mettelo Repository Access

Every team delivery repository must grant Mettelo access before the submission is considered complete.

### Exact GitHub account to invite

Invite this GitHub username:

```text
OlaoluwajohnsonT
```

### How to add Mettelo

If your repository is owned by a team member or another organisation:

1. Open your team repository on GitHub.
2. Select **Settings**.
3. Open **Collaborators** or **Collaborators and teams**.
4. Select **Add people**.
5. Search for the username **OlaoluwajohnsonT**.
6. Select the matching GitHub account.
7. Send the invitation.
8. Confirm the invitation has been sent successfully.

If the repository is already hosted inside the Mettelo GitHub organisation, do not remove existing Mettelo access.

### Required access before submission

Mettelo must be able to review:

- repository files and folders;
- commit history;
- branches;
- issues;
- pull requests;
- contribution evidence;
- final deliverables.

### Submission rule

A repository is **not a complete Mettelo submission until access for `OlaoluwajohnsonT` has been granted and verified**.

The Team Lead is responsible for confirming access and must keep it active until the review and verification process is complete.

## Mandatory Structure

```text
MTL-DA-004-<team-name>/
│
├── README.md
├── CONTRIBUTIONS.md
├── requirements.txt
├── .gitignore
│
├── data/
│   ├── README.md
│   ├── raw/
│   └── processed/
│
├── docs/
│   ├── 01-discovery/
│   ├── 02-data-model/
│   ├── 03-kpi-catalogue/
│   ├── 04-geographic-analysis/
│   ├── 05-vulnerable-road-users/
│   ├── 06-severity-analysis/
│   └── 07-technical-handover/
│
├── sql/
├── src/
├── notebooks/
├── analysis/
├── dashboard/
│   └── README.md
│
├── deliverables/
│   ├── executive-briefing/
│   └── presentation/
│
└── submission/
    └── FINAL_SUBMISSION.md
```

## README Requirements

The root README must contain:

- project ID/title;
- team name;
- members/roles;
- business-problem summary;
- solution overview;
- data acquisition instructions;
- architecture/data-flow summary;
- reproduction steps;
- dashboard link;
- deliverable links;
- limitations;
- source attribution.

## Git Workflow

Minimum expectations:

- issues for meaningful work;
- descriptive commits;
- branches for substantial changes;
- pull requests for material merges;
- peer review where practical;
- visible contribution from multiple team members.

Do not upload the entire project in one final commit.

## Data Rules

Do not modify raw source data.

If raw files are too large or unsuitable for Git, use `.gitignore` and document acquisition steps.

## Reproducibility

A technically competent reviewer must be able to reconstruct the analytical workflow from the repository instructions.

## Contribution Evidence

`CONTRIBUTIONS.md` must record actual individual contributions.

Commit count alone is not sufficient proof of contribution.
