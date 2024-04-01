# Image Library Image Access

The problem: Core image library - the dialog to browse files previously
uploaded to Backdrop - is an all-or-nothing item.

You can access all files, regardless who previously uploaded them. This is
fine for small websites with only few users (and roles). This is a pain
point, though, if different roles should have different levels of access to
existing images.

This module provides an extra permission to access all the images in the
image library - other roles (accounts) will only see *their own files* in
the image browser.

## Installation

Install this module using the
 [official Backdrop CMS instructions](https://docs.backdropcms.org/documentation/extend-with-modules).

Go to admin/config/people/permissions and grant the "Access any file in image
library" permission to the roles you need, for example "Editor".
That's it.

## Issues

Bugs and feature requests should be reported in the
 [Issue Queue](https://github.com/backdrop-contrib/image_library_image_access/issues).

## Current maintainers

- [Indigoxela](https://github.com/indigoxela)

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.
