
load('@rules_cc//cc:defs.bzl', 'objc_library')

package(default_visibility = ["//visibility:public"])

objc_library(
    name = 'ble',
    sdk_frameworks = [
        'CoreBluetooth',
    ],
    target_compatible_with = [
        "@platforms//os:macos",
    ],
)
