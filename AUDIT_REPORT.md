# Local Audit Report — ratiss-lewm-integration

> Scope: local clone only. No remote repository was modified and no push was performed.

## Repository Structure

| Check | Result |
|---|---|
| Tracked/local file count | 45 |
| Python file count | 12 |
| README | PASS |
| RATISS Labs logo (`docs/assets/logo.png`) | PASS |
| Apache 2.0 LICENSE | PASS |
| `CITATION.cff` | PASS |

## Test Validation

- Command: `python3 -m pytest -v`
- Exit status: `0`

```text
============================= test session starts ==============================
platform linux -- Python 3.12.3, pytest-9.1.1, pluggy-1.6.0 -- /usr/bin/python3
cachedir: .pytest_cache
rootdir: /home/ubuntu/ratiss-labs-repos/ratiss-lewm-integration
configfile: pyproject.toml
plugins: anyio-4.14.2
collecting ... collected 3 items

tests/test_plugins.py::test_topology_interface PASSED                    [ 33%]
tests/test_plugins.py::test_thermo_and_cohesion PASSED                   [ 66%]
tests/test_plugins.py::test_cache_gate PASSED                            [100%]

============================== 3 passed in 0.23s ===============================

```

## Compliance Notes

- Branding and common repository metadata were applied locally.
- Scientific claims were not upgraded from proxy evidence to full validation.
- The three required technical Bible documents were not present in the supplied workspace.
- This report is an engineering audit snapshot, not a claim of zero defects.
