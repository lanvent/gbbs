cc_library(
  name = "StronglyConnectedComponents",
  hdrs = ["StronglyConnectedComponents.h"],
  deps = [
  "//gbbs:gbbs",
  "//gbbs/pbbslib:resizable_table",
  "//pbbslib:random_shuffle"
  ]
)

cc_binary(
  name = "StronglyConnectedComponents_main",
  srcs = ["StronglyConnectedComponents.cc"],
  deps = [":StronglyConnectedComponents"]
)

package(
  default_visibility = ["//visibility:public"],
)
