# CodeMirror
ORIGINAL RELEASES of CodeMirror

CodeMirror is a versatile text editor implemented in JavaScript for the browser.
https://codemirror.net/

# Project Details
## Purpose
CodeMirror does not have a v5 release package on NuGet. This package contains the necessary files to run CodeMirror v5 offline and is published as CodeMirror.Erideon on NuGet.

## CodeMirror Version updates
Upon a new v5 release of CodeMirror, update the files as needed (replace all folders of the package and their contents) and ship as new NuGet version.
Update the nuspec file with the new version number and release notes

## NuGet package update
After all CodeMirror files are updated, navigate to the CodeMirror solution folder and run the following command to create a new NuGet package version (PowerShell or other command line)

./nuget pack CodeMirror/CodeMirror.nuspec

Upload the resulting file to NuGet

