## df-mcserver 👋

The open sourced code for the creatively titled minecraft server "mcserver"

### Server details

<details>
  <summary>Description of each repository (that will exist)</summary>

  ### DFLobbyServer
  - a minimal lobby server built with Minestom (1.21.8) for low resource usage

  ### DFProxyPlugin
  - a velocity plugin (3.4.0-SNAPSHOT) which manages communication with other plugins, bedrock player support, proxy-wide bans etc.

  ### DFSmpPlus
  - a papermc plugin (1.21.8) built to add various custom content and QoL tweaks to minecraft. Used with LeafMC, so may not work as intended on vanilla PaperMC.

  ### DFJavaResources
  - a minecraft (java) resource pack (1.21.8+) which adds textures and needed changes for DFSmpPlus

  ### DFBedrockResources
  - a minecraft (bedrock) resource pack (1.21.100+) which adds textures and needed changes for DFSmpPlus
</details>

<details>
  <summary>Basic server structure</summary>

  - Proxy (Velocity)
    - Geyser (Velocity)
    - Floodgate (Velocity)
    - ViaVersion (Velocity)
    - DFProxyPlugin
    - Connect the entire network together
   
  - Lobby (Minestom)
    - A place for players to load in their resource pack, and then select what sub-server they want to join
    - Communicates w/ DFProxyPlugin via BungeeCord's MessagingChannel
   
  - SMP (LeafMC)
    - DFSmpPlus
    - The actual SMP
</details>

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
