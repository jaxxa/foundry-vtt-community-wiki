# Foundry Virtual Tabletop Community Wiki Repository

Welcome to the Foundry VTT Community wiki!

This wiki serves as a repository of community-curated information about the Foundry VTT and is 100% community-managed and run. We do not represent Foundry Gaming LLC in any way.

# Official Resources
* [Foundry VTT Website](http://foundryvtt.com/)
* [Gitlab](https://gitlab.com/foundrynet)
* [Gitlab Issue Tracker](https://gitlab.com/foundrynet/foundryvtt/-/boards?milestone_title=No+Milestone&)
* [Patreon](https://www.patreon.com/foundryvtt/overview)
* [Discord](https://discordapp.com/invite/DDBZUDf)

# Community Resources
* [Community Website](https://github.com/foundry-vtt-community/master/wiki)  
* [Community Wiki](https://github.com/foundry-vtt-community/master/wiki)  
* [Community Modules Repo](https://github.com/foundry-vtt-community/modules/)
* [Community Game Systems Repo](https://github.com/foundry-vtt-community/game_systems)


Table of Contents
=================

   * [<a class="internal present" href="/foundry-vtt-community/wiki/wiki/What-is-Foundry-VTT?">What is Foundry VTT?</a>](#what-is-foundry-vtt)
   * [<a class="internal present" href="/foundry-vtt-community/wiki/wiki/FAQ">FAQ</a>](#faq)
   * [<a class="internal present" href="/foundry-vtt-community/wiki/wiki/Getting-Started">Getting Started</a>](#getting-started)
      * [<a class="internal present" href="/foundry-vtt-community/wiki/wiki/Update-Notes">Update Notes</a>](#update-notes)
      * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/Downloading-Foundry-VTT">Downloading Foundry VTT</a>](#downloading-foundry-vtt)
      * [<a class="internal present" href="/foundry-vtt-community/wiki/wiki/Self-hosted-Local">Self-hosted Local</a>](#self-hosted-local)
         * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/Windows">Windows</a>](#windows)
         * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/Linux">Linux</a>](#linux)
         * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/macOS">macOS</a>](#macos)
      * [<a class="internal present" href="/foundry-vtt-community/wiki/wiki/Self-hosted-Cloud">Self-hosted Cloud</a>](#self-hosted-cloud)
         * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/AWS">AWS</a>](#aws)
         * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/Digital-Ocean">Digital Ocean</a>](#digital-ocean)
      * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/Connecting">Connecting</a>](#connecting)
      * [<a class="internal present" href="/foundry-vtt-community/wiki/wiki/Setting-up-Worlds">Setting up Worlds</a>](#setting-up-worlds)
      * [<a class="internal present" href="/foundry-vtt-community/wiki/wiki/Setting-up-Players">Setting up Players</a>](#setting-up-players)
   * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/The-Virtual-Tabletop">The Virtual Tabletop</a>](#the-virtual-tabletop)
      * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/Command-Palette">Command Palette</a>](#command-palette)
         * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/Actor">Actor</a>](#actor)
         * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/Templates">Templates</a>](#templates)
         * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/Tiles">Tiles</a>](#tiles)
         * [<a class="internal present" href="/foundry-vtt-community/wiki/wiki/Walls">Walls</a>](#walls)
         * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/Pins">Pins</a>](#pins)
         * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/Sounds">Sounds</a>](#sounds)
      * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/Sidebar">Sidebar</a>](#sidebar)
         * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/Chat">Chat</a>](#chat)
         * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/Combat-Tracker">Combat Tracker</a>](#combat-tracker)
         * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/Actors">Actors</a>](#actors)
         * [<a class="internal present" href="/foundry-vtt-community/wiki/wiki/Journal">Journal</a>](#journal)
         * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/Playlists">Playlists</a>](#playlists)
         * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/Compendia">Compendia</a>](#compendia)
      * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/Entities">Entities</a>](#entities)
         * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/Actor">Actor</a>](#actor-1)
            * [<a class="internal present" href="/foundry-vtt-community/wiki/wiki/Tokens">Tokens</a>](#tokens)
               * [<a class="internal present" href="/foundry-vtt-community/wiki/wiki/Token-Configuration">Token Configuration</a>](#token-configuration)
               * [<a class="internal present" href="/foundry-vtt-community/wiki/wiki/Token-HUD">Token HUD</a>](#token-hud)
         * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/Combat">Combat</a>](#combat)
   * [<a class="internal present" href="/foundry-vtt-community/wiki/wiki/Modules">Modules</a>](#modules)
      * [<a class="internal present" href="/foundry-vtt-community/wiki/wiki/Modules#finding-modules">Finding Modules</a>](#finding-modules)
      * [<a class="internal present" href="/foundry-vtt-community/wiki/wiki/Modules#installing-modules">Installing Modules</a>](#installing-modules)
      * [<a class="internal present" href="/foundry-vtt-community/wiki/wiki/Modules#developing-modules">Developing Modules</a>](#developing-modules)
   * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/API">API</a>](#api)
      * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/API-Basics">API Basics</a>](#api-basics)
      * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/API-Snippets">API Snippets</a>](#api-snippets)
   * [<a class="internal absent" href="/foundry-vtt-community/wiki/wiki/Community-Game-Systems-&amp;-Modules">Community Game Systems &amp; Modules</a>](#community-game-systems--modules)
      * [<a class="internal present" href="/foundry-vtt-community/wiki/wiki/Community-Game-Systems">Community Game Systems</a>](#community-game-systems)
      * [<a href="https://github.com/foundry-vtt-community/game_systems">Community Game Systems Repository</a>](#community-game-systems-repository)
      * [<a class="internal present" href="/foundry-vtt-community/wiki/wiki/Community-Modules">Community Modules</a>](#community-modules)
      * [<a href="https://github.com/foundry-vtt-community/modules">Community Module Repository</a>](#community-module-repository)
   * [Table of Contents](#table-of-contents)
