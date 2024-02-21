# C# Unit Testing practice

## Overview

This is a practical project for studying unit testing with xunit in dotnet core

Study source: [Microsoft Learn | Unit testing C# in .NET Core using dotnet test and xUnit](https://learn.microsoft.com/en-us/dotnet/core/testing/unit-testing-with-dotnet-test)

## Takeaway notes

- `Fact` attribute declare a plain test method without taking any parameter
- `Theory` attribute declare a test method that can accept parameters with help of `InlineData` attribute. Value specified in `InlineData` will be passed to test method parameters.
- Each `InlineData` equals to 1 dedicated test
- Test Driven Development (TDD) is a approach to design test first, then code later
