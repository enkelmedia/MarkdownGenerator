MarkdownGenerator
===
Generate markdown from C# binary & xml document for GitHub Wiki.

Sample: See [UniRx/wiki](https://github.com/neuecc/UniRx/wiki)

How to Use
---
Clone and open solution, build console application.

Command Line Argument
- `[0]` = dll src path
- `[1]` = output directory 
- `[2]` = regex pattern to select namespaces (optional)

Put .xml on same directory, use document comment for generate.

for example

```
MarkdownGenerator.exe UniRx.dll md
```

Roadmap and ideas
---

[] Support for SeeAlso to generate "related links" in the end declaration https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/xmldoc/seealso
[] Support for constructors
[] Do we support examples on a "class-level"?
[] Nicer way to show return value
[]
[]
[]
[]




