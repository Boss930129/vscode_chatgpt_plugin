# ChatGPT VSCode Extension

This is a Visual Studio Code extension for ChatGPT that was built using only ChatGPT and 5 beers.
The `README.md` file for this extension was generated by ChatGPT.

## Install the plugin from the [VSCode MarketPlace](https://marketplace.visualstudio.com/items?itemName=JayBarnes.chatgpt-vscode-plugin)

## Features

- Login with your ChatGPT access token
- Ask ChatGPT any question and supply source code from your current file/selection
- Ask ChatGPT to write tests for a function/file
- Ask ChatGPT to refactor your code and explain the changes
- Ask ChatGPT for help explaining code
- Ask ChatGPT for help troubleshooting code

![image](https://user-images.githubusercontent.com/38425102/206068862-cb8d7e6d-c9ad-434e-b677-b32461e8eeb3.png)

![image](https://user-images.githubusercontent.com/38425102/206068906-2d177606-536d-4fa3-b798-baa7b867abb6.png)


## Usage

To use the extension:
**This package requires a valid session token from ChatGPT to access it's unofficial REST API.**
Open the VS Code Command Palette and Type `ChatGPT: Login`, this will prompt you for your session token.

To get a session token:

1. Go to https://chat.openai.com/chat and log in or sign up.
2. Open dev tools.
3. Open `Application` > `Cookies` (`Storage` > `Cookies` on FireFox)
   
 ![image](https://user-images.githubusercontent.com/38425102/205900045-185c2c41-b4ff-408c-9da6-bbb606ac39c6.png)
   
4. Copy the value for `__Secure-next-auth.session-token` and enter it into the prompt from `ChatGPT: Login`

*Once you're logged in, you can ask ChatGPT any question and supply source code from your current file/selection.*

The commands are:
- `ChatGPT: Query` (will provide a prompt for you to ask a question)
- `ChatGPT: Add tests`
- `ChatGPT: Why is my code broken?`
- `ChatGPT: Explain code`
- `ChatGPT: Refactor`
- `ChatGPT: Reset token` (clears access token if expired or having issues)

## Support
If you need help using this extension, please open an issue on the GitHub repository for this extension.

## Credits
- [ChatGPT](https://chat.openai.com/chat) - The large language model trained by OpenAI that was used to generate this README file
- [chatgpt-api](https://github.com/transitive-bullshit/chatgpt-api/) - The NPM package used to query ChatGPT
- [Yeoman](https://yeoman.io/) - The code generator used to scaffold the extension project
- [VS Code Extension Generator](https://github.com/Microsoft/vscode-generator-code) - The Yeoman generator for creating VS Code extensions
