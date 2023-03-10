# EzApi2012

Fork of [EzApi](http://sqlsrvintegrationsrv.codeplex.com/releases/view/21238) adapted for SQL Server 2012 version. Stand-alone edition forked by KoureasS & GitHub.

## Instructions
SQLServer2012EzApi is producing SQL Server Packages with the following charateristics:
1. Build --> 11
2. PackageFormatVersion --> 6
3. TargetSQLServerVersion --> 2012

*Based on Microsoft Intructions, SQLServerPackages should be deployed on SQLServer using aligned version of Management Studio.
**Management Studio deployment wizard may affect the Build and PackageFormatVersion in case of using a newer version of SSMS for deploying package with older TargetSQLServerVersion version.

## Updates
2023-03-09 Added EzExecutables.EzPackage.MaxConcurrentExecutables

## Changelog
Major changes from SQLServer2008EzApi --> SQLServer2012EzApi

1. EzProject.Project
2. EzProject.PackageItems
3. EzProject.ConnectionManagerItems
4. EzProject.Parameters
5. EzProject.Password
6. EzProject.CreationDate
7. EzProject.CreatorName
8. EzProject.Description
9. EzProject.ID
10. EzProject.Name
11. EzProject.ProtectionLevel
12. EzProject.VersionBuild
13. EzProject.VersionComments
14. EzProject.VersionMajor
15. EzProject.VersionMinor
16. EzProject.AddPackage
17. EzProject.InsertPackage
18. EzProject.RemovePackageAt
19. EzProject.RemovePackage
20. EzProject.AddConnectionManager
21. EzProject.RemoveConnectionManagerAt
22. EzProject.RemoveConnectionManager
23. EzProject.AddProjectParameter
24. EzProject.RemoveParameter
25. EzProject.OpenProject
26. EzProject.CloseProject
27. EzProject.SaveTo
28. EzProject.SaveAs
29. EzProject.Save
30. EzSourceDestinationProject.AddPackage
31. EzSourceDestinationProject.AddAdoNetPackage
32. EzSourceDestinationProject.AddOleDbPackage
33. EzSourceDestinationProject.AddOleDbToFilePackage
34. EzSourceDestinationProject.AddFlatFileToOleDbPackage
35. EzTransformProject.AddPackage
36. EzTransformProject.AddAdoNetPackage
37. EzTransformProject.AddOleDbPackage
38. EzTransformProject.AddOleDbToFilePackage
39. EzTransformProject.AddFlatFileToOleDbPackage

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Credits

Credits are for Microsoft =)

## License

The project inherits the Microsoft license: 

Copyright © Microsoft Corporation.  All Rights Reserved.

This code released under the terms of the 

Microsoft Public License (MS-PL, http://opensource.org/licenses/ms-pl.html.)
