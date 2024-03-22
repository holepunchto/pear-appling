cmake_minimum_required(VERSION 3.25)

project(pear_appling C)

include(pear)

add_pear_appling(
  pear_appling
  KEY "<z32-key>"
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
