cmake_minimum_required(VERSION 3.25)

project(pear_appling C)

include(pear)

add_pear_appling(
  pear_appling
  KEY keet
  NAME Keet
  VERSION 2.2.0
  PUBLISHER Holepunch
  DESCRIPTION "Chat directly with your friends. Send messages, files, high quality videos and photos with no limitations. Private and Encrypted. Always Peer-to-Peer. Never on a server."

  MACOS_IDENTIFIER io.keet.app
  MACOS_CATEGORY public.app-category.developer-tools

  LINUX_CATEGORY AudioVideo
)
