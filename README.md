# UnityPackageTemplate

Template for organizing custom unity package.     
Develop package and sample code at different unity project but manager them in the same git repository. Add the custom package to the sample project by local package or from git url.

## Usage
Just create a new repository from this public template and clone it or download this repository by zip file directly.      

Then rename the `UnityPackageTemplate` part of `src/UnityPackageTemplate` folder, `sample/UnityPackageTemplate.Sample` folder, `src/UnityPackageTemplate/Assets/UnityPackageTemplate` folder and all `UnityPackageTemplate.xxx.asmdef` files to the package name you like.

Add `src/UnityPackageTemplate/Assets/UnityPackageTemplate` and `src/UnityPackageTemplate.Sample` project from UnityHub, develop package code under `src/UnityPackageTemplate/Assets/UnityPackageTemplate` project and sample code under `src/UnityPackageTemplate.Sample` project.

Last, publish the the whole repositoy to github and then your package can be accquired by following steps,

1. Open Package Manager from Window > Package Manager.
2. Click the "+" button > Add package from git URL.
3. Enter the following URL:

```
https://github.com/YourGithubUserName/YourRepositoryName.git?path=src/YourPackageName/Assets/YourPackageName
```


