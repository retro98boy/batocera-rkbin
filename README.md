# batocera-rkbin

Validated Rockchip boot firmware and packaging tools for building
[batocera.linux](https://github.com/batocera-linux/batocera.linux).

## Why not use upstream rkbin directly?

[rockchip-linux/rkbin](https://github.com/rockchip-linux/rkbin) may remove older
blobs from newer revisions, while some boards require specific versions or
third-party modifications. Newer firmware does not necessarily improve those
boards and requires fresh validation and regression testing. Batocera therefore
keeps the versions validated for each board instead of following upstream updates.

## Retention policy

Old blobs will not be deleted or overwritten. New versions are added alongside
existing ones. Original filenames are preserved; when identical filenames refer
to different contents, a device name is added to distinguish them.
