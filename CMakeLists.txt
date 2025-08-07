cmake_minimum_required(VERSION 3.31)

find_package(cmake-pear REQUIRED PATHS node_modules/cmake-pear)

project(pear_appling C CXX ASM)

add_pear_appling(
  pear_appling
  ID "dhpc5npmqkansx38uh18h3uwpdp6g9ukozrqyc4irbhwriedyeho"
  NAME "keet-next"
  LINK "pear://ma9zo8zmfat3ih314mne1q47shrfho1odyfm9methgnn7b866w6y"
  VERSION 1.0.0
  AUTHOR "Holepunch"
  DESCRIPTION "DEMO"

  MACOS_IDENTIFIER com.holepunch.keetnext
  MACOS_CATEGORY public.app-category.utilities
  MACOS_SIGNING_IDENTITY "-"

  WINDOWS_SIGNING_SUBJECT "<string>"
  WINDOWS_SIGNING_THUMBPRINT <sha1>

  LINUX_CATEGORY Utility
)
