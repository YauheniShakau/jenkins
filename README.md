# Jenkins Backup Lab

A 2018 practice repository for a Jenkins backup workflow. It contains an Ubuntu Trusty Vagrant definition and examples of Jenkins backup and archive jobs.

## Implementation guide

| File or directory | Purpose |
| --- | --- |
| [`Vagrantfile`](Vagrantfile) | Ubuntu Trusty VM definition |
| [`jenkins-bkp/jobs`](jenkins-bkp/jobs) | Saved job definitions for backup and archiving |

## Inspect the lab

```sh
ruby -c Vagrantfile
```

The Vagrantfile selects `ubuntu/trusty64`. Jenkins requires a separate installation. The saved jobs were created for an earlier Jenkins environment. Keep any replay isolated and review the job configuration before running it.

[Implementation history](https://github.com/YauheniShakau/jenkins/commits/master/)
