---
Description: 'Each named pipe has a unique name that distinguishes it from other named pipes in the system's list of named objects. A pipe server specifies a name for the pipe when it calls the CreateNamedPipe function to create one or more instances of a named pipe.'
ms.assetid: '8f7e717a-648b-421e-ab79-a4abbae670be'
title: Pipe Names
---

# Pipe Names

Each named pipe has a unique name that distinguishes it from other named pipes in the system's list of named objects. A pipe server specifies a name for the pipe when it calls the [**CreateNamedPipe**](createnamedpipe.md) function to create one or more instances of a named pipe. Pipe clients specify the pipe name when they call the [**CreateFile**](https://msdn.microsoft.com/library/windows/desktop/aa363858) or [**CallNamedPipe**](callnamedpipe.md) function to connect to an instance of the named pipe.

Use the following form when specifying the name of a pipe in the [**CreateFile**](https://msdn.microsoft.com/library/windows/desktop/aa363858), [**WaitNamedPipe**](waitnamedpipe.md), or [**CallNamedPipe**](callnamedpipe.md) function:

\\\\*ServerName*\\pipe\\*PipeName*

where *ServerName* is either the name of a remote computer or a period, to specify the local computer. The pipe name string specified by *PipeName* can include any character other than a backslash, including numbers and special characters. The entire pipe name string can be up to 256 characters long. Pipe names are not case-sensitive.

The pipe server cannot create a pipe on another computer, so [**CreateNamedPipe**](createnamedpipe.md) must use a period for the server name, as shown in the following example.

\\\\.\\pipe\\*PipeName*

A pipe server can provide the pipe name to its pipe clients, so they can connect to the pipe. The pipe client discovers the pipe name from some persistent source, such as a registry entry, a file, or another application. Otherwise, the clients must know the pipe name at compile time.

 

 


