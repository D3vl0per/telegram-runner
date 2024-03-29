<h1 align="center">Medousa</h1>

<p align="center">
	<img src="docs/img/medousa.png" width="70%" />
</p>

## Description

Medousa is part of the [Agora project](https://github.com/AgoraSpaceDAO). She
is a ruthless greek goddess who works as a Telegram bot and does all the dirty
work from removing intruders to providing extra privileges to premium users.

- [Website](https://agora.space)
- [Changelog](./CHANGELOG.md)
- [License](./LICENSE)

## Getting started

Install dependencies (Telegraf):

```bash
npm install
# or
yarn install
```

Create a new file called .env and add the following environment variables:

```bash
BOT_TOKEN=123456:ABC-DEF1234ghIkl-zyx57W2v1u123ew11
BACKEND_URL="https://agora.space/api/"
```

Run the bot:

```bash
# for development:
npm run dev
# or
yarn dev

# for production:
npm run build && npm run prod
# or
yarn build && yarn prod
```

## Documentation

For the full, comprehensive documentation on how to add Medousa to your group
and how to customize her to suit your needs read the markdown documents in the
[docs](./docs) folder.

## Contributing

Thank you for your interest in contributing! Please refer to
[CONTRIBUTING.md](./docs/CONTRIBUTING.md) for guidance.
