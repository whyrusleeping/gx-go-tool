# gx-go-tool

A tool to use with the gx package manager for packages written in go.

## Usage:
```
NAME:
   gx-go - gx extensions for golang

USAGE:
   gx-go [global options] command [command options] [arguments...]
   
VERSION:
   0.2.0
   
AUTHOR(S):
   whyrusleeping 
   
COMMANDS:
   update	update a packages imports to a new path
   import	import a go package and all its depencies into gx
   path		prints the import path of the current package within GOPATH
   hook		go specific hooks to be called by the gx tool
   help, h	Shows a list of commands or help for one command
   
GLOBAL OPTIONS:
   --help, -h		show help
   --version, -v	print the version
```

## NOTE:
It is highly recommended that you set your `GOPATH` to a temporary directory when running import.
This ensures that your current go packages are not affected, and also that fresh versions of
the packages in question are pulled down.
