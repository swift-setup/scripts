# Package plugin script

This script is used to package the plugin for distribution. It will produce an zip file with the 
required files and folders. It's file name will be based on the platform's architecture and the
name.

For example, on m1 macs, the file name will be `macos_arm64.zip`.

## Usage

```bash
python3 package.py --pattern=*.txt --folder=folder1
```