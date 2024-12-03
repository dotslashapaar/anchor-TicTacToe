## Here is your deployment checklist 🚀

- Run `anchor build`. Your program keypair is now in `target/deploy`. Keep this keypair secret. You can reuse it on all clusters.
- Run `anchor keys list` to display the keypair's public key and copy it into your `declare_id`! macro at the top of `lib.rs`.
- Run `anchor build` again. This step is necessary to include the new program id in the binary.
- Change the `provider.cluster` variable in `Anchor.toml` to `devnet`.
- Run `anchor deploy`
- Run `anchor test`

## `anchor deploy`
<img width="491" alt="deploy" src="https://github.com/user-attachments/assets/47feb4cb-8647-44c9-9a45-64d5e80aaa0d">

## Solana Explore
<img width="864" alt="sol-explorer" src="https://github.com/user-attachments/assets/0dc088b9-a9e1-44ad-b167-702951fde6a3">
