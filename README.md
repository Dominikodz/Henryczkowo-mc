# Henryczkowo-MC

[![Author](https://img.shields.io/badge/Made%20with%20%E2%99%A5%EF%B8%8F%20by-Dominikodz-red?style=for-the-badge)](https://www.instagram.com/dominikodz/)

[![Language](https://img.shields.io/badge/Language-Polish-brightgreen?style=for-the-badge&logo=github)](https://en.wikipedia.org/wiki/Polish_language)

Polish Minecraft server site source.

## Usage

For getting info from minecraft server, it uses [mcstatus.io](https://mcstatus.io/) API. You can change API link to your server

Basic index.html 
just download and open.

Or you can host it on a dedicated server using nginx:
```
server {
       listen 80;
       listen [::]:80;

       server_name {YOUR_DOMAIN/IP};

       root /var/www/henryczkowo;
       index index.html;

       location / {
               try_files $uri $uri/ =404;
       }
}
```

## Dynmap

This site is using [Dynmap](https://github.com/webbukkit/dynmap)! You can change the link for your server dynmap under navbar and about section.

## MinecraftStats

This site is using [MinecraftStats](https://github.com/pdinklag/MinecraftStats)! You can change the link for your server stats under navbar and about section.

## Warning!

Source might be poorly coded but author is still learning (+ was drunk while coding this).

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

> Copyright (c) 2018-2022 Dominikodz

This project is licensed under the [MIT License](https://opensource.org/licenses/mit-license.php) - see the [LICENSE](https://github.com/Xonn1com/Henryczkowo-mc/blob/main/LICENSE) file for details.