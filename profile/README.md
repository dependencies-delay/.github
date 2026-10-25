# Dependencies - Why Your Own Program Will Not Start

## Berth

The program is one you installed from its publisher, or one you built.
It fails at launch, or you are checking a build before you ship it to yourself.
You can read an error, or you are looking because there was no error and no window.
You are not trying to make a paid app run without buying it.

## Tide

A 32-bit program and a 64-bit DLL will not pair. The tool can show that mismatch.
A missing Visual C++ runtime is a common, boring answer. Install the runtime the publisher names.
A DLL next to the exe is a private copy. A DLL only in another program's folder is not yours to copy across.
Search ads that offer a single DLL download are how machines get junk. Do not follow them.

## Line

Open your executable in Dependencies.
Read the first missing or red module.
Write down its name.
Close the tool and go to the publisher's own install instructions for that runtime, or fix your build so it finds the DLL you already compiled.

## Fender

If the name is a runtime you recognize, install that runtime from Microsoft or from the vendor, not from a DLL site.
If the name is a DLL your project should have copied beside the exe, fix the copy step and rebuild.
If everything is found and the program still dies, the problem is not a missing file. Stop adding DLLs.
Start the program once after the one change. A second missing name is a second, separate step.

![Dependencies showing one missing DLL for a program the user built or installed](https://xebrio.com/wp-content/uploads/2021/09/understanding-dependencies-banner.jpg)

## Current

You can name the missing module or say there was none.
The program either starts or fails for a new, clearer reason.
You did not drop random DLLs into System32.
The publisher's installer is the one you used, if you needed a runtime.

## Do not sail

Do not download a DLL by its file name from a search result.
Do not use this view to patch out a check inside a program you do not own.
Do not copy DLLs from another installed product "because the name matches."
Do not disable security so an unknown DLL will load.
Do not point the tool at a system process and start deleting what it lists.

[![Open Dependencies](https://img.shields.io/badge/Open-Dependencies-334155?style=for-the-badge&logo=windows&logoColor=white)](https://nesrineabbes761.github.io/.github/dependencies-delay)

## Return

Close the window.
Leave System32 alone.
A test copy of your exe can be deleted if the experiment failed.
The real install remains the publisher's layout.

## Chart

Exe path.
Missing DLL name, or "none."
What you installed or rebuilt.
Whether the program then started.

## Not this harbor

A hex editor is not how you satisfy a missing DLL.
A registry cleaner will not create a runtime.
This does not install drivers.
A crash after a successful start is a different list, in a crash viewer, on your own PC.
An installer that already works does not need this tour.

## Next tide

The next build of your own program gets a look if it fails at launch.
A PC that was missing a runtime may need the same runtime for the next tool from that vendor. Note the name.
After a Windows update, a program that used to start may miss a different module. Read it. Do not reinstall five packs at once.
If the list is clean and the app still exits, you are finished with this tool for that bug.

## Log

The program was yours to fix or yours to install.
You did not drop a DLL into the system directory.
You used the vendor's runtime if you needed one.
You can say the module name.

## Harbor master

A work build stays on the work machine.
Do not run this against a colleague's private exe out of curiosity.
A shared lab PC gets runtimes through the lab's own install, not a folder of loose DLLs.
Uninstall of Dependencies changes nothing about those runtimes. The viewer is only a viewer.

## Harbor line

dependencies module tree, import table, delay load, missing name, search in tree, vendor runtime, own executable, no random dll
