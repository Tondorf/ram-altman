Dashboard pictures, compiled into the binary (`api::image`) and served at `/img/<file>`.
Adding or replacing one needs a rebuild; a new file name also needs a line in `api::image`.

JPEG, with exactly these names:

- `sam-sad.jpg`: shown next to `free()` (left of the title)
- `sam-happy.jpg`: shown next to `malloc()` (right of the title)

Shown as circles, so a roughly square, face-centered image works best.
Until a file exists, the page shows an emoji placeholder instead.
