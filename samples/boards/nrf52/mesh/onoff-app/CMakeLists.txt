cmake_minimum_required(VERSION 3.8.2)
set(QEMU_EXTRA_FLAGS -s)

include($ENV{ZEPHYR_BASE}/cmake/app/boilerplate.cmake NO_POLICY_SCOPE)
project(onoff-app)

target_sources(app PRIVATE src/main.c)
