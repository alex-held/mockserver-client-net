[![Build Status](https://travis-ci.org/picadoh/mockserver-client-net.svg?branch=master)](https://travis-ci.org/picadoh/mockserver-client-net) [![NuGet version](https://badge.fury.io/nu/MockServerClientNet.svg)](https://badge.fury.io/nu/MockServerClientNet)

C# Fluent API for interacting with [Mock-Server](http://www.mock-server.com/) targetting .netstandard2.0.


# Mock
dotnet 
# Build

    dotnet build

# Testing

The below command will run the integration tests against a local running instance of Mock-Server.

    dotnet test

Use the following enviornment variables to change the target instance:

- MOCKSERVER\_TEST\_HOST
- MOCKSERVER\_TEST\_PORT

# Using the NuGet Package

Get the latest version from https://www.nuget.org/packages/MockServerClientNet/ and refer to [this page](docs/Samples.md) for usage examples.

# How to Contribute

Please take a look at [CONTRIBUTING](CONTRIBUTING.md) for instructions.

