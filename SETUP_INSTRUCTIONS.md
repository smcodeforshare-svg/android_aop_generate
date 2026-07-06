# Setup Instructions for Android APK Auto-Build

## Step 1: Enable GitHub Pages

1. Go to: https://github.com/smcodeforshare-svg/android_aop_generate/settings/pages
2. Under "Build and deployment" > "Source"
3. Select **GitHub Actions** from the dropdown
4. Save the settings

## Step 2: Run the Workflow

After enabling GitHub Pages:

1. Go to: https://github.com/smcodeforshare-svg/android_aop_generate/actions
2. Click on "Build Android APK and Deploy to GitHub Pages" workflow
3. Click the "Run workflow" button
4. Select the "main" branch
5. Click "Run workflow"

## Step 3: Download the APK

After the workflow completes (2-3 minutes):

1. In the workflow run, scroll down to the "Artifacts" section
2. Download either "debug-apk" or "release-apk"
3. Or visit your GitHub Pages site (will be available after first successful deployment)

## Your GitHub Pages URL

After the first successful deployment, your download page will be at:
`https://smcodeforshare-svg.github.io/android_aop_generate/`

## Troubleshooting

If the workflow doesn't appear:
- Make sure GitHub Pages is enabled (Step 1)
- Refresh the Actions page
- The workflow should appear within a few minutes

If the workflow fails:
- Check the workflow logs for errors
- Ensure all files are properly committed to the repository