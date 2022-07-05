# create new Hugo site

From dev outet folder
hugo new site [sitename]

# create git repository

From GitHub Desktop
Add fropdown > Create new repository
Select site root

# Install theme

- from site root folder

git submodule add https://github.com/spech66/bootstrap-bp-hugo-theme.git themes/bootstrap-bp-hugo-theme

# Update theme
From the site root…

git submodule update --remote themes/bootstrap-bp-hugo-theme
