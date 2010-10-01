# Copyright (C) 2007-2009 LuaDist.
# Created by Peter Drahoš
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

PROJECT(lunit NONE)
CMAKE_MINIMUM_REQUIRED(VERSION 2.8)
INCLUDE(dist.cmake)

# Install all files and documentation
INSTALL (FILES lunit-console.lua lunit.lua DESTINATION ${INSTALL_LMOD})
INSTALL (FILES ANNOUNCE DOCUMENTATION CHANGES LICENSE README DESTINATION ${INSTALL_DATA})
INSTALL (FILES example.lua DESTINATION ${INSTALL_EXAMPLE})
INSTALL (FILES lunit-tests.lua DESTINATION ${INSTALL_TEST})
INSTALL (FILES lunit DESTINATION ${INSTALL_FOO})
