# IPTV

A curated IPTV channel collection in JSON format for media player applications, IPTV apps, and streaming projects.

## Features

- JSON-based channel database
- Channel logo support
- Category organization
- M3U8 stream support
- Easy API integration
- Mobile-friendly structure

## JSON Structure

```json
{
  "name": "Channel Name",
  "logo": "https://example.com/logo.png",
  "stream_url": "https://example.com/playlist.m3u8",
  "category": "Sports"
}
```

## Supported Categories

- Sports
- Entertainment
- Movies
- Music
- Cartoon
- Bangladesh
- News
- Documentary

## How To Use

### Fetch JSON

```javascript
fetch("iptv.json")
  .then(res => res.json())
  .then(channels => {
    console.log(channels);
  });
```

### Example

```javascript
const player = new Hls();
player.loadSource(channel.stream_url);
```

## Contributing

Contributions are welcome.

Please ensure:

- Valid JSON format
- Working logos
- Correct categories
- No duplicate entries

## Support

Found a broken stream?

- Open an Issue
- Submit a Pull Request

## Disclaimer

This repository does not host, store, or broadcast any media content.

All channel names, logos, trademarks, and stream rights belong to their respective owners.

## DMCA

Copyright owners may request content review or removal through GitHub Issues or repository contact methods.

## License

MIT License

[![Visitors](https://visitor-badge.laobi.icu/badge?page_id=istiakrahman15.iptv-api)](https://github.com/istiakrahman15/iptv-api)
![Stars](https://img.shields.io/github/stars/istiakrahman15/iptv-api)
![Forks](https://img.shields.io/github/forks/istiakrahman15/iptv-api)
