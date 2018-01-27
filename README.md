csv-viewer
==========

csv-viewer is a viewer for tabular data files. Files are expected to
include column headers. Column separators (comma, semicolon, tab, etc.)
are recognized automatically. Data is loaded in the background with
idle-priority, allowing a quick look at a large file while (hopefully)
maintaining a responsive user interface.

<img src="https://otsaloma.io/pub/csv-viewer-1.png" width="748" alt="Screenshot">

To install, run

```bash
make PREFIX=... install
```

csv-viewer requires [Python][1] ≥ 3.0, [PyGObject][2] ≥ 3.0 and
[GTK+][3] ≥ 3.12.

[1]: https://www.python.org/
[2]: https://wiki.gnome.org/Projects/PyGObject
[3]: https://www.gtk.org/
