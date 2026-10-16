# E2E Third-party B (do not install)

**This is a test plugin. Do not install it.** It exists only for the NEGATIVE case of the Astra plugins
registry's third-party publishing walk (ROLL-32): `.well-known/astra-plugin-owner` here deliberately
carries a binding token minted for `astra-e2e-thirdparty`, a DIFFERENT repository, so the registry bot
is expected to refuse this release's ingest (`B_BINDING_UNUSABLE`). It is a copy of `astra-dice-roller`
with a different id and is not a real plugin. It will be withdrawn after the test.
