# MSC server releases

Built Windows x64 server ZIPs only.

The server uses its normal native updater to download the ZIP for its configured channel. Release tags start with `release-v`; test tags start with `test-v`. Each release has one server ZIP containing ReSkateServer.exe and license notices.

To publish manually: create a draft release with the appropriate tag, attach one server ZIP, and publish it. Mark test builds as prereleases. Server source, deployment settings, player data, plugins, bot files and credentials are not stored here. No release-channel build is published until explicitly promoted.
