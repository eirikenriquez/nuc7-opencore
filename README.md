# nuc7-opencore EFI

![macOS Big Sur](https://img.shields.io/badge/macOS-Big%20Sur%2011.6.1-blue)
![OpenCore Version](https://img.shields.io/badge/OpenCore-0.7.5-9cf)
![Intel NUC7](https://img.shields.io/badge/Intel%20NUC7-Supported-brightgreen)

This repository contains the EFI folder configuration for running macOS Big Sur (version 11.6.1) on an Intel NUC7 system using OpenCore.

## About

The EFI folder provided here is configured for the Intel NUC7 platform, enabling macOS to be booted on non-Apple hardware. This setup uses OpenCore as the bootloader, providing a way to experience the latest macOS version.

## System Specifications

- **macOS Version:** Big Sur 11.6.1
- **OpenCore Version:** 0.7.5
- **Supported Hardware:** Intel NUC7

## Getting Started

1. Download the EFI folder from this repository.
2. Customize the `config.plist` file in the EFI/OC directory to match your hardware, if necessary.
3. Follow the OpenCore documentation to create a bootable USB drive.
4. Replace the EFI folder on the USB drive with the one provided here.
5. Boot from the USB drive and install macOS.

## Disclaimer

Please note that creating a Hackintosh setup using OpenCore and this EFI configuration might involve complex technical processes and might not be fully compatible with all hardware configurations. Additionally, consider the legal and ethical implications, as Apple's terms of use might apply.

## Contributing

Contributions to improve compatibility and documentation are welcome. Feel free to submit pull requests.

## Credits

This project is made possible with the help of the OpenCore team and the Hackintosh community.
