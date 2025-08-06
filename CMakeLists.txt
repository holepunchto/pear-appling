cmake_minimum_required(VERSION 3.31)

find_package(cmake-pear REQUIRED PATHS node_modules/cmake-pear)

project(pear_appling C CXX ASM)

add_pear_appling(
  pear_appling
  ID "dhpc5npmqkansx38uh18h3uwpdp6g9ukozrqyc4irbhwriedyeho"
  NAME "pear-doctor-next"
  LINK "pear://pkdsoio8aaka3spbums7k6yw5nxj1mw3y3rdw75kj4p51j3i7ago"
  VERSION 1.0.0
  AUTHOR "Holepunch"
  DESCRIPTION "Temp"

  MACOS_IDENTIFIER <namespace>
  MACOS_CATEGORY <category>
  MACOS_SIGNING_IDENTITY -

  WINDOWS_SIGNING_SUBJECT "<string>"
  WINDOWS_SIGNING_THUMBPRINT <sha1>

  LINUX_CATEGORY <category>
)
