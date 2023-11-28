function quiz2(
ge4.waitForNetworkIdle(
)

yarn_install(
    name = "aio_npm",
        "//:.yarnrc",urrently.
    #  2. Incompatibilites with the `ts_library` rule.
    exports_directories_only = False,
)

yarn_install(
    name = "aio_example_deps",
    # Rename the default js_library target from "nod
        "//:.yarnrc",
    ],
    # Disabled because, when False, yarn_install preserves the node_modules folder
    # with bin symlinks in the external repository. This is needed to link the shared
    # set of deps for example e2es.
    exports_directories_only = False,
    manual_build_file_contents = """\
filegroup(
    name = "node_modules_files",
