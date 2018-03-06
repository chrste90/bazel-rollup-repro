Showcase for https://github.com/bazelbuild/rules_nodejs/issues/136

To reproduce run:
```
bazel run @yarn//:yarn
bazel build //:app_bundle
```
