# RT-Thread building script for component

from building import *

cwd = GetCurrentDir()
src = Glob('*.c') + Glob('*.cpp')
CPPPATH = [cwd]

group = DefineGroup('fastlz', src, depend = ['PKG_USING_FASTLZ'], CPPPATH = CPPPATH)

Return('group')
