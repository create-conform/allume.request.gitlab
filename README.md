# allume.request.gitlab
Allume request module for fetching releases from GitLab.


## Configuration

### urlNamespaceSeperator

Overrides the package namespace seperator (a dot '.') with the given character. This was introduced to fix a bug that caused the download archive function in the GitLab api to report a 404 when a repository was specified that has dots in the url path. Hopefully this will be fixed sooner than later.

### enableCache

Enables caching of packages on host machine for offline availability.

### token

Sets the private token used for accessing the repository.

### branch

If set the last commit of the given brach is used instead of tags with a matching version.

### URL Support

**Repository Namespace:**

https://gitlab.com/create-conform/

**Direct:**

https://gitlab.com/create-conform/cc_demo/

Note:
URL must always end with slash.