# Supabase Self-Hosting

This is a fork of the supabase repository with only the `docker` folder.
Follow the steps [here](https://supabase.com/docs/guides/hosting/docker) to get
started.

## Usage

1. Copy `.env.example` to `.env` and update the values as needed.
2. Run `docker-compose up -d` to start the services.
3. Run `docker-compose down` to stop the services.

## Updating

Assuming you have cloned the `supabase` repository in the parent directory, you
can update the image by running the following commands:

```bash
cp -r ../supabase/docker/. ./docker
```