LIFE FIRE - clean APK (no ads, no trackers), built free on GitHub

1. Make a free account at github.com and click New repository (name it life-fire, leave it Private).
2. On the new repository page click "uploading an existing file" and drag in everything from this folder:
   www, assets, package.json, capacitor.config.json.
3. The hidden .github folder must go in too. If it does not upload, click Add file > Create new file,
   type  .github/workflows/build-apk.yml  as the name, paste the contents of that file, and Commit.
4. Open the Actions tab, click "Build APK", then Run workflow. Wait about 5 to 10 minutes.
5. Open the finished run, scroll to Artifacts, download life-fire-apk, unzip it. app-debug.apk is your app.
6. Copy it to your phone and open it. Allow "Install unknown apps" when Android asks.
