project('lutris',
  meson_version: '>= 0.40.0',
  version: '0.4.10',
  license: 'GPL-3'
)

python = import('python3')
python3_path = python.find_python().path()
purelibdir = python.sysconfig_path('purelib')
install_subdir('lutris', install_dir: purelibdir)

subdir('bin')
subdir('share')
subdir('po')
