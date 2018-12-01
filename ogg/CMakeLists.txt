
cmake_minimum_required(VERSION 3.4.1)

include_directories(src/main/cpp/ogg/include/)
include_directories(src/main/cpp/ogg/src/)

add_library( ogg
             STATIC
    src/main/cpp/ogg/src/analysis.c
    src/main/cpp/ogg/src/bitrate.c
    src/main/cpp/ogg/src/bitwise.c
    src/main/cpp/ogg/src/block.c
    src/main/cpp/ogg/src/codebook.c
    src/main/cpp/ogg/src/envelope.c
    src/main/cpp/ogg/src/floor0.c
    src/main/cpp/ogg/src/floor1.c
    src/main/cpp/ogg/src/framing.c
    src/main/cpp/ogg/src/info.c
    src/main/cpp/ogg/src/lookup.c
    src/main/cpp/ogg/src/lpc.c
    src/main/cpp/ogg/src/lsp.c
    src/main/cpp/ogg/src/mapping0.c
    src/main/cpp/ogg/src/mdct.c
    src/main/cpp/ogg/src/psy.c
    src/main/cpp/ogg/src/registry.c
    src/main/cpp/ogg/src/res0.c
    src/main/cpp/ogg/src/sharedbook.c
    src/main/cpp/ogg/src/smallft.c
    src/main/cpp/ogg/src/synthesis.c
    src/main/cpp/ogg/src/vorbisenc.c
    src/main/cpp/ogg/src/vorbisfile.c
    src/main/cpp/ogg/src/window.c
           )


