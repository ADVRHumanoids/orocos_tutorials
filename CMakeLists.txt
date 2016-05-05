# 
#  Copyright (C) 2016 CoGiMoN
#  Author:  Enrico Mingo Hoffman
#  email: enrico.mingo@iit.it
#
#  This program is free software: you can redistribute it and/or modify
#  it under the terms of the GNU Lesser General Public License as published by
#  the Free Software Foundation, either version 3 of the License, or
#  (at your option) any later version.
#
#  This program is distributed in the hope that it will be useful,
#  but WITHOUT ANY WARRANTY; without even the implied warranty of
#  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
#  GNU Lesser General Public License for more details.
#
#  You should have received a copy of the GNU Lesser General Public License
#  along with this program. If not, see <http://www.gnu.org/licenses/>
#

cmake_minimum_required(VERSION 2.8.12)
if(COMMAND cmake_policy)
    cmake_policy(SET CMP0003 OLD)
    cmake_policy(SET CMP0005 NEW)
    cmake_policy(SET CMP0017 NEW)
endif(COMMAND cmake_policy)
include(ExternalProject)
PROJECT(orocos_tutorials)


include(${CMAKE_CURRENT_SOURCE_DIR}/helloworld/CMakeLists.txt)

include(${CMAKE_CURRENT_SOURCE_DIR}/hello-1-task-execution/CMakeLists.txt)
include(${CMAKE_CURRENT_SOURCE_DIR}/hello-1-task-execution-solution/CMakeLists.txt)

include(${CMAKE_CURRENT_SOURCE_DIR}/hello-2-properties/CMakeLists.txt)
include(${CMAKE_CURRENT_SOURCE_DIR}/hello-2-properties-solution/CMakeLists.txt)

include(${CMAKE_CURRENT_SOURCE_DIR}/hello-3-dataports/CMakeLists.txt)
include(${CMAKE_CURRENT_SOURCE_DIR}/hello-3-dataports-solution/CMakeLists.txt)

include(${CMAKE_CURRENT_SOURCE_DIR}/hello-4-operations/CMakeLists.txt)
include(${CMAKE_CURRENT_SOURCE_DIR}/hello-4-operations-solution/CMakeLists.txt)

include(${CMAKE_CURRENT_SOURCE_DIR}/hello-5-services/CMakeLists.txt)

#include(${CMAKE_CURRENT_SOURCE_DIR}/hello-6-scripting/CMakeLists.txt) <-- Uncomment this when you resolve the exercise!
include(${CMAKE_CURRENT_SOURCE_DIR}/hello-6-scripting-solution/CMakeLists.txt)

include(${CMAKE_CURRENT_SOURCE_DIR}/hello-7-deployment/CMakeLists.txt)

include(${CMAKE_CURRENT_SOURCE_DIR}/controller-1/CMakeLists.txt)
include(${CMAKE_CURRENT_SOURCE_DIR}/controller-1-solution/CMakeLists.txt)

include(${CMAKE_CURRENT_SOURCE_DIR}/controller-youbot/CMakeLists.txt)
