# AspNetCoreAnalyzers

[![Join the chat at https://gitter.im/DotNetAnalyzers/AspNetCoreAnalyzers](https://badges.gitter.im/DotNetAnalyzers/AspNetCoreAnalyzers.svg)](https://gitter.im/DotNetAnalyzers/AspNetCoreAnalyzers?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Build status](https://ci.appveyor.com/api/projects/status/wk4ra33vaa9okd9o/branch/master?svg=true)](https://ci.appveyor.com/project/JohanLarsson/aspnetcoreanalyzers/branch/master)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)


Roslyn analyzers for ASP.NET.Core.


<!-- start generated table -->
<table>
  <tr>
    <td><a href="https://github.com/DotNetAnalyzers/AspNetCoreAnalyzers/tree/master/documentation/ASP001.md">ASP001</a></td>
    <td>The parameter name does not match the url parameter.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/DotNetAnalyzers/AspNetCoreAnalyzers/tree/master/documentation/ASP002.md">ASP002</a></td>
    <td>The method has no corresponding parameter.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/DotNetAnalyzers/AspNetCoreAnalyzers/tree/master/documentation/ASP003.md">ASP003</a></td>
    <td>Parameter type does not match template.</td>
  </tr>
<table>
<!-- end generated table -->


## Using AspNetCoreAnalyzers

The preferable way to use the analyzers is to add the nuget package [AspNetCoreAnalyzers](https://www.nuget.org/packages/AspNetCoreAnalyzers/)
to the project(s).

The severity of individual rules may be configured using [rule set files](https://msdn.microsoft.com/en-us/library/dd264996.aspx)
in Visual Studio.

## Installation

AspNetCoreAnalyzers can be installed using [Paket](https://fsprojects.github.io/Paket/) or the NuGet command line or the NuGet Package Manager in Visual Studio.


**Install using the command line:**
```bash
Install-Package AspNetCoreAnalyzers
```

## Updating

The ruleset editor does not handle changes IDs well, if things get out of sync you can try:

1) Close visual studio.
2) Edit the ProjectName.rulset file and remove the AspNetCoreAnalyzers element.
3) Start visual studio and add back the desired configuration.

Above is not ideal, sorry about this. Not sure this is our bug.


## Current status

Early alpha, names and IDs may change.
