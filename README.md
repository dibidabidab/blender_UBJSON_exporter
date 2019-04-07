
This is a fork of the original [Libgdx Blender G3D Exporter](https://github.com/Dancovich/libgdx_blender_g3d_exporter)

It is an exporter addon for Blender, that exports your scene to JSON or binary JSON ([UBJSON](http://ubjson.org/)).

The original addon did not export to the official UBJSON format, because LibGDX uses a custom UBJSON loader.

This addon does export to the official UBJSON format, using [py-ubjson](https://pypi.org/project/py-ubjson/).
Because of that, the UBJSON files exported by this addon cannot be parsed by LibGDX anymore. However, they can be parsed by anything else that supports UBJSON, such as [JSON for C++](https://github.com/nlohmann/json).

### Installation

[Same as the original addon](https://github.com/Dancovich/libgdx_blender_g3d_exporter/wiki/Installation) + you need to install [py-ubjson](https://pypi.org/project/py-ubjson/)

<img src="https://download.blender.org/branding/blender_logo_socket.svg" width="200">