# 📺 IPTV Channels JSON Collection

A curated IPTV channels database in JSON format containing Bangla, News, Sports, Entertainment, Kids, Music, Hindi, English, and International TV channels.

## ✨ Features

- 200+ Live TV Channels
- Organized by Categories
- Channel Logo Support
- HLS (.m3u8) Streaming URLs
- JSON Format
- Easy Integration with IPTV Players
- Suitable for Web, Android, Smart TV, and OTT Applications

## 📂 JSON Structure

```json
{
  "name": "Channel Name",
  "logo": "Channel Logo URL",
  "group": "Category",
  "url": "Stream URL"
}
```

## 📺 Available Categories

- Bangla
- News
- Sports
- Hindi
- English
- Kids
- Music
- Indian Bangla
- International
- Entertainment

## 🚀 Usage

```javascript
fetch("channels.json")
  .then(res => res.json())
  .then(data => {
    console.log(data);
  });
```

## ⚠️ Disclaimer

This repository is intended for educational and testing purposes only.

Channel availability, stream quality, and uptime depend on the original stream providers.

The repository owner does not host, store, or rebroadcast any content.

## ❤️ Contributing

Feel free to submit pull requests to improve channel information, logos, or categories.

## ⭐ Support

If you find this project useful, please give it a star.
