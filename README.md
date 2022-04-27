# Docker Compose File for RustDesk Server

The docker compose file to run the [RustDesk](https://rustdesk.com/docs/en/self-host/install/#docker-example) server with almost no efforts.

## Usage

1. Install Docker if you haven't. You may use [this script](https://github.com/jinweijie/install-docker-and-compose) to install Docker with one command.

2. Clone this repository.

3. Create or rename the `.env_example` to `.env`. Update the IP part with your RustDesk server's IP.

4. Run `docker compose up -d` to start the server. (If you have docker-compose, run `docker-compose up -d`)

5. In the RustDesk client application. Set the `ID/Relay server` (Click the 3 dots on the right beside of your ID) with your configured server.

## Donate

If you would like to support my development, feel free to buy me a coffee, it makes a big difference! Thanks.

<a href="https://www.buymeacoffee.com/jinweijie" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/white_img.png" alt="Buy Me A Coffee"></a>