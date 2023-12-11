# leo_template.aleo

## Build Guide

To compile this Aleo program, run:
```bash
snarkvm build
```

To execute this Aleo program, run:
```bash
snarkvm run hello
```


# Install

```bash
git clone https://github.com/AleoHQ/leo
cd leo

# Build and install
cargo install --path .
```

```bash
https://github.com/AleoHQ/snarkOS/releases
```

```bash
# Download the source code
git clone https://github.com/AleoHQ/snarkVM
cd snarkvm

# Build in release mode
$ cargo install --path .

```

```bash
snarkos developer deploy --private-key ===your_private_key=== --query http://203.160.91.77:13033 --priority-fee 100 leo_template.aleo --broadcast http://203.160.91.77:13033/testnet3/transaction/broadcast --path ./build

📦 Creating deployment transaction for '[1mleo_template.aleo[0m'...

✅ Created deployment transaction for '[1mleo_template.aleo[0m'
✅ Successfully broadcast deployment at1ehfpy4rjcx92e9v603devezjyga8aa6dllj2wz2kgzev4u0fcgqqvs7unj ('[1mleo_template.aleo[0m') to http://203.160.91.77:13033/testnet3/transaction/broadcast.
at1ehfpy4rjcx92e9v603devezjyga8aa6dllj2wz2kgzev4u0fcgqqvs7unj
```
