package(default_visibility = ["//visibility:public"])

pex_binary(
    name = "test-runner",
    srcs = [
        "main.py"
    ],
    main = "main.py",
    resources = [
        "resources/test.json",
    ],
    reqs = [
        "argparse==1.4.0",
        "future==0.18.2"
    ],
    deps = [
        "//heron/common/src/python:common-py",
        "//integration_test/src/python/common",
    ],
)
