# BitcoinZ Bootstrap

This bootstrap contains the BitcoinZ blockchain from the genesis block up to the current height at the time of generation.

It allows new nodes to synchronize much more quickly instead of downloading all blocks from the network.

## 📁 Files included

- `bootstrap.dat.7z.001`, `bootstrap.dat.7z.002`, ... → 7z compressed files (multi-part)
- `SHA256SUMS.txt` → List of SHA256 checksums

## ✅ Integrity verification (strongly recommended)

```bash
# On Linux / macOS
sha256sum -c SHA256SUMS.txt

# On Windows (PowerShell)
Get-FileHash bootstrap.dat.7z.001 -Algorithm SHA256
# Manually compare with the contents of SHA256SUMS.txt

Always verify the chain on https://explorer.btcz.rocks/ or https://explorer.getbtcz.com/ after synchronization.

Thanks to the BTCZ community!
