add_executable(readfile readfile.c)
target_link_libraries(readfile cbor)

add_executable(create_items create_items.c)
target_link_libraries(create_items cbor)

add_executable(streaming_parser streaming_parser.c)
target_link_libraries(streaming_parser cbor)

add_executable(sort sort.c)
target_link_libraries(sort cbor)


add_executable(hello hello.c)
target_link_libraries(hello cbor)
