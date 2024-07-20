# Sui BCS Type Generator

This tool generates BCS types for the Sui blockchain. It fetches the normalized Move modules from a specified package and creates the corresponding BCS type definitions in JavaScript.

## Usage

To generate BCS types, use the following command:

```bash
npx sui-bcs gen --package <package_address> --file <output_file> --network <network_name>
```

- `--package <package_address>`: The address of the package from which to fetch the Move modules.
- `--file <output_file>`: The name of the file to write the generated BCS types to.
- `--network <network_name>`: The network to use (default: `testnet`).

Example:

```bash
npx sui-bcs gen --package 0x2 --file sui-bcs.js --network testnet
```

![BCS Type Generation](https://i.imgur.com/x9INRct.png)
