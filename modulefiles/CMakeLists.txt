# ##############################################################################
# Copyright (C) Intel Corporation
#
# SPDX-License-Identifier: MIT
# ##############################################################################
cmake_minimum_required(VERSION 3.13.0)

if(UNIX)
  install(
    PROGRAMS vpl
    DESTINATION ${VPL_INSTALL_MODFILEDIR}
    COMPONENT dev)
endif()
