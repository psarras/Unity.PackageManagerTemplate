# Package Manager Template

Simple custom package that can be used as a template when starting out with custom packages in Unity.

Put this in the manifest file.

```
    "com.package.template": "https://github.com/psarras/Unity.PackageManagerTemplate.git",
```

This package also contains two examples for adding sample assets on your package. you need to follow the following file structure. [source](https://forum.unity.com/threads/samples-in-packages-manual-setup.623080/)

```
<Root>
 ├── package.json
 ├── samples~
 │   ├── Sample Folder 1
 │   │   └── …
 │   └── Sample Folder 2
 │       └── …
 └── ...
```

## Links

Extra documentation from [Unity Forums](https://forum.unity.com/threads/package-manager-documentation.662611/)

- Learn about packages: [Packages](https://docs.unity3d.com/Manual/Packages.html)
- Find documentation for a specific package: [List of packages](https://docs.unity3d.com/Manual/PackagesList.html)
- Learn how to build a custom package: [Custom packages](https://docs.unity3d.com/Manual/CustomPackages.html)
- [Package Manager Glossary](https://docs.unity3d.com/Manual/Glossary.html#PackManLighting)
