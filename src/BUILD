load("@rules_cc//cc:defs.bzl", "cc_binary")

cc_binary(
  name = "introspector-generator",
  srcs = ["main.cpp", "spellbook.h"],
  copts = ["--std=c++17"],
  linkopts = ["-lc++fs"],
)
