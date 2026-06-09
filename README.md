# WorldCup IPTV

A curated IPTV playlist in JSON format for media player applications, IPTV apps, and personal testing.

## Features

- JSON-based channel database
- Organized by category
- Channel logo support
- M3U8 stream URL support
- Easy integration with web, Android, and IPTV applications

## JSON Structure

```json
{
  "name": "Channel Name",
  "logo": "https://example.com/logo.png",
  "stream_url": "https://example.com/playlist.m3u8",
  "category": "Sports"
}
```

## Categories

- Sports
- Entertainment
- Movies
- Music
- Cartoon
- Bangladesh
- News
- Documentary

## How To Use

### JavaScript

```javascript
fetch("worldcup-iptv.json")
  .then(res => res.json())
  .then(data => {
    console.log(data);
  });
```

### Android

1. Fetch JSON file
2. Parse using Gson/Moshi
3. Load stream_url into ExoPlayer

### IPTV Web Player

```javascript
player.load(channel.stream_url);
```

## API Response

The repository returns an array of channel objects:

```json
[
  {
    "name": "Channel Name",
    "logo": "Logo URL",
    "stream_url": "Stream URL",
    "category": "Sports"
  }
]
```

## Contributing

Pull Requests are welcome.

Before submitting:

- Verify stream availability
- Verify logo URLs
- Keep category naming consistent
- Remove duplicate channels

## Support

If you find broken streams:

- Open an Issue
- Submit a Pull Request
- Report incorrect channel information

## Disclaimer

This repository does not host any video content.

All streams, channel names, trademarks, and logos belong to their respective owners.

The repository only provides references to publicly accessible streams.

## DMCA

If you are a copyright owner and believe that any content infringes your rights, please open an issue or submit a DMCA request.

Reported content will be reviewed and removed when appropriate.

## License

MIT License
