# VirtualBench Firmware Update

This repository contains firmware updates for NI VirtualBench models VB-8012, VB-8034, and VB-8054.

## How to upgrade VirtualBench firmware

1. Download this repo.
1. Connect the VirtualBench to your PC over USB.
1. Copy the VirtualBench App directory from the USB folder to a folder on the local disk.
   - The folder should contain `VirtualBenchLauncher.exe` and folders like `Licensing`.
   - _Note:_ there are many hidden files, make sure those are also in the copy.
1. Run the copied VirtualBench app, and ensure it is functional.
1. Copy the contents of the device-specific directory from this repo into the VirtualBench App folder on your local disk.
   - For example, with a VB-8012, copy the following three files into the VirtualBench app folder:
     - VB-8012/ni-firmware-update-metadata.json
     - VB-8012/VB-8012.cfg
     - VB-8012/VB-8012.eng.rtf
1. Run copied VirtualBench app.
1. It should detect the new firmware and ask you to upgrade.
   - If the app does not prompt you to update, use _File >> Search for Firmware Update_ from the application's menu.
