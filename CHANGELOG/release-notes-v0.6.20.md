## v0.6.20

## Bugs
- fix: resource tree panic fix (#3775)
- fix: remove use-buildx flag to use k8s buildx driver (#3773)
- fix: updated user flow update api unlock condition (#3770)
- fix: rbac fix terminal connection on view and edit in helm apps (#3723)
- fix:  Intermittent helm apps deployment fail deployed through gitops (#3756)
- fix: server version check for ephemeral suport bug fix (#3757)
- fix:  app status fix for helm apps which are deployed via acd (#3746)
- fix: Showing port number instead of string port_number. (#3729)
- fix:migration script issue  (#3750)
- fix: resource tree error handling miss (#3704)
- fix: manifest output is not in sync with selected chart version and wrong manifest coming in deployment history (#3701)
- fix: empty format type in global variable fix (#3695)
- fix: matching k8s version using regex for ephemeral container feature support (#3688)
- fix: auto deploy fix for migrated pre/post cd steps where inly one is configured (#3677)
- fix: blob storage upload failed due to USE_BLOB_STORAGE_CONFIG_IN_CI_WORKFLOW flag (#3667)
- fix: Pod for in-cluster not getting scheduled because of node affinity selector. (#3663)
- fix: optimized fetch deployment status timeline api (#3653)
- fix: critical vulnerabilities in dependencies (#3632)
- fix: Scan tool metadata enabling for Security Module (#3598)
- fix: obfuscate secret for devtron/helm apps (#3602)
- Fix: SSO configuration gets change after refreshing the page (#3605)
- fix Role group delete fix (#3609)
- fix: Deployment enforcement config save err(#3626)
- fix: updated ValidateRegistryStorageType for OCI registry configs(#3634)
- fix: Clone of app with external-ci (#3624)
- Fix: optimizing when querying DB to get running Helm deployments (#3637)
## Enhancements
- feat: support for docker buildx k8s driver (#3743)
- perf:  user update api concurrent request handling (#3760)
- feat: workflow to validate PRs if an issue is linked or not (#3730)
- feat:sql script file added for Approval node notification  (#3725)
- feat: Allow changing chart ref (#3706)
- feat: Patch branch api (#3722)
- feat: App grouping admin access (#3692)
- feat: description for apps and jobs (#3668)
- Enhancement: Kubernetes api refactoring (#3635)
- feat: Patch source of ci material api (#3661)
- feat: Bulk deployemnt with appName and EnvName (#3644)
- feat: Ephemeral containers (#3618)
- feat: flag for node (#3654)
- feat: plugin and step support in pre post cd (#3563)
- feat: edit Ingress for specific host (#3640)
- feat: enhancement app workflow clone, added specific deployment clone in workflow (#3645)
- Feature: Run Devtron Jobs in application environment (#3572)
- feat: support for official argo rollout with Canary (#3591)
- feat: image tagging feat (3446)
- feat: pod manifest edit feature and option to connect session with node debug pod (#3116)
- feat: devtronContainerImageRepo variable added (#3604)
- feat: Integrated OCI registries in global config artifact store.(#3567)
- feat: Flag to pass build platform globally(#3625)
- enhancement: enforcing deployment type in environment (#3616)
## Documentation
- docs: removed new line from token generation command (#3710)
- docs: disaster recovery docs (#3236)
- docs: added devtron release note in summary.md (#3681)
- docs: Updated readme for 4.18 chart for winter soldier. (#3673)
## Others
- chore: Addition of K9s image in cluster terminal (#3779)
- chore: migration for kubectl proxy (#3731)
- chore: Update pr-issue-validator.yaml (#3740)
- chore: Removed path-ignore section in pr-issue-validator (#3739)
- fix : Resource list fetch for K8s (#3713)
- integration test cases FW (#3508)
- task: Updated chart version for v0.6.19 (#3639)
- chore: added migration for reference chart 5-0-0 with active false (#3692)
- task: updated plugin list to include i/o vars, refactored detail get api (#3627)

