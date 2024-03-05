cmake_minimum_required(VERSION 3.25)

project(pear_appling C)

include(pear)

add_pear_appling(
  pear_appling
  KEY keet
  NAME Keet
  VERSION 2.2.0
  AUTHOR Holepunch
  DESCRIPTION "Chat directly with your friends. Send messages, files, high quality videos and photos with no limitations. Private and Encrypted. Always Peer-to-Peer. Never on a server."

  MACOS_IDENTIFIER io.keet.app
  MACOS_CATEGORY public.app-category.developer-tools
  MACOS_ENTITLEMENTS
    com.apple.security.cs.allow-jit
    com.apple.security.cs.allow-unsigned-executable-memory
    com.apple.security.cs.allow-dyld-environment-variables
    com.apple.security.cs.disable-library-validation
    com.apple.security.device.microphone
    com.apple.security.device.audio-input
    com.apple.security.device.camera
  MACOS_SIGNING_IDENTITY "<TODO>"

  WINDOWS_SIGNING_SUBJECT "<TODO>"
  WINDOWS_SIGNING_THUMBPRINT "<TODO>"

  LINUX_CATEGORY AudioVideo
)
