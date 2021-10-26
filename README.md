# rust wasm

## command(Unverified)
```bash
# build rust wasm
cargo install wasm-pack
cd rust-wasm-hello/hello-wasm
wasm-pack build

cd ../

# prepare yarn
yarn install

# listen request
yarn webpack-cli serve
```

# environment
rustc: 1.56.0  
npm: 8.1.0  
yarn: 1.22.10  
node: v16.13.0  
