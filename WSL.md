# WSL

If you're on a Snapdragon 8** or c** (the much newer models), you have Hyper-V drivers and should just follow the normal WSL2 setup guide

## WSL1 without Virtualization drivers

Microsoft seems to be neglecting a few older snapdragon chipsets regarding WSL; It's horribly painful to get WSL1 up and running without first using WSL2 (impossible for us).

Steps:

1. Open powershell as admin, run `wsl --set-default-version 1`
2. Uninstall all current Ubuntu VMs
3. Download the following: https://cloud-images.ubuntu.com/groovy/current/groovy-server-cloudimg-arm64-wsl.rootfs.tar.gz
4. Rename that file to `rootfs.tar.gz`
5. Run `wsl --import Ubuntu2010 C:\Ubuntu .\rootfs.tar.gz --version 1` (You can replace `C:\Ubuntu` with any directory you'd like Ubuntu to be installed in)
6. Your WSL instance should be good to go.