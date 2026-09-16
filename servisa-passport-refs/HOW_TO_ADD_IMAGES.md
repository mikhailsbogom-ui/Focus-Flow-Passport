# How to add the JPEGs

GitHub API from this session writes text reliably. Binary JPEGs (~60–200 KB) need one manual drop.

1. Download `servisa-supplier-photos.zip` from the chat.
2. Unzip. You get:
   - `servisa-passport-refs/suppliers/` — 8 photos of service suppliers
   - `servisa-passport-refs/source-spec/` — screenshots from the product specs
3. Open https://github.com/mikhailsbogom-ui/Focus-Flow-Passport/tree/main/servisa-passport-refs
4. Drag the folders `suppliers` and `source-spec` onto that page and commit.

After that another model can clone:

```
git clone https://github.com/mikhailsbogom-ui/Focus-Flow-Passport.git
```

and read `servisa-passport-refs/manifest.json`.
