change it!!!
change on local
change on remote
local changed twice
cmake_minimum_required(VERSION 3.15)

project(CCSNMonitor)
set(CMAKE_CXX_STANDARD 17 CACHE STRING "")
remote changed twice
find_package(junosw)
#find_package(myJUNOCommon)
include(PKG)
include(EDM)

add_subdirectory(MonitorMethod)
add_subdirectory(PromptMonitor)
add_subdirectory(OnlineMonitor)
##add_subdirectory(dataExtract)
##add_subdirectory(crossCheck)

include(JUNOSetupScripts)
include(JUNOInstallOfflineSetup)
