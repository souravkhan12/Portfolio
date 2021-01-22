# My Protfolio's frontend Hosted on netlify and Backend on heroku
https://inspiring-ritchie-d6fd98.netlify.app
# To Run in your environment
# ---------------------------Follow-------------------------
# Profile FE

## Testing

```bash
npm test
```

## Local Run

Set up your development environment

```bash
npm install
cp .env.template .env.development
```

Provide correct values in `.env.development` and proceed with local run:
```bash
npm start
```

## Deployment

Similar to `.env.development`, create a `.env.production` file with necessary variables.

Sign up for Netlify and install Netlify CLI

```bash
netlify login
```

Proceed with deployment:
```bash
npm run-script build
netlify deploy --dir=public --prod
```
