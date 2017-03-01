# gitlab-docker

A single bash script that will help you develop and deploy docker applications with GitLab. It might also work for other repositories as well but it is not tested.

Available features:

- Build docker images locally with image name exacly the same as GitLab requires it
- Automatic docker image name and tag discovery from git remote and current branch
- Push built image to GitLab docker repository
- Deploy application to rancher server locally for development and to staging/production (using rancher CLI)
- Execute commands in running rancher containers (using rancher CLI)

