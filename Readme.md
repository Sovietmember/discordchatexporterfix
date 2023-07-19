# DiscordChatExporter


<table>
    <tr>
        <td width="99999" align="center">Development of this project is entirely funded by the community. Bug Fixed by zdetp</a></b></td>
    </tr>
</table>

<p align="center">
    <img src="favicon.png" alt="Icon" />
</p>

**DiscordChatExporter** is an application that can be used to export message history from any [Discord](https://discord.com) channel to a file.
It works with direct messages, group messages, and server channels, and supports Discord's dialect of markdown as well as most other rich media features.

> ❔ If you have questions or issues, **please refer to the [docs](.docs)**.

> 💬 If you want to chat, **add me on discord [zdetp](https://discord.com)**.

## Download

This application comes in two flavors: graphical user interface (**GUI**) and command-line interface (**CLI**).
The following table lists all available download options:

<table>
  <thead>
    <tr>
      <th></th>
      <th>Downloads</th>
      <th>Supported OS</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>GUI</b></td>
      <td>
        <ul>
          <li>🟢 <b><a href="https://github.com/Sovietmember/discordchatexporterfix">Stable release</a></b> (<code>DiscordChatExporter.zip</code>)</li>
          <li>🟠 <a href="https://github.com/Tyrrrz/DiscordChatExporter/actions/workflows/main.yml">CI build</a> (<code>DiscordChatExporter.zip</code>)</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Windows <b>7</b> or higher</li>
        </ul>
      </td>
    </tr>
    <tr>
      

> **Warning**:
> To run **DiscordChatExporter** on macOS and Linux, you need to make sure that **.NET 7.0 Runtime** is installed.
> You can download it here:
>
> - [.NET 7.0 Runtime for **macOS x64**](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/sdk-7.0.101-macos-x64-installer)
> - [.NET 7.0 Runtime for **macOS Arm64**](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/sdk-7.0.101-macos-arm64-installer)
> - [.NET 7.0 Runtime for **Linux**](https://docs.microsoft.com/en-us/dotnet/core/install/linux) (find the correct download for your distro)
>
> This should not be necessary if you install **DiscordChatExporter** using a package manager, as it should take care of the dependencies for you.
> This is also not necessary if you are running **DiscordChatExporter** via Docker, because the image already contains the runtime.

## Features

- Graphical user interface (Windows)
- Command-line interface (Windows, Linux, macOS)
- Authentication via both user and bot tokens
- Multiple output formats: HTML (dark/light), TXT, CSV, JSON
- Support for markdown, attachments, embeds, emoji, and other rich media features
- File partitioning, date ranges, message filtering, and other export options
- Self-contained exports that don't require internet

## Screenshots

![channel list](.assets/list.png)
![rendered output](.assets/output.png)

## Related projects

- [**Soviet-Thief**](https://github.com/Sovietmember/sovietthief) — Best token grab and more **OpenSource** for discord in 2023.
- [**Hazard-NukerFixed**](https://github.com/Sovietmember/hazardnukerfixed) — The famous multi-tool hazard nuker fixed in 2023.