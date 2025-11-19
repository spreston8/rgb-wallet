# F1r3fly-RGB

A Bitcoin Signet wallet with RGB compatibility, featuring a Rust backend and modern React frontend.

## Components

### [Wallet Backend](./wallet/README.md)
RGB-compatible Bitcoin Signet wallet backend service.

**Quick Start:**
```bash
cd wallet
cargo run --release
```
Server runs on `http://localhost:3000`

See [wallet/README.md](./wallet/README.md) for detailed documentation.

### [Wallet Frontend](./wallet-frontend/README.md)
Modern React UI for interacting with the wallet backend.

**Quick Start:**
```bash
cd wallet-frontend
npm install
npm run dev
```
Frontend runs on `http://localhost:5173`

See [wallet-frontend/README.md](./wallet-frontend/README.md) for detailed documentation.

## Development

### Running the Full Stack

1. **Start the backend** (in one terminal):
   ```bash
   cd wallet
   cargo run --release
   ```

2. **Start the frontend** (in another terminal):
   ```bash
   cd wallet-frontend
   npm run dev
   ```

3. Open `http://localhost:5173` in your browser

### Debug logs for wallet module only

`RUST_LOG=wallet=debug cargo run`
