# Screenshots — `@open-mercato/marketing-automation`

Images referenced from pull request #6749 and from the phased stack #6864…#6953. An orphan branch carrying
nothing but these files: a PR body needs somewhere to point, and putting them on the code branch would mean a
reviewer downloads several MB of PNG to read a diff.

Retaken on 2026-10-13 against the branch head, because the previous set was taken on 2026-09-30 and twenty
commits had changed the screens since. The customer profile alone had been rebuilt from one long column into
panels, the funnel had learned to say who rather than only how many, and the audience panel had been resized
to fit the panel it lives in — so every image in the old set showed a layout that no longer existed.

**Capture conditions differ from the first set, and the images are smaller because of it.** The originals were
full-page captures 1680px wide, taken against a dev instance at 1920×1200 on a 2× display; several ran very
tall (`12-jobs` was 4404px). These are single viewport frames, 1470×690, taken on a 1470×956 laptop display
with no external monitor attached. Each screen is therefore shown from the top down to the fold rather than in
full. Light theme, as before.

Known cosmetics, neither of them a defect in the module:

- `01-campaign-list` lists five campaigns. A leftover test campaign named "Welcome" sits above the four the
  first set showed.
- `13-settings` renders the file picker as "Wybierz plik / Nie wybrano pliku". That is the browser's own
  native control following the OS locale, not module copy.
