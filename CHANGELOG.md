# 0.1.2

- `fromJson`/`toJson` no longer require/add a `runtimeType` key for classes with a
  single constructor. (https://github.com/rrousselGit/freezed/issues/7)

- don't generate anything for classes that add `@immutable` but define real properties
  (https://github.com/rrousselGit/freezed/issues/5)

# 0.1.1

Upgrade min range of `analyzer` dependency

# 0.1.0

Add support for `json_serializable`

# 0.0.2

Implicitly generate `debugFillProperties` if the necessary classes are imported.

# 0.0.1

Add generic support

# 0.0.0

Initial release