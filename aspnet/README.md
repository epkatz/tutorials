#Beginning ASP.NET core on linux 

##Installation 

###Linux

In your terminal type:

```curl -sSL https://raw.githubusercontent.com/aspnet/Home/dev/dnvminstall.sh | DNX_BRANCH=dev sh && source ~/.dnx/dnvm/dnvm.sh```

Once you install this, type ```dnvm``` to see a list of options.
Install the coreclr with:
```dnvm upgrade -r coreclr```

Install mono (you'll need for Visual Studio Code)
```dnvm upgrade -r mono```







##Glossary

####DNVM (.NET Version Manager)
DNVM is a set of command line instructions which allow you to configure your .NET Runtime.
####DNX (.NET Execution Environment)
DNX is a SDK and a runtime environment for creating .NET applications for Windows, Mac and Linux. Basically it allows the cross-platform development using the .NET 5 Core.
####DNU (.NET Development Utilities)
DNU is the .NET Development Utility. It allows you to build, package and publish projects created with DNX.



##Helpful Links
http://docs.asp.net/en/latest/getting-started/index.html




