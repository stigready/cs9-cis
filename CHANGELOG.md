# Changelog

Format based on [Keep a Changelog](https://keepachangelog.com/).

## [0.3.0] - 2026-09-12

### Changed
- StigForge export refresh for `cs9_cis` at `0.3.0`.

### Verified (OpenSCAP)

- **`cis-l1`** — score **96.0%** (floor 90.0%) · gate **PASS** · evidence `20260912T125303Z`
  - Remaining counted failures: `accounts_password_pam_modules_in_authselect_profile, file_permissions_ungroupowned, use_pam_wheel_group_for_su`
- **`cis-l2`** — score **96.1%** (floor 90.0%) · gate **PASS** · evidence `20260912T125551Z`
  - Remaining counted failures: `accounts_password_pam_modules_in_authselect_profile, file_permissions_ungroupowned, use_pam_wheel_group_for_su`
- **`cis-ws-l1`** — score **96.0%** (floor 90.0%) · gate **PASS** · evidence `20260912T125730Z`
  - Remaining counted failures: `accounts_password_pam_modules_in_authselect_profile, file_permissions_ungroupowned, use_pam_wheel_group_for_su`
- **`cis-ws-l2`** — score **96.05%** (floor 90.0%) · gate **PASS** · evidence `20260912T125950Z`
  - Remaining counted failures: `accounts_password_pam_modules_in_authselect_profile, file_permissions_ungroupowned, use_pam_wheel_group_for_su`

### Provenance

- Factory pipeline: https://github.com/stigready/stigforge/actions/runs/34693316989
- Factory commit: `562a1f7c1a8e19235ee26e972174d1be6c88998c`

## [0.2.4] - 2026-07-31

### Added
- Initial StigForge export of matrix role `cs9_cis`.
- OpenSCAP verify evidence bundles per profile under `compliance/releases/`.

### Verified (OpenSCAP)

- **`cis-l1`** — score **98.67%** (floor 90.0%) · gate **PASS** · evidence `20260731T090425Z`
  - Remaining counted failures: `configure_custom_crypto_policy_cis`
- **`cis-l2`** — score **98.7%** (floor 90.0%) · gate **PASS** · evidence `20260731T090749Z`
  - Remaining counted failures: `configure_custom_crypto_policy_cis`
- **`cis-ws-l1`** — score **98.67%** (floor 90.0%) · gate **PASS** · evidence `20260731T090932Z`
  - Remaining counted failures: `configure_custom_crypto_policy_cis`
- **`cis-ws-l2`** — score **98.68%** (floor 90.0%) · gate **PASS** · evidence `20260731T091210Z`
  - Remaining counted failures: `configure_custom_crypto_policy_cis`

### Provenance

- Factory pipeline: https://github.com/stigready/stigforge/actions/runs/30617333526
- Factory commit: `5c2fc8f5ad23bdd66e77fe95e1363d5a10c9f05d`

## [0.2.1-private-review] - 2026-07-28

### Changed
- Galaxy-style layout: Ansible role at repository root; evidence under `compliance/`.
- Private review tag `v0.2.1-private-review` (supersedes nested `roles/<role>/` export).

## [0.2.0-private-review] - 2026-07-26

### Added
- First private StigForge export to `stigready/*` (factory review; nested role path).
