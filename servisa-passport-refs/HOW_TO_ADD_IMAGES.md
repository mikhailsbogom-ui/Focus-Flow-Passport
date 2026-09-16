# How to add the generated JPEGs

GitHub API from this session can write text files, but not reliably push ~100KB binary JPEGs in one commit.

Do this once:

1. Download `servisa-passport-refs.zip` from the chat.
2. Unzip.
3. Drag the folders `generated/` and `source-spec/` into
   `https://github.com/mikhailsbogom-ui/Focus-Flow-Passport/tree/main/servisa-passport-refs`
4. Commit.

After that another model can clone:

```
git clone https://github.com/mikhailsbogom-ui/Focus-Flow-Passport.git
```

and read `servisa-passport-refs/manifest.json`.
