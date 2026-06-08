# Zhenbang Peng Homepage

This repository contains the Jekyll-based academic homepage for Zhenbang Peng.

## Local Preview

Install Ruby and Bundler first. On Windows, use RubyInstaller:

```powershell
gem install bundler
bundle install
bundle exec jekyll serve
```

Then open:

```text
http://127.0.0.1:4000/
```

## GitHub Pages Deployment

1. Push this repository to GitHub.
2. Open the repository page on GitHub.
3. Go to `Settings -> Pages`.
4. Set `Source` to `Deploy from a branch`.
5. Select branch `main` and folder `/root`.
6. Save and wait for GitHub Pages to finish building.

If the repository is named `Arknightpzb.github.io`, the public URL will be:

```text
https://Arknightpzb.github.io/
```

With the repository name `zhenbangpeng.github.io` under the `Arknightpzb` account, the public URL is usually:

```text
https://Arknightpzb.github.io/zhenbangpeng.github.io/
```

To make `https://zhenbangpeng.github.io/` itself work, the GitHub owner must be the `zhenbangpeng` account or organization, or you must configure a custom domain and DNS.

## Content Files

- `_config.yml`: site title, profile sidebar, email, GitHub, Google Scholar, ORCID.
- `_pages/about.md`: homepage content, news, research interests, publications, education, and contact.
- `_data/navigation.yml`: top navigation anchors.

## Optional Google Scholar Crawler

The crawler workflow is set to manual dispatch to avoid unstable scheduled failures from Google Scholar anti-bot restrictions. To run it manually, open `Actions -> Get Citation Data -> Run workflow`.
