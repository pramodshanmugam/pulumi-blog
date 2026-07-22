# Held Up

Public static blog (**Held Up**) about adopting Pulumi safely — especially stopping faulty deletes — plus comparisons to Terraform/CDK and migration paths from existing stacks.

**Live site (after GitHub Pages is enabled):** https://pramodshanmugam.github.io/pulumi-blog/

## Enable GitHub Pages

1. Open the repo on GitHub → **Settings** → **Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Branch: `main`, folder: `/ (root)`.
4. Save. The site usually appears within a few minutes at the URL above.

This repo includes `.nojekyll` so static assets are served as-is.

## Local preview

Open `index.html` in a browser, or from the repo root:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080/`.

## Posts

| Post | Path |
|------|------|
| How Pulumi protect stops faulty deletes | `posts/pulumi-protect.html` |
| Why prefer Pulumi over Terraform and CDK | `posts/why-pulumi.html` |
| Import Terraform, CDK, or CloudFormation into Pulumi | `posts/migrate-to-pulumi.html` |
