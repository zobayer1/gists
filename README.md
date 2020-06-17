# GISTS

Master repository for all my github gists.

## Add A New Gist

1. Create or find a gist in [gist.github.com](https://gist.github.com/)

2. Find Gist URL (can be either of `ssh` or `https` url)

3. Add as submodule to this repo: `git submodule add [Gist URL] [A meaningful directory name]`

4. Commit in master repository and push to origin.

## Clone All Gists

1. Clone all submoduels using: `git clone --recurse-submodules [Master URL]`

2. Note: If you have a lot of gists, there will be a lot of cloning.

## Pull All Changes

1. Pull changes from all submodules: `git pull --recurse-submodules`

## Run for All Submodules

1. To see logs from all submodules: `git submodule foreach --recursive 'git log'`

## Credits

1. An idea from [Yumalnaura](https://gist.github.com/YumaInaura)
