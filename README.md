Einstein Engines -> Nuclear 14 -> blue station

## Building

Refer to [the Space Wizards' guide](https://docs.spacestation14.com/en/general-development/setup/setting-up-a-development-environment.html) on setting up a development environment for general information, but keep in mind that Einstein Engines is not the same and many things may not apply.
We provide some scripts shown below to make the job easier.

### Build dependencies

> - Git
> - .NET SDK 9.0.101


### Windows / Linux

> 1. Clone this repository
> 2. Run `dotnet build` in a terminal
> 4. Run `dotnet run --project Content.Server` and `dotnet run --project Content.Client` in a terminal to launch client and the server 
> 4.1. If it doesn't work, try `dotnet run --project Content.Server --configuration Release` and `dotnet run --project Content.Client --configuration Release` instead, it might help
> 5. Connect to localhost in the client and play

### MacOS

> May God help you

## License

Please read the [LEGAL.md](./LEGAL.md) file for information on the licenses of the code and assets in this repository.
