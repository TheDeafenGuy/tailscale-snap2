# tailscale-snap2

<h1>October 2025 Update</h1>
<h2>I have just noticed now that there is a snap by Canonical for Tailscale, so I now see no purpose in further maintaining this snap. This is mostly because this snap has such an unfortunate name and is a hassle to use (having to issue tailscale-snap2 to use commands). The initial purpose of this snap was to provide Tailscale through a snap, since the snap "Tailscale" at the time had not been maintained for a long time. Since there is now a semi-official snap, I see no reason in providing this snap anymore. I cannot recommend the use of this snap anymore.</h2>
<h2>I have made the snap private and have set this repository to read-only.</h2>

A Snap port of Tailscale.

This is a port of Tailscale to the Snap store. The snapcraft.yaml is based on the one by sergiusens, found here: https://github.com/sergiusens/tailscale 

This project also was originally started with the goal of getting Tailscale working on Ubuntu Touch (now maintained by the Ubports Foundation) without having to disable read only mode on "/" to install Tailscale, and instead install Tailscale through Snap, which can be added by installing an app to enable Snap support. It seems that snaps added using this support do persist even with OTA updates, which means that if the device recieves an OTA update, tailscale-snap2 and its settings will persist.

I also used AI to fix some of the snapcraft.yaml, because I am inexperienced with building Snaps.
Updates to the snapcraft.yaml for newer versions of Tailscale should not be needed because this version of Tailscale has a built-in updater, so theoretically, it should be fine.
The version of Tailscale this snap comes with is usually the latest version, as I try my best to update the snap to the newer version of tailscale as soon as possible.
To install, invoke the command "sudo snap install --edge tailscale-snap2 --devmode"

Note: To use the Tailscale CLI, you must invoke the command "tailscale-snap2" instead of just "tailscale"

<a href="https://snapcraft.io/tailscale-snap2">
  <img alt="tailscale-snap2" src="https://snapcraft.io/tailscale-snap2/badge.svg" />
</a>

<h1>Updating</h1>

I usually try to update the snap to the latest version of Tailscale within one day of an update to Tailscale itself.

Also note that I may not be able to help/fix all issues, considering how limited ChatGPT is in actually helping with the task it is given. For instance, the snap is not confined right now because I am unable ot figure out how to do that without sacrificing usability. I created this in the first place because I just wanted tailscale to work. 
