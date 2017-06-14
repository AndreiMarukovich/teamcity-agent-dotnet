# TeamCity Build Agent for .NET Core
TeamCity Build Agent image with pre-installed .NET Core runtime and tools.

The image is based on the official jetbrains/teamcity-agent image and extends it by installing the .NET Core SDK.

Image's tag represents a version of the installed .NET Core SDK. Note that the version of the SDK is decoupled from the version of the carried runtimes. For example, SDK 1.0.4 installs .NET Core runtimes 1.0.5 and 1.1.0.

The 'latest' tag denotes an image with the latest stable version of the SDK. 


