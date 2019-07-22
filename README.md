# ScriptUtils

rt.py - A script for creating react components either as a class or a component in a folder substructure with the css file.

Usage: python rt.py <f or function c or class> <name of component or class>
       python rt.py f App
    
Automatically stores under src/components/{componentName}

sc.py - A script for shallow downloads of folders or a file from a github, can work on your private github repos as well if you generate an access token. Super useful for boot strapping react projects by copying over your favorite components from previous projects. Useful in general when you just want a file or a folder from a repo isntead of having to download the entier thing.

Usage: python3 sc.py <GithubRepoOwnerUserName> <RepoName> <RelativePathToFolderOrFileInRepo> <PathToWhereYouWantFileDownloadedToDefaultsTo ./> <Optional access-token-here for your private repos>

       python3 sc.py SaranSundar NSO-GUI react-ui/src/components/NoMatch src/components/NoMatch access-token-here
