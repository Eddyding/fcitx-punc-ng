set(FCITX_PUNC_SOURCES
  iniparser/dictionary.c
  iniparser/iniparser.c
  cfgrw.c
  punc-ng.c)
fcitx_add_addon_full(punc-ng SCAN SCAN_PRIV
  SOURCES ${FCITX_PUNC_SOURCES}
  HEADERS punc-ng.h)
