# NodeByte Translations

Community translations for [NodeByte Hosting](https://nodebyte.host).

[![Crowdin](https://badges.crowdin.net/nodebyte/localized.svg)](https://crowdin.com/project/nodebyte)

## Contributing Translations

### Via Crowdin (Recommended)
The easiest way to contribute translations is through our Crowdin project:
* **[Translate on Crowdin](https://crowdin.com/project/nodebyte)**


## Translation Guidelines

1. **Keep placeholders intact** - Variables like `{count}` or `{name}` should not be translated
2. **Maintain formatting** - Keep the same JSON structure
3. **Use native expressions** - Translate naturally, don't translate word-for-word
4. **Use indexed objects for arrays** - Use `{"0": "item", "1": "item"}` not `["item", "item"]`

## Supported Languages

| Language | Code | Language | Code |
|----------|------|----------|------|
| 🇬🇧 English | `en` | 🇮🇹 Italiano | `it-IT` |
| 🇿🇦 Afrikaans | `af-ZA` | 🇯🇵 日本語 | `ja-JP` |
| 🇸🇦 العربية | `ar-SA` | 🇰🇷 한국어 | `ko-KR` |
| 🇪🇸 Català | `ca-ES` | 🇳🇱 Nederlands | `nl-NL` |
| 🇨🇿 Čeština | `cs-CZ` | 🇳🇴 Norsk | `no-NO` |
| 🇩🇰 Dansk | `da-DK` | 🇵🇱 Polski | `pl-PL` |
| 🇩🇪 Deutsch | `de-DE` | 🇧🇷 Português (Brasil) | `pt-BR` |
| 🇬🇷 Ελληνικά | `el-GR` | 🇵🇹 Português | `pt-PT` |
| 🇪🇸 Español | `es-ES` | 🇷🇴 Română | `ro-RO` |
| 🇫🇮 Suomi | `fi-FI` | 🇷🇺 Русский | `ru-RU` |
| 🇫🇷 Français | `fr-FR` | 🇷🇸 Српски | `sr-SP` |
| 🇮🇱 עברית | `he-IL` | 🇸🇪 Svenska | `sv-SE` |
| 🇭🇺 Magyar | `hu-HU` | 🇹🇷 Türkçe | `tr-TR` |
| 🇺🇦 Українська | `uk-UA` | 🇻🇳 Tiếng Việt | `vi-VN` |
| 🇨🇳 简体中文 | `zh-CN` | 🇹🇼 繁體中文 | `zh-TW` |

## How It Works

1. **Source files**: `templates/en/*.json` are modular English sources maintained by the NodeByte team and community. 
2. **Crowdin sync**: When changes are pushed, Crowdin detects new/updated strings in all template files.
3. **Community translation**: Translators contribute via Crowdin's web interface
4. **Auto PR**: Crowdin automatically creates PRs with approved translations to `messages/` (with modular structure per locale)

## Requesting a New Language

If your language isn't listed you can request it here:
- [Open an issue](https://github.com/NodeByteHosting/translations/issues)
- [Join our Discord](https://discord.gg/nodebyte)!

## License

Our translations are licensed under the [MIT License](../LICENSE) - feel free to use them in your own projects!
