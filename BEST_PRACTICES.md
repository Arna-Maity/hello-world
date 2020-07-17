## Best Practices while using Git:

1. *Keep commits atomic.*

    This means that all the changes related to a particular bug fix, or feature implementation should be included in a single commit. In case, this is not possible initially, try to **squash** multiple commits into a single commit. This greatly helps in simplifying our git workflow later, when we want to migrate particular features to different branches using the **git cherry-pick** command.

2. *Create a new branch while implementing a new feature.*

    It is always a good idea to create a new branch when starting to work on a new feature.

    This can be helpful in the following situations:
    1. When your application is being deployed from a particular branch, you should keep this branch clean and free from any experimental changes. All experimental changes can be made on a separate branch. You can merge the feature branch to the master/default branch once the feature has been completely implemented and tested.

    2. In case, you are working on a forked project, you might often need to **pull** upstream(repo from which you forked) changes to fetch all the necessary updates and bugfixes. This might fail if you would make all your changes on the master branch itself.

3. *Regularly rebase your feature branches against the master/default branch.*

    This helps to maintain a linear history for your git repo which will help you avoid complicated scenarios of merge conflicts and help maintain the project with ease in long run.

4. *Keep your local copy of a forked repo in sync with the changes in the upstream repo.*

    This helps in avoiding merge conflicts in the future.