# C# - Inbound Call Queue Tutorial

This project serves as a guide to help you build an application with FreeClimb. View this tutorial on [FreeClimb.com](https://docs.freeclimb.com/docs/inbound-call-queue#section-c). Specifically, the project will:

- Add a Caller to a queue
- Play audio to the caller in the queue
- Get digits from the caller
- Exit the queue when a key is pressed

## Setting up your new app within your FreeClimb account

To get started using a FreeClimb account, follow the instructions [here](https://docs.freeclimb.com/docs/getting-started-with-freeclimb).

## Setting up the Inbound Call Queue Tutorial

1. Install the nuget packages necessary using command:

   ```bash
   $ dotnet add package freeclimb-cs-sdk --version 1.0.0.2
   ```

2. Configure environment variables

   | ENV VARIABLE            | DESCRIPTION                                                                                                                                                                             |
   | ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
   | ACCOUNT_ID              | Account ID which can be found under [API Keys](https://www.freeclimb.com/dashboard/portal/account/authentication) in Dashboard                                                         |
   | AUTH_TOKEN              | Authentication Token which can be found under [API Keys](https://www.freeclimb.com/dashboard/portal/account/authentication) in Dashboard                                               |
   | HOST | The host url where your application is hosted (e.g. yourHostedApp.com) |


## Runnning the Tutorial

1. Run the application using command:

   ```bash
   $ dotnet run
   ```

