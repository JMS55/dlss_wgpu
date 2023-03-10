# dlss_wgpu
### Deep Learning Super Sampling for wgpu

## Downloading The DLSS SDK
The DLSS SDK cannot be redistributed by this crate. You will need to download the SDK as follows:
* On Linux, install `clang` and `ar`
* On Windows, install `clang` (following https://rust-lang.github.io/rust-bindgen/requirements.html#windows) and `lib` (provided by Visual Studio)
* Clone the NVIDIA DLSS Super Resolution SDK v3.1 from https://github.com/NVIDIA/DLSS
* Set the environment variable `DLSS_SDK = /path/to/dlss_sdk/DLSS`
* Ensure you comply with the DLSS SDK license located at https://github.com/NVIDIA/DLSS/blob/main/LICENSE.txt
