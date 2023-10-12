Steps before release of the AKS reflector

- [ ] Secret does not exist but cluster exists - Create a new secret
- [ ] Partial apply of clusters - ensure that subsequent reconciliations work
- [ ] Add managed-by labels!
- [ ] Conditions - ready with count of reflected clusters
- [ ] Events - publish when cluster created or removed
- [ ] Suspension
- [ ] Manually triggered reconciliation
- [ ] Provide for authentication via a Secret?