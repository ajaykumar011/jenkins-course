https://www.linode.com/docs/development/ci/automate-builds-with-jenkins-on-ubuntu/#scripted-vs-declarative-pipeline-syntax


Preliminary AssumptionsPermalink
This guide is oriented toward DevOps professionals and thus presumes:

A local workstation will be used for development and testing.

A Linode will be used for the remote Jenkins server.
Both will use Ubuntu 16.04.
Jenkins will be used mainly through the newer Blue Ocean web interface.

The workstation and remote Linode will each need Docker installed beforehand. See our guide on how to install docker images for detailed instructions.

For the purpose of this guide, only a Jenkins master server will be used.

You will need a GitHub account already created, or similar procedures can be used for Bitbucket and GitLab.

You will also need a Docker Hub or similar registry account.