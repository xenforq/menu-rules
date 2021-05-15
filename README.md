<!-- HEADER -->
<a href="https://williamhallin.com"><img src="https://raw.githubusercontent.com/whallin/whallin/master/img_header.png" alt="A banner showing the William Hallin logo."></a>

<!-- SHIELDS -->
<p align=center>
  <a href="https://github.com/whallin/menu-rules/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/whallin/menu-rules.svg?style=for-the-badge&color=brightgreen" alt="Shield showing total amount of contributors.">
  </a>
  <img src="https://badges.pufler.dev/visits/whallin/menu-rules?style=for-the-badge">
</p>

<!-- ABOUT -->
# 🎮 menu-rules
menu-rules was originally created and developed by [@XARIUS](https://forums.alliedmods.net/showthread.php?p=639481), but has now turned into a more inactive resource that sadly isn't being maintained. Hence, why this repository exists. We're here to make sure development of this incredibly useful plugin remains active and fixes are made to existing issues. 

menu-rules lets you display a menu filled with your rules to your users, to make sure they are aware of your server's terms. Kick them from your server if they fail to agree to your rules either by manually declining or not answering in time. 

<!-- CVARS -->
## 🚀 Cvars
All commands can be used with ! Or / in the chat.
- ``sm_showrules_version``			: Shows the current version of the plugin.
- ``sm_showrules_enabled``			: 1 = Enables the plugin. 0 = Disables the plugin. (Default: 1)
- ``sm_showrules_joinsound``		: Sound file to play to connecting clients.  Relative to the sound/ folder.  Example: 'welcome.mp3' or 'mysounds/welcome.mp3'
- ``sm_showrules_menutime`` 		: Time to display rules menu to client before dissolving (and kicking them). (Default: 120 seconds)
- ``sm_showrules_showonjoin``		: Display Rules menu to clients automatically upon joining the server. 1 = Enabled. 0 = Disabled. (Default: 1)
- ``sm_showrules_showtoadmins``		: On join, display menu to admins. 1 = Enabled. 0 = Disabled. (Default: 0)
- ``sm_showrules_displayattempts``	: Number of times to attempt to display the rules' menu. (3 second intervals) (Default: 20 times)
- ``sm_showrules_failurekick``		: Kick the client if the rules cannot be displayed after defined display attempts. 1 = Enabled. 0 = Disabled. (Default: 1)
- ``sm_showrules_showmenuoptions``	: Shows agree/disagree options instead of a single option to close the rules' menu. 1 = Enabled. 0 = Disabled. (Default: 1)
- ``sm_showrules_expiration``		: Number of hours before the previous terms' agreement expires. (Default: 24 hours)
- ``sm_showrules_showrules``		: Show the rule to a certain player. ``sm_showrules <#userid|name>``

<!-- COMPILE -->
## ▶️ Compile yourself
Make compiling easy with [Spider (https://spider.limetech.io/)](https://spider.limetech.io/) or follow [this guide](https://wiki.alliedmods.net/Compiling_SourceMod_Plugins) written on the AlliedModders wiki.

<!-- CONTRIBUTORS -->
## 🤝 Contributors
<a href="https://github.com/whallin/menu-rules/graphs/contributors"><img src="https://contrib.rocks/image?repo=whallin/menu-rules" /></a>

<!-- LICENSE -->
## ⚖️ License
Copyright © 2021 [William Hallin Multimedia &lt;me@williamhallin.com&gt; (https://www.williamhallin.com)](https://www.williamhallin.com)

whallin/menu-rules is licensed under the ``GPL-3.0`` license. Read more about its meaning and effects [here](https://github.com/whallin/menu-rules/blob/main/LICENSE).
