# sophosd

Daemon for connecting to Sophos written in Rust.

 ## Installation and Usage
  ### For Windows 
  Download [rustup-init.exe](https://win.rustup.rs/) and run it. Proceed with installation of rust.

  If prompted for missing Visual C++ prerequisites, you will have to download Microsft Visual C++ build tools from 
  [here](https://visualstudio.microsoft.com/downloads/#build-tools-for-visual-studio-2019). After installing Visual Studio Installer,         in the workload tab select C++ build tools, under the Windows header and install.

  Clone this repository using [Git Bash](https://git-scm.com/download/win) or download the 
  [ZIP file](https://github.com/DelusionalOptimist/sophosd.git) and extract it to user's home directory.


  ### For Linux
  As there is no binary release you'd have to compile the source code on your own machine. For that the [Rust compiler and Cargo             package      manager](https://www.rust-lang.org/learn/get-started) are needed. You may also need to install an OpenSSL development         package - this is `libssl-dev` on Ubuntu and `openssl-devel` on Fedora.

  Clone this repository

## Starting the daemon

 ### On Windows
  Launch Windows PowerShell and `cd` to home directory, where `Cargo.toml` is located. 
  
  Enter your username and password for connecting to sophos in the format:
  
  ```cargo run <username> <password>```
  
  ### On Linux 
  [`cargo run`](https://doc.rust-lang.org/cargo/commands/cargo-run.html)

  `cd` to base directory where `Cargo.toml` is located and type:

  ```cargo run <username> <password> ```

