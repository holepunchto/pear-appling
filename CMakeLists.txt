cmake_minimum_required(VERSION 4.0)

find_package(cmake-pear REQUIRED PATHS node_modules/cmake-pear)

project(pear_appling C CXX ASM)

add_pear_appling(
  pear_appling
  ID "<z32-key>"
  NAME "<string>"
  VERSION 1.0.0
  AUTHOR "<string>"
  DESCRIPTION "<string>"

  MACOS_IDENTIFIER <namespace>
  MACOS_CATEGORY <category>
  MACOS_SIGNING_IDENTITY <id>

  WINDOWS_SIGNING_SUBJECT "<string>"
  WINDOWS_SIGNING_THUMBPRINT <sha1>

  LINUX_CATEGORY <category>
)
