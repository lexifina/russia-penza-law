<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Penza Oblast only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-26 05:50 UTC, Penza Oblast: Official Internet Portal of Legal Information (region58): 15 addresses read; 0 added, 0 changed, 0 removed; no change; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Penza Oblast: Official Internet Portal of Legal Information (region58)](http://publication.pravo.gov.ru/documents/block/region58) | `zakony-<year>/` | daily | 2026-11-26 05:50 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-26 05:49](checks/2026-11.md#ru-pravo-penza-20261126t054923z) | pravo-penza | 15 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-25 06:24](checks/2026-11.md#ru-pravo-penza-20261125t062425z) | pravo-penza | 15 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-24 14:24](checks/2026-11.md#ru-pravo-penza-20261124t142454z) | pravo-penza | 15 | 25 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-penza-law/compare/fd6a692b5187...04266c0e05c5) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
