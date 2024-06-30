# Fly.io Example App for Medama Analytics

This is a simple repository to store the initial configuration for a Fly.io app that will be used to deploy the Medama Analytics application.

## Getting Started

To deploy the app, you need to have an account on Fly.io and Fly CLI installed. Then you can run the following commands in a directory such as `medama-analytics`:

```bash
# Make a directory for the configuration
mkdir medama-analytics
cd medama-analytics

# Be sure you're running the latest version of flyctl.
fly version update

# Launch the application
fly launch --from https://github.com/medama-io/example-fly-io
```

From there, update the application by running `fly deploy` in the root of the repository.
