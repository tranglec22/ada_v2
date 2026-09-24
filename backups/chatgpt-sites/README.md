# ChatGPT @Sites Backup Registry

Backup branch: `chatgpt-sites-backup`

This folder preserves the verified ChatGPT @Sites projects associated with the account and their recovery context.

Important limitation: the ChatGPT @Sites source/export API is not exposed in the current chat environment, so this backup currently preserves project identity, canonical slug, published URL, purpose, and recovery notes rather than a byte-for-byte source-code export.

## Verified @Sites projects

1. **UTC.OS**
   - Canonical slug: `utc-os-app`
   - Published URL: https://utc-os-app.tranglec.chatgpt.site
   - Role: canonical UTC.OS personal operating system / command center.

2. **UP2CODE Painting & Contracting**
   - Canonical slug: `up2code-me`
   - Published URL: https://up2code-me.tranglec.chatgpt.site
   - Role: UP2CODE painting & contracting business site.

3. **UP2CODE Lead Engine**
   - Canonical slug: `up2code-lead-engine`
   - Published URL: https://up2code-lead-engine.tranglec.chatgpt.site
   - Role: lead-generation / lead-engine site feeding UP2CODE and UTC.OS workflows.

4. **Lil Wiz-Nap Secret Vault**
   - Canonical slug: `lil-wiznap-secret`
   - Published URL: https://lil-wiznap-secret.tranglec.chatgpt.site
   - Role: hidden/artist-side Lil Wiz-Nap experience and secret-vault content.

## Related projects that are not counted as ChatGPT @Sites

- Older UTC.OS / Up To Code OS builds in Lovable and other builders are related projects, but they are not treated as duplicate @Sites projects in this registry.
- `up2code.me` is a custom domain and should not be confused with the ChatGPT Sites slug `up2code-me`.

## Recovery rule

The canonical site names/slugs above should be preserved. Future restores or migrations should update the existing canonical project whenever possible instead of creating unnecessary duplicates.
