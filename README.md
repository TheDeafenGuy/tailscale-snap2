# tailscale-snap2
A Snap port of Tailscale.

This is a port of Tailscale to the Snap store. The snapcraft.yaml is based on the one by sergiusens, found here: https://github.com/sergiusens/tailscale 

This project also was originally started with the goal of getting Tailscale working on Ubuntu Touch (now maintained by the Ubports Foundation) without having to disable read only mode on "/" to install Tailscale, and instead install Tailscale through Snap, which can be added by installing an app to enable Snap support.

I also used AI to fix some of the snapcraft.yaml, because I am inexperienced with building Snaps.
Updates to the version of tailscale should not be needed because this version of Tailscale has a built-in updater, so theoretically, it should be fine.
The version of Tailscale this snap comes with is 1.58.2, which is much newer compared to the older snap by seriusens, which has 1.22.1.
To install, invoke the command "sudo snap install --edge tailscale-snap2 --devmode"

Note: To use the Tailscale CLI, you must invoke the command "tailscale-snap2" instead of just "tailscale"

<a href="https://snapcraft.io/tailscale-snap2">
  <img alt="tailscale-snap2" src="https://snapcraft.io/tailscale-snap2/badge.svg" />
</a>
