 ## 安装gitlab runner
 
 参考 ：[https://gitlab.com/gitlab-org/gitlab-ci-multi-runner/blob/master/docs/install/linux-repository.md](https://gitlab.com/gitlab-org/gitlab-ci-multi-runner/blob/master/docs/install/linux-repository.md)
 
 
1. Add GitLab's official repository:
```
# For Debian/Ubuntu
curl -L https://packages.gitlab.com/install/repositories/runner/gitlab-ci-multi-runner/script.deb.sh | sudo bash

# For RHEL/CentOS
curl -L https://packages.gitlab.com/install/repositories/runner/gitlab-ci-multi-runner/script.rpm.sh | sudo bash

```

2. Install gitlab-ci-multi-runner:
```
# For Debian/Ubuntu
sudo apt-get install gitlab-ci-multi-runner

# For RHEL/CentOS
sudo yum install gitlab-ci-multi-runner

```
