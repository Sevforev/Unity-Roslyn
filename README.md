# Unity Roslyn (Netstandard 2.0)
All the dependencies required to use .NET Roslyn in Unity (Netstandard 2.0)

# Clarification

This repository contains all the DLL files required for using the Roslyn .NET compiler in Unity, as getting these is a damn struggle. All Copyright belongs to Microsoft; https://github.com/dotnet/roslyn

# Included

List of .DLLs included

| Name | File |
| --------------- | --------------- |
|  Microsoft.CodeAnalysis  | Microsoft.CodeAnalysis.dll  |
|  Microsoft.CodeAnalysis.Scripting  | Microsoft.CodeAnalysis.Scripting.dll  |
| Microsoft.CodeAnalysis.Csharp  | Microsoft.CodeAnalysis.Csharp.dll  |
| Microsoft.CodeAnalysis.Csharp.Scripting  | Microsoft.CodeAnalysis.Csharp.Scripting.dll  |
| System.Collections.Immutable  | System.Collections.Immutable.dll  |
| System.Reflection.Metadata  | System.Reflection.Metadata.dll  |
| System.Runtime.CompilerServices.Unsafe  | System.Runtime.CompilerServices.Unsafe.dll  |

# Personal Notes

Fuck Microsoft - Microsoft.CodeAnalysis.Scripting.dll had been removed from every release of Microsoft.CodeAnalysis.Scripting on NuGet, which meant that I had to spend two hours scavenging the internet for it. Hopefully this repository spares someone else the trouble.

# Installation

Either install this repository as a .ZIP, or install as .Unitypackage from the [Releases -page](https://github.com/Sevforev/Unity-Roslyn/releases/tag/Roslyn)
# Usage Example

# Documentation

Refer to .NET and MS documentation; https://github.com/dotnet/roslyn
