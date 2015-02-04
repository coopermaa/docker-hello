# docker-hello

A simple repo to demonstrate the Automated Build of Docker Hub.

## To setup an Automated Build

1. Create a Docker Hub account and login.
2. Link your GitHub or BitBucket account through the "Link Accounts" menu.
3. Configure an Automated Build.
4. Pick a GitHub or BitBucket project that has a Dockerfile that you want to build.
5. Pick the branch you want to build (the default is the master branch).
6. Give the Automated Build a name.
7. Assign an optional Docker tag to the Build.
8. Specify where the Dockerfile is located. The default is /.

Once the Automated Build is configured it will automatically trigger a build and,
 in a few minutes, you should see your new Automated Build on the Docker Hub Registry.
 It will stay in sync with your GitHub and BitBucket repository until you deactivate
 the Automated Build.