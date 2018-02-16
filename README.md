# Minimal

A very minimal [Ghost] theme inspired by https://thebestmotherfucking.website/.

See it in action at https://annema.me/

[Ghost]: https://ghost.org/

## Installation

Download `minimal.zip` from the [latest release]

[latest release]: https://github.com/klaaspieter/minimal/releases

Upload it to your ghost blog:

https://your-ghost-blog.url/ghost/#/settings/design

Activate the theme.

## Developing

Clone this repo

```sh
git clone https://github.com/klaaspieter/minimal.git
```

Symlink the minimal theme in your [local ghost install]:

```sh
cd path/to/local/ghost
cd content/themes
ln -s /path/to/minimal ./
cd ../../
```

Activate the minimal theme at http://localhost:2369/ghost/#/settings/design

[local ghost install]: https://docs.ghost.org/docs/install-local#section-developing-themes

## Releasing

Zip the theme:

```sh
zip minimal *
```

Copy the changelog for the version and create a git tag:

```sh
git tag -s [version]
```

Paste the changelog into the editor. Save and quit.

Push the git tag:

```sh
git push --tags
```

Create a new [github release]. Paste the changelog to describe the release and attach the minimal.zip file.

Publish the release.

[github release]: https://github.com/klaaspieter/minimal/releases/new
