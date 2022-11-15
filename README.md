# MAME4Mobile
ndk只能用17.2.4988734版本， 下好ndk后改makefile里面的ndk路径。
再运行make，生成mame64，手动改成libmame4droid.so（后面这个改到自动流程中)。

目前只在mac下编过，后面会调pc环境。
仅用makefile编安卓so，先不要用它编ios的.a，它里面的ios目前不通。

More information visit my cnblog: https://www.cnblogs.com/ciml/

Available roms: https://wowroms.com/en/roms/list/mame+0.139u1

# License

The native code(iOS&Android) is under terms of GNU General Public License <http://www.gnu.org/licenses>, version 2 or later (GPL-2.0+)

The MAME core library is under MAME license, Visit http://mamedev.org for licensing and usage restrictions. 
