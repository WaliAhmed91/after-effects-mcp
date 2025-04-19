# 🎨 After Effects MCP Server

![GitHub release](https://img.shields.io/github/release/WaliAhmed91/after-effects-mcp.svg)
![Node.js](https://img.shields.io/badge/Node.js-v14.17.0-green.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-v ES6-blue.svg)

Welcome to the **After Effects MCP Server** repository! This project enables remote control of Adobe After Effects using the Model Context Protocol (MCP) via ExtendScript. You can manipulate compositions, text, shapes, solids, and properties seamlessly.

## 🚀 Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Releases](#releases)

## 🌟 Features

- **Remote Control**: Control various aspects of Adobe After Effects remotely.
- **Model Context Protocol**: Utilizes MCP for effective communication.
- **ExtendScript Integration**: Leverage ExtendScript for scripting capabilities.
- **Automation**: Automate tasks in After Effects to save time and improve efficiency.
- **Supports Multiple Properties**: Work with compositions, text, shapes, solids, and properties.
- **Cross-Platform**: Compatible with Windows and macOS.

## 📦 Installation

To get started, clone the repository and install the necessary dependencies.

```bash
git clone https://github.com/WaliAhmed91/after-effects-mcp.git
cd after-effects-mcp
npm install
```

## 🛠️ Usage

To use the MCP Server, follow these steps:

1. **Start the Server**: Run the following command to start the server.

   ```bash
   node server.js
   ```

2. **Connect to After Effects**: Use ExtendScript to connect to the MCP server. Here’s a simple example:

   ```javascript
   var server = new MCPServer();
   server.connect();
   ```

3. **Control Compositions**: Now you can control various properties of your After Effects project. For example, to change the text of a layer:

   ```javascript
   var layer = app.project.activeItem.layer(1);
   layer.text.sourceText.setValue("New Text");
   ```

## 🤝 Contributing

We welcome contributions! If you have suggestions or improvements, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/YourFeature`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/YourFeature`.
5. Open a pull request.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📧 Contact

For any questions or suggestions, feel free to reach out:

- **Wali Ahmed**: [@WaliAhmed91](https://twitter.com/WaliAhmed91)
- **Email**: wali.ahmed@example.com

## 📦 Releases

To download the latest release, visit the [Releases](https://github.com/WaliAhmed91/after-effects-mcp/releases) section. Make sure to download the appropriate file and execute it to get started with the MCP Server.

## 🌐 Topics

This repository covers various topics including:

- After Effects
- Automation
- JavaScript
- Model Context Protocol
- Motion Graphics
- Remote Control
- Node.js
- TypeScript
- Video Editing

## 🎉 Conclusion

Thank you for checking out the After Effects MCP Server! We hope this tool helps you streamline your workflow in Adobe After Effects. For more information, updates, and community discussions, please visit the [Releases](https://github.com/WaliAhmed91/after-effects-mcp/releases) section.

---

Feel free to explore the code, contribute, and share your experiences. Happy animating! 🎬