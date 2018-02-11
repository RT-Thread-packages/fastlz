# RT-Thread building script for component
Import('RTT_ROOT')
from building import *
Import('rtconfig')

cwd = GetCurrentDir()
src = Glob('fastlz.c')
CPPPATH = [cwd]

if GetDepend('FASTLZ_USING_SAMPLE'):
    src += ['fastlz_sample.c']

group = DefineGroup('fastlz', src, depend = ['FASTLZ_USING_SAMPLE'], CPPPATH = CPPPATH)

Return('group')
