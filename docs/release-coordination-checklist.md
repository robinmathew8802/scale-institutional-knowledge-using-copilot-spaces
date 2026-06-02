# Release Coordination Checklist

Use this during release planning and execution.

Pre-release
- [ ] Release Manager assigned and release window scheduled
- [ ] All required PRs merged and CI green
- [ ] Security scans completed and cleared
- [ ] QA Lead has run regression and smoke tests
- [ ] Release notes drafted
- [ ] Rollback plan documented and tested (where possible)
- [ ] Stakeholder Advocate notified of expected changes

Deployment
- [ ] Backup/snapshot taken (if applicable)
- [ ] Deploy to staging and run post-deploy smoke tests
- [ ] Production deployment performed by automated pipeline or Release Manager
- [ ] Post-deploy verification & monitoring checks run

Post-release
- [ ] Confirm no critical incidents reported in X hours
- [ ] Update status in project README and notify stakeholders
- [ ] Capture any release-related action items and assign owners
