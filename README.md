<br />
<p align="center">
  <a href="https://github.com/dec0dOS/zero-ui">
    <img src="docs/images/logo.png" alt="Logo" width="150" height="150">
  </a>

  <p align="center">
    ZeroUI - ZeroTier Controller Web UI - is a web user interface for a self-hosted ZeroTier network controller.
    <br />
  </p>
</p>

---

## About

The point of this fork is to run zero-ui native, attached to and controlling your local zerotier-one process for self-hosting.

## Getting Started

### Build
1. `npm install -g pm2 yarn`
2. Clone the repository
3. `cd zero-ui/app/frontend`
4. `yarn install`
5. `cd ../backend`
6. `yarn install`
7. `cd ../..`
8. `cp -R frontend/* app/frontend/`
8. `cp -R backend/* app/backend/`

### Run
1. `cd app/backend`
2. `node bin/www`
