Download the Correct Tailscale Package
Once you know your DSM version, go to:
👉 Tailscale Synology Packages

Look for the correct .spk package for DSM6 or DSM7 (x86_64) and copy the download link.

1. Stop the Tailscale Package
sudo synopkg stop Tailscale

3. Install the New Version
sudo synopkg install tailscale-x86_64-1.80.0-700080000-dsm7.spk

5. Start Tailscale Again
sudo synopkg start Tailscale

7. Verify the Update
tailscale version

This should work on DSM 7
