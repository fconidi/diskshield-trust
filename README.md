# DiskShield vendor key

This repository publishes the public key used to verify DiskShield commercial licences and signed revocation lists. It contains no private key.

The key identifier is `vendor-2026-d50e6cdf`. The SHA-256 fingerprint of [vendor-public.pem](vendor-public.pem) is:

```text
d50e6cdf1531d9716234333d155b6683026573a14cb8c4b24acad5e7ba71e66b
```

Compare this fingerprint with the one shown by the DiskShield report verification page. To check the downloaded file locally, run `sha256sum vendor-public.pem`.

For report verification, use the DiskShield verification page or `diskshield-report verify` with the XML, PDF and `.sig` files. The date in a report is declared by its signer; it is not an independent timestamp.

## Italiano

Questo repository pubblica la chiave pubblica usata per verificare le licenze commerciali DiskShield e gli elenchi firmati delle revoche. Non contiene chiavi private. L'identificativo è `vendor-2026-d50e6cdf`; verifica l'impronta SHA-256 del file con `sha256sum vendor-public.pem` e confrontala con quella mostrata nella pagina di verifica. La data del report è dichiarata dal firmatario e non costituisce una marca temporale indipendente.
