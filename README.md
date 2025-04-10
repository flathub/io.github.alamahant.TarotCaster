# TarotCaster

An AI-powered tarot reading application built with Qt that combines traditional tarot wisdom with modern artificial intelligence.

## Features

- **Multiple Tarot Decks Support**: Includes the classic Rider-Waite deck with support for adding your own custom decks
- **Various Spread Types**: Choose from multiple layouts including:
  - 1-card draw
  - 3-card spread
  - Celtic Cross spread
  - Horseshoe spread
  - More spreads coming soon!
- **AI-Generated Readings**: Powered by Mistral AI for insightful and personalized card interpretations
- **Traditional Card Meanings**: Built-in traditional interpretations for all cards
- **Show Full Deck Feature**: Browse and explore the entire deck of cards
- **Enhanced Randomization**: Shuffle button gathers system entropy for truly random card selection
- **Save/Load Functionality**: Save your readings to revisit them later
- **Intuitive Interface**: Clean, user-friendly design suitable for both beginners and experienced readers

## Installation

### Flatpak

```bash
flatpak install io.github.alamahant.TarotCaster
```

### From Source

For detailed build instructions, please visit the [main project repository](https://github.com/alamahant/TarotCaster).

## Using AI Interpretations

TarotCaster uses Mistral AI to generate personalized card interpretations. To use this feature:

1. Register for a free Mistral AI API key at [https://mistral.ai/](https://mistral.ai/)
2. Enter your API key in the application settings
3. Select "Get Reading" when viewing spread

The free tier of Mistral AI provides sufficient requests for personal tarot reading use.

## Adding Custom Decks

You can add your own tarot decks to TarotCaster:

1. Create a folder with your deck name in the decks directory
2. Name your card images according to the required convention
3. Restart the application to see your new deck

For detailed instructions on custom deck creation, please visit the [main project repository](https://github.com/alamahant/TarotCaster).

## Dependencies

### For Flatpak Users
No additional dependencies required - everything is included in the Flatpak package.

## Credits and Licensing

### Tarot Deck Artwork
- Original Rider-Waite Tarot deck artwork by Pamela Colman Smith under the direction of Arthur Edward Waite
- Images sourced from [Wikimedia Commons](https://commons.wikimedia.org/wiki/Category:Rider-Waite_tarot_deck)
- These images are in the public domain in the United States, the EU and globally because their copyright has expired

### Tarot Interpretations
- Traditional card meanings adapted from [Corpora Project](https://github.com/dariusk/corpora/blob/master/data/divination/tarot_interpretations.json)
- AI interpretations powered by Mistral AI

## License
GPL-3.0 - See the LICENSE file for details

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
