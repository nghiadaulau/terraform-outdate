# Unsupported Packages for Darwin ARM64

This repository provides a collection of Terraform providers and other essential packages that are no longer officially supported for the `darwin_arm64` architecture (Apple Silicon - M1/M2/M3). It serves as a community-driven initiative to compile, store, and distribute necessary binaries for developers working on macOS with Apple Silicon.

## 🚀 Features
- Pre-compiled binaries for unsupported Terraform providers
- Instructions on how to install and use the stored packages
- Community contributions to maintain compatibility

## 📌 Why This Repository?
Many open-source tools and Terraform providers have not been updated to support Apple Silicon (`darwin_arm64`). This repository helps bridge that gap by providing:
- Manually compiled versions of outdated packages
- Workarounds and alternative installation methods
- A centralized location to find necessary binaries

## 📥 Installation & Usage
To use a package from this repository, follow these steps:

1. **Download the required package** from the `releases` section or build it from source if applicable.
2. **Move the binary to the appropriate directory**. For example, for Terraform providers:
   ```sh
   mkdir -p ~/.terraform.d/plugins/registry.terraform.io/hashicorp/<provider>/<version>/darwin_arm64/
   mv <binary-file> ~/.terraform.d/plugins/registry.terraform.io/hashicorp/<provider>/<version>/darwin_arm64/
   ```
3. **Verify the installation**:
   ```sh
   terraform providers
   ```
4. **Run Terraform or other tools as usual.**

## 🛠️ How to Contribute
We welcome contributions! If you have compiled a package for `darwin_arm64` that is not available in official channels, please consider contributing:

1. Fork the repository.
2. Add your package to the appropriate directory.
3. Update the documentation if necessary.
4. Create a pull request with a description of the changes.

## 📜 License
This repository is licensed under the MIT License. Please refer to the `LICENSE` file for details.

---

For any issues or requests, feel free to open an issue or contribute! 🚀

