cmake_minimum_required(VERSION 3.31)

find_package(cmake-pear REQUIRED PATHS node_modules/cmake-pear)

project(pear_appling C CXX ASM)

add_pear_appling(
  pear_appling
  ID "dhpc5npmqkansx38uh18h3uwpdp6g9ukozrqyc4irbhwriedyeho"
  NAME "Keet"
  LINK "pear://oeeoz3w6fjjt7bym3ndpa6hhicm8f8naxyk11z4iypeoupn6jzpo"
  VERSION 1.0.0
  AUTHOR "Holepunch"
  DESCRIPTION "Example appling"

  MACOS_IDENTIFIER to.holepunch.example
  MACOS_CATEGORY public.app-category.utilities
  MACOS_SIGNING_IDENTITY "-"

  WINDOWS_SIGNING_SUBJECT "<string>"
  WINDOWS_SIGNING_THUMBPRINT <sha1>

  LINUX_CATEGORY Utility
)
