# Gemfile
source "https://rubygems.org"

# Core
gem "jekyll", "~> 4.3"
gem "minima", "~> 2.5"

# Optional but recommended plugins (SEO & sitemap)
gem "jekyll-seo-tag", "~> 2.8"
gem "jekyll-sitemap", "~> 1.4"

# Dev-only (Windows 편의 & 로컬 서버)
group :development do
  gem "webrick", "~> 1.8"                         # Ruby 3.x에서 jekyll serve에 필요
  gem "wdm", ">= 0.1.0", platforms: [:mingw, :x64_mingw, :mswin]  # Windows 파일감시 속도 향상
  gem "fiddle", "~> 1.1", platforms: [:mingw, :x64_mingw, :mswin] # 향후 Ruby 3.5 경고 억제용(선택)
end
