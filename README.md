# Matri Check

Independent fictional provider: Janani Care Technologies. Synthetic evaluation only.

Record symptoms during pregnancy or after birth and support referral.

AI role: Speech-to-text for confirmed maternal symptoms; referral prompts are explicit rules, not predictive diagnosis.

Run node build.mjs, then serve dist/server/wrangler.json with Wrangler. Sites provides private dispatch authentication, D1 and server-only PARTNER_KEY. Migrations are generated from db/schema.ts.

Browser models process recordings/images on-device. Corrected synthetic text and worker-confirmed observations are sent to the provider and retained as receipts. Signed receipts attest rule processing, not browser inference execution. Manual/sample evidence never claims AI inference. Browser speech/OCR evidence is explicitly client-reported. Uncertain results support lookup without re-inference. No clinical approval, prescribing or automatic patient update.
