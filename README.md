# NuclearBot API

Twitch chatbot with plugin and commands, extensive GUI.
This is a public API to make plugins for NuclearBot.

The API follows a different versioning than the original repository.

Versions are called `a.b.c`:
* if only `c` changes, the release contains tweaks with backwards-compatible or no changes to the actual API;
* if `b` changes, the release is a minor version, which may or may not contain big changes, but remains backwards-compatible, possibly deprecated, often a change of implementation;
* if `a` changes, the release is a major version, which is not guaranteed to be fully backwards-compatible, usually an API redesign.

For further information, please use the Wiki: https://github.com/NuclearCoder/nuclear-bot/wiki
