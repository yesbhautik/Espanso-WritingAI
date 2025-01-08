## Requirements

- [Espanso](https://espanso.org/install/) must be installed
- [PowerShell](https://docs.microsoft.com/en-us/powershell/scripting/install/installing-powershell-on-windows) must be installed for **Windows**
- Active internet connection
- [Groq API key](https://console.groq.com/keys)

## Installation
**Note:** Currently, this package is only support for Windows only.

### Using Package Manager

Coming Soon

### Manually

1. Go to **Espanso Packages** Directory
    For **Windows**: `C:\Users\<Your Username>\AppData\Local\Espanso\Packages`
    For **Linux**: `~/.config/espanso/packages`
    For **macOS**: `~/Library/Application Support/espanso/packages`

2. Clone the repository into your *Espanso Packages* directory.

    ```bash
    git clone https://github.com/yesbhautik/Espanso-WritingAI.git
    ```

## After Installation

- Go to [Groq](https://console.groq.com/keys) and create an API key.
- Open the package.yml file and replace YOUR_API_KEY with your own Groq API key.
- [Optional] Open the package.yml file and replace the trigger key with your own [trigger key](https://ss64.com/ascii.html). Default is `\x11` (Ctrl+Q).
- [Optional] Open the package.yml file and replace the model whichever you want to use [Groq LLM Models](https://console.groq.com/docs/models). Default is `llama-3.3-70b-versatile`.
- [Optional] Open the package.yml file and replace the system prompt with your own prompt. Default is `I want you to act as an English translator, spelling corrector and improver. I will speak to you in any language and you will detect the language, translate it and answer in the corrected and improved version of my text, in English. I want you to replace my simplified A0-level words and sentences with more beautiful and elegant, upper level English professional words and sentences (Do not use very hard to understand language, make it easy to understand). Keep the meaning of the sentence the same.`.
- Save the package.yml file.
- Restart Espanso.
- Copy the text you want to improve.
- Use the trigger key to activate the package.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

**Bhautik Bavadiya**

- GitHub: [@yesbhautik](https://github.com/yesbhautik)

## Version

Current version: 0.1.0

## Support

For support, questions, or feature requests, please open an issue in the repository.

---