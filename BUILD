java_library(
    name = "everything",
    srcs = glob([
        "guava/src/**/*.java",
        "futures/failureaccess/src/**/*.java",
    ]),
    deps = [
        "@maven//:com_google_code_findbugs_jsr305",
        "@maven//:com_google_errorprone_error_prone_annotations",
        "@maven//:com_google_j2objc_j2objc_annotations",
        "@maven//:org_checkerframework_checker_qual",
        "@maven//:org_codehaus_mojo_animal_sniffer_annotations",
    ],
)

java_binary(
    name = "test",
    srcs = ["src/Main.java"],
    deps = ["//:everything"],
    main_class = "src.Main"
)