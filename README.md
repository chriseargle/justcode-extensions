Telerik has built extensions for JustCode to demonstrate usage of the public JustCode API and to collect individual contributions for JustCode in one package. These extensions are open sourced and licensed under MS-PL. You are welcome to use this project as the basis for creating your own.

Prerequisites
-------
  - Microsoft Visual Studio: http://msdn.microsoft.com
  - The Visual Studio SDK: http://msdn.microsoft.com/en-US/vstudio/vextend
  - Telerik JustCode: http://www.telerik.com/products/justcode.aspx
 
How to use this project
-------
  1. Get the sample source code and open JustCodeExtensions.sln inside Visual Studio. 
  2. Run/Debug the solution. Another Visual Studio instance will start with the sample extensions loaded by JustCode. 
  3. You can test the extensions inside the started Visual Studio instance. Currently, the samples include
   - JustCode.Analyzers: Custom analyzers that make JustCode show additional warnings
   - JustCode.Cleaning: Custom code cleaning steps that are available as part of [JustCode's **Clean Code**](http://www.telerik.com/help/justcode/code-cleaning-clean-code.html) feature
   - JustCode.Navigation: Custom navigation features, that are available in [JustCode's **Navigate**](http://www.telerik.com/help/justcode/code-navigation-and-search.html) Visual Aid section
 You can add additional commands, analyzers or code cleaning steps inside the existing Github project. 
 
Create your own project
------
 You can create your own JustCode extension project using the [Visual Studio template](http://www.telerik.com/help/justcode/reference-custom-justcode-extension.html) that is installed as part of JustCode.

Distribution of your own project
------
 JustCode extensions can be packaged and distributed as Visual Studio Extensions in the [Visual Studio Gallery](http://visualstudiogallery.msdn.microsoft.com/). Search for *JustCode* there and you'll find some of the samples published in this project.
 

