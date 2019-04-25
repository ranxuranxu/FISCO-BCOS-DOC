# Download & Install

## Environment Dependence

Dependence of FISCO BCOS generator:

| Dependent software | Supported version |
| :-: | :-: |
| python | 2.7+ or 3.6+ |
| openssl | 1.0.2k+|
| curl | default version |
| nc | default version |

## Download & Install

```bash
$ git clone https://github.com/FISCO-BCOS/generator.git
$ cd generator
$ bash ./scripts/install.sh
$ ./generator -h
```

When using this tool, users need to place `fisco-bcos` binary program (demo instruction is excepted) under meta folder. The way to get `fisco-bcos` binary program is as below:

Users can aquire FISCO BCOS executable program through one of the methods below. Downloading pre-compiled binary from GitHub is preferred. 

- Statically linked pre-compiled file offered officially can be run on Ubuntu 16.04 and CentOS 7.2 or above.

```bash
# aquire fisco-bcos binary file
$ ./generator --download_fisco ./meta
# check if the binary is executable and execute the instruction below to see the version information
$ ./meta/fisco-bcos -v

**PS**：compile source code to aquire executable program, reference [source code compilation](../manual/get_executable.md)。
