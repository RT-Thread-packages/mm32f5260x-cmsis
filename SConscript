from building import *

cwd = GetCurrentDir()

src = []
CPPPATH = [
    cwd + '/CMSIS/Core',
]

group = DefineGroup('CMSIS', src, depend = ['PKG_USING_MM32F5260X_CMSIS'], CPPPATH = CPPPATH)

Return('group')
