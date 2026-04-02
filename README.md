# Synthesizer V Studio 2 Linux Installer

Just a script to install Synth V 2 on linux.

Download the script and run it, make sure you have wine, winetricks and yabridge/yabridgectl installed if you want to try and use the VST plugin.

_Bash_

```bash
bash <(curl -s https://raw.githubusercontent.com/umutondersu/Synthesizer-V-Studio-2-Linux-Installer/refs/heads/main/sv2linuxinstaller.sh)
```

_Fish_ (because I use fish and fish is wierd)

```fish
bash (curl -s https://raw.githubusercontent.com/umutondersu/Synthesizer-V-Studio-2-Linux-Installer/refs/heads/main/sv2linuxinstaller.sh | psub)
```

VST works on new wine with this yabridge: https://github.com/robbert-vdh/yabridge/actions/workflows/build.yml?query=branch%3Anew-wine10-embedding
