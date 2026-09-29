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

## Mandatory Mettelo Organisation Access

Every team delivery repository must be accessible to the **Mettelo GitHub organisation** for review, verification and quality assurance.

### Preferred method — create the repository inside Mettelo

Where available, teams should create their delivery repository **inside the Mettelo GitHub organisation**.

This is the preferred setup because Mettelo can manage organisation-level access, teams and repository permissions centrally.

The repository name must follow:

```text
MTL-DA-XXX-<team-name>
```

### If your repository is created outside Mettelo

GitHub does not normally allow a personal repository to invite an entire organisation as a collaborator.

If your team creates the repository under a personal GitHub account or another organisation, you must follow the Mettelo access method communicated for that cohort before submission. This may require:

- transferring the repository into the Mettelo organisation; or
- granting access to the specific Mettelo reviewer account/team designated by Mettelo.

### Submission rule

A repository is **not a complete Mettelo submission until the Mettelo organisation has verified access**.

Mettelo must be able to review:

- repository files and folders;
- commit history;
- branches;
- issues;
- pull requests;
- contribution evidence;
- final deliverables.

Access must remain active until project review and verification are complete.

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
