# Fly.io Example App for Medama Analytics

This is a simple repository to store the initial configuration for a Fly.io app that will be used to deploy the Medama Analytics application.

## Getting Started

To deploy the app, you need to have the Fly CLI installed. You can install it by running the following command:

```bash
# Be sure you're running the latest version of flyctl.
fly version update

# Launch the application
fly launch --from https://github.com/medama-io/example-fly-io
```

From there, update the application by running `fly deploy` in the root of the repository.
