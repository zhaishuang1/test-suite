list(APPEND CPPFLAGS -DVERIFICATION)
list(APPEND LDFLAGS -lm)
set(RUN_OPTIONS -s small -g 1250 -l 1000000)
llvm_multisource(XSBench)
