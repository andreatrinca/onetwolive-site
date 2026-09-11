# onetwolive-site
Official website of OneTwoLive


## Direct purchase configuration

Set `dodoProductId` in `site-config.js` before going live with direct purchases through Dodo Payments. Set `downloadUrl` when the final installer is available.


## Release workflow

The standalone Windows installer is distributed as a GitHub Release asset, not committed to the repository.

For each release:

1. Create a Git tag/release such as `v1.1.0`.
2. Upload `OneTwoLiveSetup-1.1.0-win-x64.exe` as a release asset.
3. Update `downloadUrl` and `releaseVersion` in `site-config.js`.
4. Update `/releases/` and `/it/releases/` with the release notes.
5. Publish the website.
