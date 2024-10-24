# Stytch: B2B Magic Links Example

This repository contains a sample application demonstrating a B2B Magic Link and Google OAuth flow using a Go backend.

## Running Locally

### Prerequisites

- Go `^v1.22`.
- A Stytch account.
  - A test project.
  - The project id and project secret for your test project.

### Quickstart

#### 1. Clone the repo.

```shell
git clone git@github.com:stytchauth/stytch-go-b2b-magic-links.git
```

#### 2. Install dependencies.

```shell
go get
```

#### 3. Populate environment variables.

```shell
cp .env.template .env.local
```

Populate the `STYTCH_PROJECT_ID` and `STYTCH_SECRET` in the new `.env.local` file.

#### 4. Run the application.

```shell
go run ./...
```

The service will be available at [http://localhost:3000/](http://localhost:3000/).

## Next steps

This example app showcases a small portion of what you can accomplish with Stytch. Next, explore adding additional login methods, such as [SSO](https://stytch.com/docs/b2b/guides/sso/initial-setup).

## Get help and join the community

#### :speech_balloon: Stytch community Slack

Join the discussion, ask questions, and suggest new features in our ​[Slack community](https://stytch.com/docs/resources/support/overview)!

#### :question: Need support?

Check out the [Stytch Forum](https://forum.stytch.com/) or email us at [support@stytch.com](mailto:support@stytch.com).
