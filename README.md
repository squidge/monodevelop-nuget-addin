# NuGet Addin for XamarinStudio

This is a branch of the original port [MonoDevelop Nuget Addin](https://github.com/mrward/monodevelop-nuget-addin) that works with XamarinStudio under OS X. It adds a Manage Packages dialog to XamarinStudio where you can install, update or uninstall NuGet packages.

It uses a custom build of [NuGet.Core.dll](https://github.com/mrward/nuget/tree/monodevelop), based on the original NuGet source code taken from the mono-build branch available from [CodePlex](http://nuget.codeplex.com), and also some code from the latest version of the Mono runtime library.

# Requirements

 * XamarinStudio 4.0
 * Mono 2.10.11 or above
 * mono-winfxcore (required by NuGet.Core)
 * mono-wcf (required by NuGet.Core)

# Installation

I am sure the author of the original port will eventually make an add-in repository url available (pull request sent) but in the meantime (as this is only a *hack* branch)
you cand find the add-in package in the [pack](https://github.com/squidge/monodevelop-nuget-addin/tree/xs-nuget-addin/pack) directory so all you need to do is install it in XamarinStudio via the Add-in Manager.

#License

[MIT](http://opensource.org/licenses/MIT)

Original SharpDevelop addin code is [LGPL](http://www.gnu.org/licenses/lgpl-2.1.txt).

#Environments Tested

 * XamarinStudio 4.0
 * OS X Mountain Lion
 * Mono 2.10.11

