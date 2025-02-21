
java_library(
    name = "util_lib",
    srcs = glob(["utils/*.java"]),
    visibility = ["//visibility:public"],

)
java_binary(
    name = "hello_world",
    srcs = ["HelloWorld.java"],
    main_class = "main.java.com.example.project.HelloWorld",
    deps = [
        ":util_lib",
    ],
)

