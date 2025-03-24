This forked repository provides Chromium Web Browser Stable releases built from the Snap packages to AppImages. This repo also are archival repo for futures and it will give updates for stable versions only. 

# Troubleshoot
AppImages based on Electron require the kernel to be configured in a certain way to allow for its sandboxing to work as intended (specifically, the kernel needs to be allowed to provide “unprivileged namespaces”). Many distributions come with this configured out of the box (like Ubuntu for instance), but some do not (for example Debian), and the AppImage works only with the `--no-sandbox` option. 

For more, visit https://docs.appimage.org/user-guide/troubleshooting/electron-sandboxing.html
