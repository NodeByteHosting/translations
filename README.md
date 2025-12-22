# NodeByte Translations

Community translations for [NodeByte Hosting](https://nodebyte.host).

## 🌍 Contributing Translations

### Option 1: Via Crowdin (Recommended)
The easiest way to contribute translations is through our Crowdin project:
**[Translate on Crowdin →](https://crowdin.com/project/nodebyte)**

Crowdin provides a user-friendly interface for translating and automatically syncs approved translations to this repository.

### Option 2: Direct GitHub Contribution
1. Fork this repository
2. Copy `messages/en.json` to `messages/<language-code>.json`
3. Translate all strings in the new file
4. Add your language to `locales.json`
5. Submit a Pull Request

## 📁 Structure

```
├── messages/
│   ├── en.json      # English (source)
│   ├── de.json      # German
│   ├── fr.json      # French
│   ├── es.json      # Spanish
│   └── ...
├── locales.json     # List of available locales
└── README.md
```

## 📝 Translation Guidelines

1. **Keep placeholders intact** - Variables like `{count}` or `{name}` should not be translated
2. **Maintain formatting** - Keep the same JSON structure and indentation
3. **Use native expressions** - Translate naturally, don't translate word-for-word
4. **Test your translations** - Ensure they make sense in context

## 🌐 Available Languages

| Language | Code | Status | Translator |
|----------|------|--------|------------|
| English | `en` | ✅ Complete | NodeByte Team |
| German | `de` | ✅ Complete | Community |
| French | `fr` | ✅ Complete | Community |
| Spanish | `es` | ✅ Complete | Community |

## 🆕 Adding a New Language

1. Create `messages/<code>.json` based on `en.json`
2. Add the locale to `locales.json`:
   ```json
   {
     "locales": ["en", "de", "fr", "es", "YOUR_CODE"],
     "names": {
       "YOUR_CODE": "Language Name"
     },
     "flags": {
       "YOUR_CODE": "🏳️"
     }
   }
   ```
3. Submit a PR with your translations

## 📜 License

Translations are licensed under [MIT License](LICENSE) - feel free to use them in your own projects!

## 💬 Questions?

Join our [Discord](https://discord.gg/wN58bTzzpW) if you have questions about translations.
