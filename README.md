# C# Flex

This is a fork of the original [C# Port by Jonathan Gilbert on SourceForge](https://sourceforge.net/projects/csflex/).

***

## Original README 
from https://sourceforge.net/projects/csflex/

> This is the initial release of C# Flex, the translation of JFlex to C#. It
> borrows the JFlex version number of 1.4, but as it has not had extensive
> testing, it is classified as a beta test release.
> 
> C# Flex has a SourceForge.net project home page at the following URL:
> 
>   https://sourceforge.net/projects/csflex/
> 
> This is the place to go to look for new releases and file bug reports.
> 
> Note that I have not tested building C# Flex under mono. I do not know if
> mono's build tools support the embedding of resources (as would be accessed
> through Assembly.GetManifestResourceStream and the ResXResourceReader class
> in the System.Resources namespace). If it does not, then the code cannot be
> built under mono, but if it does, it should be possible to build it; the files
> "skeleton.default", "skeleton.nested" and "Messages.xml" must be embedded for
> C# Flex to run correctly.
> 
> I have also not tested running C# Flex under mono. Again, the only issue I can
> think of is resources. In fact, I'm not even certain System.Resources is a part
> of the ECMA specification; it's possible that it's proprietary, like
> System.Windows.Forms. Which is the other issue: The GUI might not work properly
> under mono, depending on the completeness of the S.W.F implementation (at the
> time of this release, February 15th 2005, probability is pretty low). However,
> it should still be able to build, provided that Button, Label, TextBox and
> Open/SaveFileDialog are properly stubbed. The command-line interface should
> work regardless of whether S.W.F is present :-)
> 
> Building and running under Windows with Microsoft's runtime and Visual Studio
> .NET should be much more straight-forward: Simply load the included .sln file
> and hit "Build". Without Visual Studio .NET, perhaps some alternative build
> tool can parse the .csproj file. If not, then compiling by hand will be a pain
> in the ass, but doable. There should be no issues with S.W.F and
> System.Resources compatibility :-)
> 
> Note that this source code distribution contains files generated with this
> tool and with C# CUP. These files can be generated with the respective tools.
> Also note that this project makes use of C# CUP's runtime. This file is
> included in this distribution as it is a requirement for building C# Flex.
> 
> Hopefully this tool can be of some use to you in your projects. Good luck!
> 
> \- Jonathan Gilbert
> 