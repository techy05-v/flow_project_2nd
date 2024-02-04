# Cadence Smart Contract Overview

This repository is home to a Cadence smart contract designed for the Flow blockchain, utilizing its scripting language to demonstrate key concepts. The contract, dubbed `SomeContract`, is structured to exhibit the various access control features that Cadence supports. Through the definition of variables and functions in distinct sections of the contract, it illustrates how scope and accessibility are managed within Cadence.

## Contract Organization

`SomeContract` is meticulously organized into specific areas, each serving a unique purpose in demonstrating access control mechanisms. Below is an outline of these areas and their functionalities:

### Area 1: Struct Functionality

- **Purpose**: Shows how variables within the same contract are accessible.
- **Accessible Variables**: `a`, `b`, `c`, `d` (all with read/write capabilities)
- **Accessible Functions**: None

### Area 2: Resource Functionality

- **Purpose**: Demonstrates variable access within the scope of a resource.
- **Accessible Variables**: `e` (with read/write capabilities)
- **Accessible Functions**: None

### Area 3: Contract-Wide Functionality

- **Purpose**: Highlights access to both variables and functions across the contract.
- **Accessible Variables**: `a`, `b`, `c`, `d` (all with read/write capabilities)
- **Accessible Functions**: `publicFunc`, `contractFunc`, `privateFunc`

### Area 4: Main Function

- **Purpose**: Entry point demonstrating access to specific functions within `SomeContract`.
- **Accessible Functions from SomeContract**: `createSomeResource`, `questsAreFun`

## Accessibility and Scope

The structure of `SomeContract` is a practical example of how Cadence manages access control and scope. By segregating functionalities into distinct areas, the contract provides a clear illustration of how variables and functions can be accessed within different parts of a Cadence contract. This setup not only showcases the language's flexibility but also its robust security features that are essential for developing on the Flow blockchain.
