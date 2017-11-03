## 一、Python内置模块的定义：
	这里说的内置模块是指python对性能要求比较高，以C语言编写的模块，通过如下方式可以获得内置模块的名字：
  
```
Python3
>>> import sys
>>> dir(sys)
['__displayhook__', '__doc__', '__excepthook__', '__interactivehook__', '__loade
r__', '__name__', '__package__', '__spec__', '__stderr__', '__stdin__', '__stdou
t__', '_clear_type_cache', '_current_frames', '_debugmallocstats', '_enablelegac
ywindowsfsencoding', '_getframe', '_git', '_home', '_xoptions', 'api_version', '
argv', 'base_exec_prefix', 'base_prefix', 'builtin_module_names', 'byteorder', '
call_tracing', 'callstats', 'copyright', 'displayhook', 'dllhandle', 'dont_write
_bytecode', 'exc_info', 'excepthook', 'exec_prefix', 'executable', 'exit', 'flag
s', 'float_info', 'float_repr_style', 'get_asyncgen_hooks', 'get_coroutine_wrapp
er', 'getallocatedblocks', 'getcheckinterval', 'getdefaultencoding', 'getfilesys
temencodeerrors', 'getfilesystemencoding', 'getprofile', 'getrecursionlimit', 'g
etrefcount', 'getsizeof', 'getswitchinterval', 'gettrace', 'getwindowsversion',
'hash_info', 'hexversion', 'implementation', 'int_info', 'intern', 'is_finalizin
g', 'maxsize', 'maxunicode', 'meta_path', 'modules', 'path', 'path_hooks', 'path
_importer_cache', 'platform', 'prefix', 'ps1', 'ps2', 'set_asyncgen_hooks', 'set
_coroutine_wrapper', 'setcheckinterval', 'setprofile', 'setrecursionlimit', 'set
switchinterval', 'settrace', 'stderr', 'stdin', 'stdout', 'thread_info', 'versio
n', 'version_info', 'warnoptions', 'winver']
>>> sys.builtin_module_names
('_ast', '_bisect', '_blake2', '_codecs', '_codecs_cn', '_codecs_hk', '_codecs_i
so2022', '_codecs_jp', '_codecs_kr', '_codecs_tw', '_collections', '_csv', '_dat
etime', '_functools', '_heapq', '_imp', '_io', '_json', '_locale', '_lsprof', '_
md5', '_multibytecodec', '_opcode', '_operator', '_pickle', '_random', '_sha1',
'_sha256', '_sha3', '_sha512', '_signal', '_sre', '_stat', '_string', '_struct',
 '_symtable', '_thread', '_tracemalloc', '_warnings', '_weakref', '_winapi', 'ar
ray', 'atexit', 'audioop', 'binascii', 'builtins', 'cmath', 'errno', 'faulthandl
er', 'gc', 'itertools', 'marshal', 'math', 'mmap', 'msvcrt', 'nt', 'parser', 'sy
s', 'time', 'winreg', 'xxsubtype', 'zipimport', 'zlib')

Python2
>>> import sys
>>> dir(sys)
['__displayhook__', '__doc__', '__excepthook__', '__name__', '__package__', '__s
tderr__', '__stdin__', '__stdout__', '_clear_type_cache', '_current_frames', '_g
etframe', '_mercurial', 'api_version', 'argv', 'builtin_module_names', 'byteorde
r', 'call_tracing', 'callstats', 'copyright', 'displayhook', 'dllhandle', 'dont_
write_bytecode', 'exc_clear', 'exc_info', 'exc_type', 'excepthook', 'exec_prefix
', 'executable', 'exit', 'flags', 'float_info', 'float_repr_style', 'getcheckint
erval', 'getdefaultencoding', 'getfilesystemencoding', 'getprofile', 'getrecursi
onlimit', 'getrefcount', 'getsizeof', 'gettrace', 'getwindowsversion', 'hexversi
on', 'last_traceback', 'last_type', 'last_value', 'long_info', 'maxint', 'maxsiz
e', 'maxunicode', 'meta_path', 'modules', 'path', 'path_hooks', 'path_importer_c
ache', 'platform', 'prefix', 'ps1', 'ps2', 'py3kwarning', 'setcheckinterval', 's
etprofile', 'setrecursionlimit', 'settrace', 'stderr', 'stdin', 'stdout', 'subve
rsion', 'version', 'version_info', 'warnoptions', 'winver']
>>> sys.builtin_module_names
('__builtin__', '__main__', '_ast', '_bisect', '_codecs', '_codecs_cn', '_codecs
_hk', '_codecs_iso2022', '_codecs_jp', '_codecs_kr', '_codecs_tw', '_collections
', '_csv', '_functools', '_heapq', '_hotshot', '_io', '_json', '_locale', '_lspr
of', '_md5', '_multibytecodec', '_random', '_sha', '_sha256', '_sha512', '_sre',
 '_struct', '_subprocess', '_symtable', '_warnings', '_weakref', '_winreg', 'arr
ay', 'audioop', 'binascii', 'cPickle', 'cStringIO', 'cmath', 'datetime', 'errno'
, 'exceptions', 'future_builtins', 'gc', 'imageop', 'imp', 'itertools', 'marshal
', 'math', 'mmap', 'msvcrt', 'nt', 'operator', 'parser', 'signal', 'strop', 'sys
', 'thread', 'time', 'xxsubtype', 'zipimport', 'zlib')
```
还有两个相关的概念，内建模块和lib库里面的标准库（自带电池）
通常我是这么区分的：

 - 内建模块：在Python3中是指`builtins`模块，在Python2中是指`__builtin__`模块 
 - 标准库：Python安装目录lib库里面的包和模块，这些模块都是用Python编写的
 - 内置模块 ：如上所述，包含了内建模块

## 二、简单对比

 - Python3共有63个内置模块，Python2共有62个内置模块
 - 如下45个模块名字是相同的
 
```
 '_ast',
 '_bisect',
 '_codecs',
 '_codecs_cn',
 '_codecs_hk',
 '_codecs_iso2022',
 '_codecs_jp',
 '_codecs_kr',
 '_codecs_tw',
 '_collections',
 '_csv',
 '_functools',
 '_heapq',
 '_io',
 '_json',
 '_locale',
 '_lsprof',
 '_md5',
 '_multibytecodec'
 '_random',
 '_sha256',
 '_sha512',
 '_sre',
 '_struct',
 '_symtable',
 '_warnings',
 '_weakref',
 'array',
 'audioop',
 'binascii',
 'cmath',
 'errno',
 'gc',
 'itertools',
 'marshal',
 'math',
 'mmap',
 'msvcrt',
 'nt',
 'parser',
 'sys',
 'time',
 'xxsubtype',
 'zipimport',
 'zlib'
```
 - Python2和Python3 不同的模块 
 

```
Python2
 '__main__', 
 '_hotshot',
 '_subprocess',
 'future_builtins'
 'imageop',
 'strop',
 'exceptions',
 
 '_sha',
 '_winreg',
 'cPickle',
 'cStringIO',
 'datetime',
 'imp',
 'operator',
 'signal',
 'thread',
 '__builtin__',

Python3
 '_blake2',
 '_stat',
 '_tracemalloc',
 '_winapi',
 'atexit',
 '_opcode',
 'faulthandler',
 
 '_sha1',
 '_sha3',
 'winreg',
 '_pickle',
 '_string',
 '_datetime',
 '_imp',
 '_operator',
 '_signal',
 '_thread',
 'builtins',
```
 -  模块细节的不同之处，以后工作中再深入了解比较。
