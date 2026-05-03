The documentation for translation is [here](https://github.com/vcmi/vcmi/blob/develop/docs/translators/Translations.md).

Information for dubbing are [here](https://github.com/vcmi-mods/empty-translation?tab=readme-ov-file#dubbing)

Please create a new issue [here](https://github.com/vcmi-mods/latvian-translation/issues/new) for any mistake.

# How to play to Heroes of Might and Magic III in Latvian

1. Buy _Heroes of Might and Magic III Complete Edition_ on GOG (not the HD version)
1. Install the game
1. Download VCMI (free)
1. Install VCMI
1. When installing VCMI, specify the location of the base game's `Data`, `MP3`, and `Maps` folders.
1. Set the language to _Latvian_
1. Install the _Tulkojums latviešu valodā_ mod
1. Launch the game

# Kā spēlēt Heroes of Might and Magic III latviešu valodā

1. Iegādājieties _Heroes of Might and Magic III Complete Edition_ vietnē GOG (nevis HD versiju)
1. Instalējiet spēli
1. Lejupielādējiet VCMI (bez maksas)
1. Instalējiet VCMI
1. Instalējot VCMI, norādiet bāzes spēles mapju `Data`, `MP3` un `Maps` atrašanās vietu.
1. Iestatiet valodu uz _Latviešu_
1. Instalējiet _Tulkojums latviešu valodā_ modu
1. Palaidiet spēli

# How to dub

1. Copy a prolog/epilog from [`latvian-translation/content/config/vcmi-latvian/campaigns.json`](https://github.com/vcmi-mods/latvian-translation/tree/vcmi-1.7/mods/AITranslated/Content/config/vcmi-latvian-ai/)
2. Go to [this](https://huggingface.co/spaces/k2-fsa/OmniVoice) OmniVoice TTS
3. Click on _Clone voice_
4. Paste the speech text
5. Select _Latvian_
4. Upload a voice
3. Paste the reference text
6. Click on _Generate_
7. Download the audio file
8. Retrieve the property for the speech in the [`latvian-translation/content/config/vcmi-latvian/campaigns.json`](https://github.com/vcmi-mods/latvian-translation/tree/vcmi-1.7/mods/AITranslated/Content/config/vcmi-latvian-ai/) file
9. Retrieve the related audio filename in the [empty-translation mod](https://github.com/vcmi-mods/empty-translation?tab=readme-ov-file#dubbing)
10. Rename the audio file
11. Move the file to `latvian-translation/content/sounds/` folder

# How to contribute

1. Go to the GitHub mod page: https://github.com/vcmi-mods/latvian-translation
2. Fork the repository by clicking on the "Fork" button
3. Browse to the file you want to change
4. Click on the pencil button to edit the file
5. Edit the file
6. Click on the "Commit changes..." button
7. Click on the "Pull request" tab
8. Click on the "Create Pull Request" button
9. Write a description and create the PR (Pull Request)
