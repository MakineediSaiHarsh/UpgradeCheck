# UpgradeCheck — Task 3 landing page

This is a one-page preview of a household repair-or-upgrade decision tool. Refrigerators are the first planned flow; air conditioners are the next planned category. The page builds on the Task 1 fridge concept and the Task 2 LinkedIn hook.

The example is intentionally static. A ₹4,000 repair and ₹25,000 replacement leave a ₹21,000 upfront gap. Across five years and an illustrative ₹7–10 per unit, the new fridge would need to save 420–600 units each year for electricity savings alone to close that gap. The page does not claim that it will.

## Preview

Open index.html in a browser. Keep the assets folder beside it. There is no build step, external API, data upload, or account flow.

## Publish for the assignment

1. Create a public repository and upload index.html, assets/repair-or-upgrade-editorial.png, and this README. Record the repository URL in Task 3 cell C30. [GitHub's upload guide](https://docs.github.com/en/get-started/start-your-journey/uploading-a-project-to-github).
2. Import that repository on Vercel or drag the folder into [Vercel Drop](https://vercel.com/drop). Record the public URL in Task 3 cell C31.
3. Check the live desktop and mobile page, then capture a real screenshot and complete the ratings. The URL and screenshot fields are blank until those steps happen.

## Task 4 direction

Extend this page with the working refrigerator flow. The separate calculator starter preserves the earlier deterministic form. The required Task 4 stack is Vercel, Gemini, and Supabase: an AI feature should help read a BEE label or explain a verified scenario, while the arithmetic remains deterministic. Add the AC category only after a separate model for its label metric and usage hours has been checked.

BEE labels are standard-test data. The site must not infer an old fridge's actual current consumption from age or star rating, assume a uniform DISCOM rate, or predict a future failure rate.
