# premake-modules

Find documentation on how to make new modules here:
[Developing Modules](https://github.com/premake/premake-core/wiki/Developing-Modules)

General premake documentation here:
[Premake Wiki](https://github.com/premake/premake-core/wiki)

### Publishing your module.

- Make sure your module is a public project, otherwise the module server cannot clone the project for packaging. 
- Setup a github webhook to: https://packagesrv.com/api/v1/githubwebhook
- Select the 'Let me select individual events' option, and check the "Create" and "Release" checkboxes.
- Then whenever you create a release, using a [semver](http://semver.org) compliant version number, the module server will:
  - Pull down that release and publish it on 'https://packagesrv.com'.
  - Update the list below.

### List of Premake 5 modules.

| Name | Description | Repository link |
| :--- | :--- | :--- |
| raw | Generate raw representation of Premake structures | https://github.com/premake/premake-raw.git |

