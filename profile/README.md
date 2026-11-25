<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="readme/hero-dark.svg">
    <img src="readme/hero-light.svg" alt="vibecook: ingredients for the app you're cooking. Four projects: truffle, ghosttea, mille and flux." width="100%">
  </picture>
</p>

<p align="center">
  <b>Three libraries and an app, all open source.</b><br>
  A mesh network, a terminal and a file tree for the app you're building.<br>
  And flux, a media server built on two of them.
</p>

<br>

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/vibecook-dev/truffle"><picture><source media="(prefers-color-scheme: dark)" srcset="readme/plate-truffle-dark.svg"><img src="readme/plate-truffle-light.svg" alt="truffle" width="100%"></picture></a>
      <a href="https://github.com/vibecook-dev/truffle"><picture><source media="(prefers-color-scheme: dark)" srcset="readme/shot-truffle-dark.png"><img src="readme/shot-truffle-light.png" alt="truffle's benchmark app during a TCP throughput run between two devices" width="100%"></picture></a>
      Direct connections between your own devices, on top of Tailscale. TCP, UDP, QUIC, WebSocket and HTTP, with no server to run.<br>
      <sub><a href="https://github.com/vibecook-dev/truffle"><b>Repository</b></a>&nbsp;&nbsp;·&nbsp; <a href="https://vibecook-dev.github.io/truffle/">Docs</a>&nbsp;&nbsp;·&nbsp; <a href="https://www.npmjs.com/package/@vibecook/truffle">npm</a>&nbsp;&nbsp;·&nbsp; <a href="https://crates.io/crates/truffle">crates.io</a></sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/vibecook-dev/ghosttea"><picture><source media="(prefers-color-scheme: dark)" srcset="readme/plate-ghosttea-dark.svg"><img src="readme/plate-ghosttea-light.svg" alt="ghosttea" width="100%"></picture></a>
      <a href="https://github.com/vibecook-dev/ghosttea"><picture><source media="(prefers-color-scheme: dark)" srcset="readme/shot-ghosttea-dark.png"><img src="readme/shot-ghosttea-light.png" alt="The ghosttea demo app with three split terminal panes" width="100%"></picture></a>
      A terminal to embed in your app. Ghostty's terminal core, a Rust daemon, and GPU renderers for Electron and iOS.<br>
      <sub><a href="https://github.com/vibecook-dev/ghosttea"><b>Repository</b></a>&nbsp;&nbsp;·&nbsp; <a href="https://vibecook-dev.github.io/ghosttea/">Website</a>&nbsp;&nbsp;·&nbsp; <a href="https://www.npmjs.com/package/@vibecook/ghosttea-react">npm</a>&nbsp;&nbsp;·&nbsp; <a href="https://crates.io/crates/ghosttea">crates.io</a></sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/vibecook-dev/mille"><picture><source media="(prefers-color-scheme: dark)" srcset="readme/plate-mille-dark.svg"><img src="readme/plate-mille-light.svg" alt="mille" width="100%"></picture></a>
      <a href="https://github.com/vibecook-dev/mille"><picture><source media="(prefers-color-scheme: dark)" srcset="readme/shot-mille-dark.png"><img src="readme/shot-mille-light.png" alt="mille's file tree beside a file preview, with git status letters" width="100%"></picture></a>
      A file explorer for your Electron app. A Rust engine walks, watches and searches the folder, and React draws only the rows on screen.<br>
      <sub><a href="https://github.com/vibecook-dev/mille"><b>Repository</b></a>&nbsp;&nbsp;·&nbsp; <a href="https://vibecook-dev.github.io/mille/">Website</a>&nbsp;&nbsp;·&nbsp; <a href="https://www.npmjs.com/package/@vibecook/mille">npm</a></sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/vibecook-dev/flux"><picture><source media="(prefers-color-scheme: dark)" srcset="readme/plate-flux-dark.svg"><img src="readme/plate-flux-light.svg" alt="flux" width="100%"></picture></a>
      <a href="https://github.com/vibecook-dev/flux"><picture><source media="(prefers-color-scheme: dark)" srcset="readme/shot-flux-dark.jpg"><img src="readme/shot-flux-light.jpg" alt="flux's Wall lens: a grid of film posters" width="100%"></picture></a>
      A fast, private media server for the films and shows you own. Written in Rust, and in alpha.<br>
      <sub><a href="https://github.com/vibecook-dev/flux"><b>Repository</b></a>&nbsp;&nbsp;·&nbsp; <a href="https://vibecook-dev.github.io/flux/">Website</a>&nbsp;&nbsp;·&nbsp; <a href="https://github.com/vibecook-dev/flux/releases">Download</a></sub>
    </td>
  </tr>
</table>

<p align="center"><sub>Screenshots, not mocks: truffle's benchmark app on its demo data, ghosttea's demo app, mille's <code>FileTree</code>, and flux's Wall lens.</sub></p>

## How they fit

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="readme/fit-dark.svg">
    <img src="readme/fit-light.svg" alt="ghosttea, mille and flux each connect down to truffle, which gives direct connections between your own devices on Tailscale. ghosttea uses it for shared sessions, mille for remote workspaces, and flux for its own tailnet node. flux also scans your library with mille." width="100%">
  </picture>
</p>

truffle is the network under the other three. You can use any one of them without the rest.

All four are MIT licensed and still 0.x, so their APIs can change between releases.

<br>

<p align="center">
  <a href="https://github.com/jamesyong-42">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="readme/james-yong-dark.svg">
      <img src="readme/james-yong-light.svg" alt="James Yong" height="14">
    </picture>
  </a>
</p>

<p align="center">
  <sub>vibecook is made by <a href="https://github.com/jamesyong-42">James Yong</a>.</sub>
</p>
