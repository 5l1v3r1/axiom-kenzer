# axiom-kenzer

A custom axiom image to quickly deploy [kenzer](https://github.com/ARPSyndicate/kenzer) recon chatbot to VPS.

## Usage

1. Copy `kenzer.json` packer image file to axiom config directory under `~/.axiom/images/provisioners`
2. Build axiom image
3. Initialize new axiom instance

```
cp kenzer.json ~/.axiom/images/provisioners/kenzer.json
axiom-build kenzer
axiom-init
```
