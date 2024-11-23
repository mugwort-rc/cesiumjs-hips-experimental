# Experimental HiPS tiling

HiPS Tiling for CesiumJS.

See: https://zenn.dev/mugwort_rc/scraps/7c85c6046f8e91

## Usage

```bash
git clone https://github.com/mugwort-rc/cesiumjs-hips-experimental.git
cd cesiumjs-hips-experimental
git submodule init
git submodule update
cd cds-healpix-rust/libwasmbindgen
cargo install wasm-pack  # if you not installed yet
wasm-pack build --target web
cd ../../
python3 -m http.server
```
