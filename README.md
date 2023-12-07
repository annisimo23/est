

yarn_install(nk the shared
    # set of deps for example e2es
    exports_directories_only = False,
    manual_build_file_contents = """\
filegroup(
    name = "node_modules_files",
