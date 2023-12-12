# PuraVida Changelog

The `galoy-pay` repository was cloned and modified so that it would be more suitable for PuraVida Bitcoin.
This file outlines the changes we made to the original source files, in case the changes need to be replicated
to a different branch/version later on.

1. Removed the Galoy footer from `/components/Layouts/AppLayout.tsx`
2. Added `/public/icons/puravida-logo-icon.svg`
3. Changed logo filename in `/components/Layouts/AppLayout.tsx`
4. Adjusted nav header padding in `/components/Layouts/app-layout.module.css`
5. Updated config values in `/config/config.ts`
6. Updated `lib/config/config.ts` to default to PuraVida domains
7. Updated `.github` with build and public deploy configuration for PuraVida
   - All Galoy configs were moved to `/.github.galoy.backup`
   - Added workflow calls to `PuraVida-Technologies/pura-vida-shared-workflows`

```
deploy test2
```