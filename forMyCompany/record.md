#
#
#

./symbolicatecrash ./*.crash ./*.app.dSYM > symbol.crash

#if upscript no work then:
xcode-select -print-path
#if not equel:
/Applications/Xcode.app/Contents/Developer/
#then:
export DEVELOPER_DIR=/Applications/XCode.app/Contents/Developer