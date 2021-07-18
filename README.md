# SCA-Cloud-School-Application
This repo contains the SCA cloud school application assessment


Exercise
Jenkins Pipeline (or simply "Pipeline") is a suite of plugins which supports implementing and integrating continuous delivery pipelines into Jenkins. A continuous delivery pipeline is an automated expression of your process for getting software from version control right through to your users and customers

Git : Git steps performs a clone from the specified repository. Checkout from the git client plugin source repository using ssh protocol, private key credentials, and the master branch. The credential must be a private key credential if the remote git repository is accessed with the ssh protocol. The credential must be a username / password credential if the remote git repository is accessed with http or https protocol

Build: This method triggers a new build for a given job. The build step also supports passing password parameters, but this is not recommended. The plaintext secret may be persisted as part of the Pipeline's internal state, and it will not be automatically masked if it appears in the build log If enabled (default state), then the result of this step is that of the downstream build (e.g., success, unstable, failure, not built, or aborted). If disabled, then this step succeeds even if the downstream build is unstable, failed, etc.
