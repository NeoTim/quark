#[[
Copyright 2018 Google LLC

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
]]
cmake_minimum_required(VERSION 3.0)
project(xmssmt_verify)

include_directories(${COMMON_SRC_ROOT}
        ${XMSSMT_SRC_ROOT}
        )

add_library(xmssmtVerify
        ${XMSSMT_SRC_ROOT}/verify.c
        ${COMMON_SRC_FILES}
        )
