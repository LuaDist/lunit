# Copyright (C) 2007-2012 LuaDist.
# Created by Peter Drahoš
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

project ( lunit NONE )
cmake_minimum_required ( VERSION 2.8 )
include ( cmake/dist.cmake )
include ( lua )

# Install all files and documentation
install_lua_module ( lunit-console lunit-console.lua )
install_lua_module ( lunit-tests lunit-tests.lua )
install_lua_module ( lunit lunit.lua )
install_data ( ANNOUNCE DOCUMENTATION CHANGES LICENSE README )
install_example ( example.lua )
install_foo ( lunit )
