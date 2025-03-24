# Soundness Command

🔹 Tw: https://tinyurl.com/yc7y3bzw
🔹DC: https://tinyurl.com/e7j8pp63
🔹Offitial link: https://soundness.xyz/

This guide provides step-by-step instructions to install Rust, set up Soundness Layer, and manage key pairs using `soundness-cli`.

## Prerequisites
Ensure your system is up to date:
```bash
sudo apt update && sudo apt upgrade -y
```

## Install Rust
Download and install Rust:
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Load Rust environment:
```bash
source $HOME/.cargo/env
```

Verify Rust and Cargo installation:
```bash
rustc --version && cargo --version
```

Make Rust environment persistent:
```bash
echo 'source $HOME/.cargo/env' >> ~/.bashrc
source ~/.bashrc
```

## Install Soundness Layer
Run the installation script:
```bash
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
```
```bash
source ~/.bashrc
```

## Install Soundness CLI
```bash
soundnessup install
soundnessup update
```

## Key Management
### Generate a Key Pair
```bash
soundness-cli generate-key --name my-key
```

### Import a Key Pair (From Mnemonic)
```bash
soundness-cli import-key --name my-key
```

### List All Key Pairs
```bash
soundness-cli list-keys
```

### Export a Key's Mnemonic
```bash
soundness-cli export-key --name my-key
```

---

## Notes
- Ensure you have the necessary permissions to run the commands.
- Always keep your key mnemonic secure.
- If you face any issues, refer to the official documentation of Soundness Layer.

For Update follw my 
Discord: https://discord.gg/fAbDjmAyHs
Telegram: https://t.me/NachT_DROP



