#Remote Data Blocks Demo

This repo uses [WordPress Playground](https://playground.wordpress.net/) to provide interactive examples of using Remote Data Blocks with Spotify.

[![Launch in WordPress Playground](https://img.shields.io/badge/Launch%20in%20WordPress%20Playground-DA9A45?style=for-the-badge&logo=wordpress)](https://wordpress-playground.atomicsites.blog/?blueprint-url=https://raw.githubusercontent.com/Automattic/spotify-demo/trunk/blueprint.json)

**Note: WordPress Playground sometimes retains state from previous sessions. Opening a new incognito window may be necessary to get a fresh start.**

Remote Data Blocks is a WordPress plugin that makes it easy to combine content and remote data in the block editor. Easily register blocks that load data from Airtable, Google Sheets, Shopify, GitHub, or any other API. [Read more about well-supported use cases](https://github.com/Automattic/remote-data-blocks).

A [simple plugin](./spotify.php) is included to demonstrate the use of remote data blocks with Spotify. Before using it, replace the placeholder credentials in `spotify.php` with your own Spotify API credentials:

- `YOUR_SPOTIFY_CLIENT_ID` — Your Spotify app's Client ID
- `YOUR_SPOTIFY_CLIENT_SECRET` — Your Spotify app's Client Secret
- `YOUR_SPOTIFY_ARTIST_ID` — The Spotify Artist ID you want to display top tracks for

You can obtain a Client ID and Client Secret by creating an app in the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard).

Without this plugin, significant custom development would be necessary to retrieve, cache, and output this third-party information.
