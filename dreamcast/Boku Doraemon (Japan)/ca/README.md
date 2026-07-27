# Boku Doraemon (Japan): Catalan

Catalan patch for the Dreamcast game *Boku Doraemon* (Japan).

## Download

**Latest release:** [Boku_Doraemon_Japan_T-Cat_v0.6-Beta](https://github.com/consolesplayingconsoles/game-translations/releases/tag/boku-doraemon-japan-t-cat-v0.6-beta)

Patch file: [`Boku_Doraemon_Japan_T-Cat_v0.6-Beta.dcp`](https://github.com/consolesplayingconsoles/game-translations/releases/download/boku-doraemon-japan-t-cat-v0.6-beta/Boku_Doraemon_Japan_T-Cat_v0.6-Beta.dcp)

Releases in this monorepo are namespaced per game, so the tag carries the game name (`boku-doraemon-japan-...`), not just a version.

## Applying the patch

Use [Universal Dreamcast Patcher](https://github.com/DerekPascarella/UniversalDreamcastPatcher/releases), the standard Dreamcast patching tool. It rebuilds a correct disc image from your own copy of the game, so it works across GDI, CUE+BIN, and CHD dumps.

You will need a GDI image of the original Japanese game with MD5 *58f3df741685a17c74b2187735a3a0dd*

1. Download the latest version for your OS.
2. Open the **Apply Patch** tab.
3. Select your source disc image (`.gdi`, `.cue`, or `.chd`).
4. Choose the `.dcp` patch file above.
5. Pick an output folder and format.
6. Click **Apply Patch**.

## Known issues

This is a **beta**. The translation is complete, but the whole game has not yet been played end to end to verify every line in context, so some text may still be unverified. The game is otherwise fully playable.

- **Invention list not yet translated.** The catalogue of gadgets shown inside the **Butxaca màgica** menu is still in Japanese. It lives only in that menu and does not affect gameplay. It will be translated in a later version.

## Feedback

Feedback from faster players than me is very welcome, especially while the game is in beta. Found a bug, a typo, or untranslated text? [Open an issue](https://github.com/consolesplayingconsoles/game-translations/issues/new). Note the scene or menu where it happens (a screenshot helps), and mention that it is the Catalan Boku Doraemon patch.
