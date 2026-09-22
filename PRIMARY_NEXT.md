# Primary Next scaffold

Primary Next is rooted at the current Primary main commit. It retains separate
aspect entry points under `aspects/` without copying old logs or claiming that
they are read-only mounts. The inherited Primary `flows/` tree remains the
available historical view.

Workers use the inherited root `AGENTS.md`, `SKILL_VARIABLES.md`, and
`NON_MANAGEMENT_AGENTS.md`. The generated skill catalogs are inherited from
Primary, not materialized as a new native catalog, so this scaffold is not
ready to launch a native main flow.
