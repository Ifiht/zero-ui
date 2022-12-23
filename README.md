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

### Setup
1. Edit `backend/utils/controller-api.js` if you intend to use a non-standard primary port.
2. `export ZU_DEFAULT_USERNAME="CHANGE_ME"`
3. `export ZU_DEFAULT_PASSWORD="CHANGE_ME"`

### Build
1. `npm install -g pm2 yarn`
2. Clone the repository
3. `cd zero-ui/app/frontend`
4. `yarn install`
5. `cd ../backend`
6. `yarn install`
7. `cp -R ../../frontend/* ./`
8. `yarn build`
9. `cd ../..`
10. `cp -R backend/* app/backend/`

### Run
1. `cd app/backend`
2. `node bin/www`
