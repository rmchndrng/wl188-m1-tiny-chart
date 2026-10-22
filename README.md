# m1-tiny-chart (SYNTHETIC)
Fixture for the M1 root e2e (scripts/e2e/m1/fixtures.sh). Published as `rmchndrng/wl188-m1-tiny-chart` by scripts/wl188-fixtures.sh.
- `chart/`    one Deployment running an external image (`busybox:1.36.1`, sleeps). The good chart.
- `bad-crds/` same chart plus a `crds/` directory: the runner must refuse it with failure_class `chart_has_crds`.
No customer content.
