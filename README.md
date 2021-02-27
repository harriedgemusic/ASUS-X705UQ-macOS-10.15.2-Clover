![Screenshot 2021-02-27 at 05 31 02](https://user-images.githubusercontent.com/13720261/109373006-8de9e480-78bd-11eb-8b81-3ae4b96192ef.png)
# ASUS-X705UQ-macOS-10.15.2-Clover
EFI folder for running macOS Catalina on ASUS Vivibook Pro 17, N705U(V/UQ/X705U)

# Install

1. Make EFI partition on flash drive, copy this EFI folder to.
2. Boot from flash drive
3. Install macOS

# For Wi-Fi:

1. Make /-mount of filesystem as RW: sudo mount -uw /
2. Run KextUtility, drag IO80211Family.kext to window
3. Copy ATH9KInjector.kext to EFI/Clover/Kexts/Other
4. Reboot!

[Uploading Screenshot 2021-02-27 at 05.31.02.png…]()
![Screenshot 2021-02-27 at 05 31 14](https://user-images.githubusercontent.com/13720261/109372921-2d5aa780-78bd-11eb-9f02-b6980ccacf37.png)
![Screenshot 2021-02-27 at 05 31 57](https://user-images.githubusercontent.com/13720261/109372923-2f246b00-78bd-11eb-8baa-0b8f9e559124.png)
