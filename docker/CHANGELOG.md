# Changelog

All notable changes to the fyne-cross docker images will be documented in this file.

Release cycle won't follow the fyne-cross one, so the images will be tagged using the label
year.month.day along with the latest one.

# Release 20.11.28
- Update fyne cli to v1.4.2-0.20201127180716-f9f91c194737 fyne-io#1609

# Release 20.11.25
- Update fyne cli to v1.4.2-0.20201125075943-97ad77d2abe0 fyne-io#1538

# Release 20.11.23
- Update fyne cli to v1.4.2-0.20201122132119-67b762f56dc0 fyne-io#1527

# Release 20.11.04
- fyne cli updated to v1.4.0

# Archive

These releases occurred in the original namspace, lucor/fyne-cross

# Release 20.08.13
- Base image is based on dockercore/golang-cross@1.13.15 (Go v1.13.15)
- fyne cli updated to v1.3.3

# Release 20.07.17
- Base image is based on dockercore/golang-cross@1.13.14 (Go v1.13.14)

# Release 20.07.16
- Base image is based on dockercore/golang-cross@1.13.13 (Go v1.13.13)
- fyne cli updated to v1.3.2

# Release 20.06.07
- Base image is based on dockercore/golang-cross@1.13.12 (Go v1.13.12)
- fyne cli updated to v1.3.0

# Release 20.05.21
- Base image is based on dockercore/golang-cross@1.13.11 (Go v1.13.11)
- Android image: upgrade fyne cli tool to develop to allow build for app fyne
  develop branch

# Release 20.05.10
- Add support for FreeBSD: lucor/fyne-cross:freebsd-latest

# Release 20.05.03
- Introduce new label versioning
- Base image is based on dockercore/golang-cross@1.13.10 (Go v1.13.10)
- Add dedicated images for linux 386, arm and arm64 #25