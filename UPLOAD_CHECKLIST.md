# GitHub publication checklist

- [ ] Confirm the GitHub connection has write permissions to `zpala1/datapub`.
- [ ] Do not upload third-party raw hydrology/meteorology data without redistribution permission.
- [ ] Confirm the monthly flow variable's measurement unit and aggregation.
- [ ] Refactor absolute `/mnt/data` paths to configurable local directories.
- [ ] Pin Python dependency versions and re-run on a clean environment.
- [ ] Review and exclude any personally identifying or confidential metadata.
- [ ] Publish in a dedicated `meric-streamflow/` directory, without modifying existing datasets.
- [ ] After final release, archive a versioned GitHub release with Zenodo if permitted, to obtain a stable DOI.
- [ ] Replace the provisional Data Availability Statement with one describing the actual deposited files and access restrictions.
