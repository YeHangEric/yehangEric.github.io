# source "https://rubygems.org"
source "https://jekyllrb.com/docs/continuous-integration/github-actions/"

# 使用 GitHub Pages 支持的 Jekyll 版本
gem "github-pages", "~> 228", group: :jekyll_plugins

# 如果你想在本地运行，添加以下插件
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"
  gem "jekyll-paginate"
end

# Windows 和 JRuby 支持
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# JRuby 支持
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
