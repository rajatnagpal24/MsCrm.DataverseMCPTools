# Dataverse MCP Tools for XrmToolBox

![Dataverse MCP Tools](https://img.shields.io/badge/XrmToolBox-Plugin-blue) ![.NET Framework 4.8](https://img.shields.io/badge/.NET%20Framework-4.8-purple) ![License](https://img.shields.io/badge/license-MIT-green)

A powerful XrmToolBox plugin that enables you to test and interact with Dataverse Model Context Protocol (MCP) tools directly from within XrmToolBox.

## 📋 Overview

**Dataverse MCP Tools** is an XrmToolBox plugin designed to help developers and administrators work with the Model Context Protocol (MCP) in Microsoft Dataverse environments. This tool provides an intuitive interface to discover, test, and debug MCP tools without leaving XrmToolBox.

### What is MCP?

The Model Context Protocol (MCP) is a standardized protocol for AI assistants and tools to interact with external systems. Dataverse's MCP implementation allows AI agents to perform operations on your Dataverse environment through a structured, type-safe interface.

## ✨ Features

- **🔍 Discover MCP Tools**: Automatically load and list all available MCP tools from your connected Dataverse environment
- **📝 Interactive Testing**: Test MCP tool invocations with a user-friendly JSON editor
- **🎯 Smart Schema Generation**: Automatically generate sample JSON input based on tool schemas
- **📊 Response Visualization**: View formatted responses with pretty-printed JSON output
- **🔐 OAuth Integration**: Seamlessly uses your XrmToolBox connection credentials
- **💡 Helpful Hints**: Inline comments show required/optional parameters and descriptions
- **⚡ Async Operations**: Non-blocking operations ensure smooth UI experience

## 🚀 Installation

### From XrmToolBox Tool Library (Recommended)

1. Open **XrmToolBox**
2. Click on **Tool Library** (or press `F7`)
3. Search for **"Dataverse MCP Tools"**
4. Click **Install**
5. Restart XrmToolBox

### Manual Installation

1. Download the latest release from the [Releases page](https://github.com/rajatnagpal24/MsCrm.DataverseMCPTools/releases)
2. Extract the ZIP file
3. Copy the `DataverseMcpTools` folder to your XrmToolBox `Plugins` directory
4. Restart XrmToolBox

## 📖 Usage

### Getting Started

1. **Connect to Your Environment**
   - Open XrmToolBox
   - Connect to your Dataverse environment using OAuth authentication
   - Navigate to **Dataverse MCP Tools** from the tools menu

2. **Load MCP Tools**
   - Click the **"Load Tools"** button in the toolbar
   - The plugin will discover all available MCP tools from your environment
   - Select a tool from the dropdown to begin testing

3. **Configure Input Parameters**
   - The JSON editor will auto-populate with a sample schema
   - Edit the values to match your test scenario
   - Comments indicate which fields are required vs optional

4. **Execute the Tool**
   - Click the **"Execute Tool"** button
   - View the response in the output panel
   - Responses are automatically formatted for readability


## 🔧 Requirements

- **XrmToolBox**: Version 1.2025.7.71 or higher
- **.NET Framework**: 4.8 or higher
- **Dataverse Environment**: With MCP enabled
- **Authentication**: OAuth authentication required

## 🏗️ Technical Details

### Built With

- .NET Framework 4.8
- XrmToolBox SDK
- Microsoft.Xrm.Sdk
- Newtonsoft.Json
- System.Text.Json

### Key Components

- **McpClient**: HTTP client for MCP protocol communication
- **Model Classes**: Strongly-typed models for MCP requests/responses
- **Smart JSON Editor**: Auto-generates schemas with inline documentation
- **OAuth Token Management**: Seamless integration with XrmToolBox credentials


## 📝 Changelog

### Version 1.0.3.0 (Initial Release)
- ✅ List available MCP tools from Dataverse
- ✅ Execute MCP tools with custom parameters
- ✅ Auto-generate JSON schemas from tool definitions
- ✅ Format and display tool responses
- ✅ OAuth authentication support
- ✅ Error handling and user feedback


## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Rajat Nagpal**

- GitHub: [@rajatnagpal24](https://github.com/rajatnagpal24)

## 🙏 Acknowledgments

- Built for the [XrmToolBox](https://www.xrmtoolbox.com/) platform
- Thanks to the XrmToolBox community for their excellent documentation
- Microsoft Dataverse team for MCP implementation

## 📞 Support

If you encounter any issues or have questions:

- 🐛 [Report a Bug](https://github.com/rajatnagpal24/MsCrmTools-DataverseMCPTools/issues)
- 💡 [Request a Feature](https://github.com/rajatnagpal24/MsCrmTools-DataverseMCPTools/issues)
- 📖 [View Documentation](https://github.com/rajatnagpal24/MsCrmTools-DataverseMCPTools/wiki)


---

**Made with ❤️ for the Dataverse community**

⭐ If you find this tool helpful, please consider giving it a star on GitHub!
