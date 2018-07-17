# Autotuning OpenCL Workgroup Size for Stencil Patterns (ADAPT'16).

exports_files(["README.md"])

genrule(
    name = "2016_01_adapt",
    srcs = glob([
        "tex/**/*.bib",
        "tex/**/*.cls",
        "tex/**/*.tex",
        "tex/img/*",
    ]),
    outs = ["2016_01_adapt.pdf"],
    cmd = "$(location //tools:autotex) docs/2016_01_adapt/tex/paper.tex $@",
    tools = ["//tools:autotex"],
)
